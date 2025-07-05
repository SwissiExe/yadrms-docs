## 7.1 Zwischenergebnisse

### 7.1.1 Zwischenergebnis 1: Projektplanungsphase abgeschlossen

**Datum:** 02.05.2025  
**Ort:** Berufsschule  
**Teilnehmer:** Isaac Lins (PL), Jay Nagel (AG)

Die Planungsphase des YADRMS-Projekts wurde erfolgreich abgeschlossen. Alle wesentlichen Konzepte und Planungsdokumente sind erstellt und genehmigt. Das Projekt kann nun in die Entwicklungsphase übergehen.

| **Aufgabe**                                                                  | **Verantwortliche/Erledigt von** | **Status** | **Beschreibung**                                                             |
| ---------------------------------------------------------------------------- | -------------------------------- | ---------- | ---------------------------------------------------------------------------- |
| Management Summary erstellt und genehmigt                                    | YADRMS-TEAM/Isaac                | ✅         | Management Summary erstellt und genehmigt                                    |
| Projektidee mit 6-3-5 Methode entwickelt und Hero Journey dokumentiert       | YADRMS-TEAM/Isaac                | ✅         | Projektidee mit 6-3-5 Methode entwickelt und Hero Journey dokumentiert       |
| Vollständiger Projektantrag mit Ausgangslage, Problemanalyse und Zielsetzung | YADRMS-TEAM/Isaac                | ✅         | Vollständiger Projektantrag mit Ausgangslage, Problemanalyse und Zielsetzung |
| Nutzwertanalyse für Konzeptvarianten durchgeführt                            | YADRMS-TEAM/Isaac                | ✅         | Nutzwertanalyse für Konzeptvarianten durchgeführt                            |
| Detailkonzept mit Projektstruktur und Arbeitspaketen definiert               | YADRMS-TEAM/Isaac                | ✅         | Detailkonzept mit Projektstruktur und Arbeitspaketen definiert               |

#### 7.1.1 Nächste Schritte und Planungen

Wir müssen noch die Entwicklungsumgebung einrichten und die BuilderUI-Grundstruktur implementieren.
Dazu möchten wir den ersten funktionalen Modul implementieren (Screenshot).

### 7.1.2 Zwischenergebnis 2: Frontend-Grundstruktur entwickelt

**Datum:** 09.05.2025  
**Ort:** Berufsschule  
**Teilnehmer:** Isaac Lins (PL)

| **Aufgabe**                                                       | **Verantwortliche/Erledigt von** | **Status** | **Beschreibung**                                                  |
| ----------------------------------------------------------------- | -------------------------------- | ---------- | ----------------------------------------------------------------- |
| Setup der Entwicklungsumgebung (Next.js Frontend, Python Backend) | Kenta, Oliver & Joel/Isaac       | ✅         | Setup der Entwicklungsumgebung (Next.js Frontend, Python Backend) |
| ShadCN UI-Komponenten integriert                                  | Kenta, Oliver/Isaac              | ✅         | ShadCN UI-Komponenten integriert                                  |
| Implementierung der BuilderUI-Grundstruktur                       | Joel/Isaac                       | ✅         | Implementierung der BuilderUI-Grundstruktur                       |
| Entwicklung des ersten funktionalen Moduls (Screenshot)           | Joel/Isaac                       | ✅         | Entwicklung des ersten funktionalen Moduls (Screenshot)           |
| Discord-Bot-Konfigurationsformular erstellt                       | Kenta, Oliver/Isaac              | ✅         | Discord-Bot-Konfigurationsformular erstellt                       |

Die Frontend-Grundstruktur wurde erfolgreich implementiert. Die BuilderUI ist funktionsfähig und ermöglicht bereits die grundlegende Konfiguration von Discord-Bot-Einstellungen.
Frontend läuft stabil auf http://localhost:3000 und lässt sich mit `npm run dev` starten.
Diese Seite ist noch nicht fertig, aber wir können bereits die grundlegende Konfiguration von Discord-Bot-Einstellungen generieren.

Mögliche Verbesserungen wären intuitiver Modulauswahl-Interface und bessere visuelle Hierarchie der Elemente.

#### 7.2.1 Nächste Schritte und Planungen

