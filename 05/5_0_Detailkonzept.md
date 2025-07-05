## 5. Detailkonzept

Das Detailkonzept konkretisiert die im Grobkonzept definierte Lösung und beschreibt die technische, funktionale und organisatorische Umsetzung des Projekts im Detail. Es dient als verbindliche Grundlage für die Realisierung des Projekts und stellt sicher, dass alle Stakeholder ein gemeinsames Verständnis der geplanten Lösung haben.

### 5.0.1 Technische Architektur, Systemaufbau und Workflow

Das Frontend basiert auf Next.js 14 als modernem React-Framework. TypeScript wird durchgängig eingesetzt, um Typsicherheit zu gewährleisten und die Entwicklererfahrung durch intelligente Code-Vervollständigung und Fehlerprävention zu verbessern. ShadCN UI wird für die Bereitstellung moderner, barrierefreier UI-Komponenten eingesetzt.

Das Backend wird in Python 3.8+ entwickelt und nutzt die Flexibilität dieser Sprache für die dynamische Code-Generierung. Die modulare Architektur ermöglicht eine einfache Erweiterung um neue Funktionalitäten. Next.js API Routes werden für die REST-API-Implementierung verwendet, wodurch eine nahtlose Integration zwischen Frontend und Backend gewährleistet wird.

Die API-Schicht, implementiert durch Next.js API Routes, fungiert als Vermittler zwischen Frontend und Backend. Sie verarbeitet alle Anfragen, validiert Eingaben und koordiniert die Kommunikation mit dem Python Script Generator. Dieser Generator stellt das Herzstück des Systems dar und ist verantwortlich für die dynamische Erstellung massgeschneiderter Python-Clients basierend auf den Benutzerkonfigurationen.

Der generierte Python-Client wird als eigenständige Anwendung bereitgestellt, die auf dem Zielsystem ausgeführt wird. Nach der Aktivierung verbindet sich dieser Client mit dem konfigurierten Discord-Server und wartet auf Befehle, die über Chat-Kanäle gesendet werden. Diese Architektur ermöglicht eine vollständige Trennung von Konfiguration und Ausführung. Der User muss nicht Coden können, um die Funktionalität des Systems zu nutzen.

Die Anwendung verwendet JSON-Dateien für die Speicherung von Einstellungen, was eine einfache Konfiguration und Wartung ermöglicht. Diese dateibasierte Herangehensweise reduziert die Komplexität und macht externe Datenbanksysteme überflüssig
Die Discord-API bildet das Herzstück der Kommunikationsfunktionalität und ermöglicht die nahtlose Integration mit Discord-Servern. Node.js wird für die Ausführung der Anwendung verwendet, während Playwright für End-to-End-Tests und Jest sowie Mocha für Unit-Tests eingesetzt werden.

Die Bot-Konfigurationsfunktion ermöglicht es Benutzern, Discord-Token, Guild-IDs und gewünschte Module über eine intuitive Weboberfläche zu definieren. Das System speichert die Konfiguration in einer strukturierten JSON-Datei. Diese Konfiguration bildet die Grundlage für die anschliessende Client-Generierung.
Nach der Speicherung des JSONs kann der Benutzer die Kompilierung starten, welche beim Backend API-Aufrufe an den Python-Builder ausgelöst. Dieser liest die gespeicherten Einstellungen, wählt die entsprechenden Module aus und generiert einen vollständigen Python-Client. Der generierte Code wird im OUTPUT-Verzeichnis bereitgestellt und kann vom Benutzer heruntergeladen werden.

Nach dem Download startet der Benutzer das generierte Python-Skript auf dem Zielsystem. Der Bot verbindet sich automatisch mit Discord, erstellt, verwaltet den konfigurierten Channel und wartet auf eingehende Befehle. Die Kommunikation erfolgt über standardisierte Discord-Kommandos. 
Die Remote-Steuerung erfolgt durch das Senden spezifischer Befehle im Discord-Channel. Ein Befehl wie ".screenshot" wird vom Bot empfangen, das entsprechende Modul ausgeführt und das Ergebnis als Nachricht oder Datei im Channel gepostet. Diese intuitive Bedienung ermöglicht eine einfache Fernsteuerung ohne technische Vorkenntnisse. Unterstützte Module umfassen Screenshots, Blue Screen Of Death, Clipboard-Operationen, Systeminformationen und einen vollen Bash shell auf dem Zielsystem.

Das System unterstützt die einfache Erweiterung um neue Module. Entwickler können neue Python-Module im entsprechenden Verzeichnis ablegen, und diese erscheinen automatisch in der Benutzeroberfläche. Diese Flexibilität ermöglicht eine kontinuierliche Weiterentwicklung und Anpassung an neue Anforderungen.