Wir müssen noch die Backend-Entwicklung starten und die API-Routen für Client-Generierung implementieren, da die im Moment noch Manuell gerufen werden müssen.

### 7.1.3 Zwischenergebnis 3: Backend-Integration und erste Module

**Datum:** 16.05.2025  
**Ort:** Berufsschule  
**Teilnehmer:** Isaac Lins (PL)

| **Aufgabe**                                            | **Verantwortliche/Erledigt von** | **Status** |
| ------------------------------------------------------ | -------------------------------- | ---------- |
| Python-Backend mit modularer Architektur implementiert | Joel/Isaac                       | ✅         |
| API-Endpunkte für Client-Generierung erstellt          | Kenta/Isaac                      | ✅         |
| Screenshot-Modul vollständig funktionsfähig            | Joel/Isaac                       | ✅         |
| Clipboard-Modul implementiert und getestet             | Joel/Isaac                       | ✅         |
| System-Info-Modul entwickelt                           | Joel/Isaac                       | ✅         |
| Frontend-Backend-Kommunikation etabliert               | Kenta, Oliver/Isaac              | ✅         |
| Erste End-to-End-Tests erfolgreich                     | Kenta, Oliver & Joel/Isaac       | ✅         |

Das Backend wurde erfolgreich entwickelt und mit dem Frontend integriert. Die ersten Module (Screenshot, Clipboard, System-Info) sind funktionsfähig und können dynamisch in den generierten Client eingebunden werden.
Wir haben 3/6 geplanten Module fertiggestellt und können diese auch auf Windows 10/11 benutzen.
Die Client-Generierung funktioniert in durchschnittlich 2,3 Sekunden und ein Test-Bot erfolgreich auf 2 verschiedenen Systemen (Windows 10/11) getestet.

Unser PoC ist erfolgreich und wir können die ersten Module in den generierten Client einfügen.

#### 7.3.1 Nächste Schritte und Planungen

Wir müssen noch die fehlenden Module implementieren (File-Management, Process-Control, Network-Info) und die Tests durchführen.

### 7.1.4 Zwischenergebnis 4: Finalisierung und Testphase

**Datum:** 23.05.2025  
**Ort:** Berufsschule  
**Teilnehmer:** Isaac Lins (PL)

| **Aufgabe**                                          | **Verantwortliche/Erledigt von** | **Status** |
| ---------------------------------------------------- | -------------------------------- | ---------- |
| Alle 6 Module vollständig implementiert und getestet | Joel/Isaac                       | ✅         |
| Komponententests für alle Module durchgeführt        | Joel/Isaac                       | ✅         |
| Integrationstests erfolgreich abgeschlossen          | Kenta & Oliver/Isaac             | ✅         |
| Performance-Optimierung implementiert                | YADRMS-Team/Isaac                | ✅         |
| Finale EULA und Dokumentation erstellt               | YADRSM-Team/Isaac                | ✅         |

Das YADRMS-Projekt nähert sich dem Abschluss. Alle geplanten Module sind implementiert und umfassende Tests wurden durchgeführt. Das System ist stabil und bereit für die finale Dokumentation.

Alle 6 Module funktionsfähig: Screenshot, Clipboard, System-Info, File-Management, Process-Control, Network-Info. Die Performance ist mit durchschnittlich 1,8 Sekunden für die Client-Generierung sehr gut. Das System wurde erfolgreich auf Windows 10/11, macOS und Ubuntu getestet.

#### 7.4.1 Nächste Schritte und Planungen

Fertigstellung der Projektdokumentation und Erstellung des Abschlussberichts mit Soll-Ist-Vergleich. Dokumentation der Lessons Learned und Vorbereitung der finalen Präsentation.

### 7.1.5 Zusammenfassung aller Zwischenergebnisse

#### Gesamtprojektfortschritt

Die modulare Architektur hat sich als sehr erfolgreich erwiesen.
Dies war Sinnvoll, da wir so flexibel sein können und neue Module einfach hinzufügen können. Dies dauerte eine Weile, da wir noch nicht wussten, wie wir die Module implementieren sollten, doch lohnte sich.
Plattformübergreifende Kompatibilität erforderte mehr Aufwand als geplant.
Umfassende Tests waren entscheidend für die Projektqualität und die Kombination aus Next.js und Python erwies sich als sehr effektiv.
