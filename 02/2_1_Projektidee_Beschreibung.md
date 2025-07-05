# Projektidee – Beschreibung: YADRMS

## Ziele / Erwarteter Nutzen

Entwicklung und Dokumentation einer klaren, innovativen und umsetzbaren Projektidee für **YADRMS (Yet Another Discord Remote Management Software)**, die den Anforderungen der End-Dokumentation entspricht und einen echten Nutzen für Bildungszwecke stiftet.

## 1. Beschreibung des Grundproblems bzw. Bedarfs

In der modernen IT-Ausbildung und im Bereich der Cybersecurity-Bildung besteht ein wachsender Bedarf an praktischen, hands-on Lernerfahrungen. Traditionelle Lernansätze sind oft zu theoretisch und bieten wenig Gelegenheit, reale Systemarchitekturen und Technologie-Integrationen zu verstehen.

**Identifizierte Probleme:**

Es mangelt an praktischen Demonstrationstools für moderne Softwarearchitekturen. Zusätzlich besteht eine hohe Komplexität beim Erlernen von Client-Server-Kommunikation und API-Integration. Weiterhin fehlen zugängliche Plattformen für das Experimentieren mit modularen Systemen. Schließlich besteht ein Bedarf an sicheren, kontrollierten Umgebungen für Remote-Management-Konzepte.

## 2. Zielgruppenanalyse: Wer profitiert vom Projekt?

### Primäre Zielgruppe:

- **Studierende der Informatik/IT**: Lernen moderne Webentwicklung und Backend-Integration
- **Cybersecurity-Lernende**: Verstehen von C2-Konzepten in kontrollierten Umgebungen
- **Dozenten und Ausbildner**: Praktisches Demonstrationstool für Systemarchitekturen

### Sekundäre Zielgruppe:

- **Hobbyentwickler**: Interesse an Discord-Bot-Entwicklung und modularen Systemen
- **IT-Professionals**: Prototyping und Experimentieren mit neuen Technologien

## 3. Skizzierung der Kernidee und des geplanten Lieferobjekts

### Kernidee

YADRMS ist ein modulares Fernwartungs- und Verwaltungssystem, das Discord als Kommunikationskanal nutzt. Das System ermöglicht es Benutzern, über eine intuitive Weboberfläche einen benutzerdefinierten Python-Client zu konfigurieren und zu generieren.
Dieser Client verbindet sich nach der Ausführung auf einem Zielsystem mit einem Discord-Server und wartet auf Befehle, die über einen Chat-Kanal gesendet werden.

### Geplantes Lieferobjekt

Ein vollständiges, funktionsfähiges System bestehend aus:

1. **Frontend (Next.js/TypeScript)**:

Das Frontend wird mit Next.js und TypeScript umgesetzt. Es bietet eine moderne, reaktive Weboberfläche namens BuilderUI. Über diese Oberfläche können die Einstellungen des Discord-Bots konfiguriert werden. Ausserdem ermöglicht sie die Auswahl und Konfiguration von Modulen sowie ein Dashboard für Echtzeit-Testing und Logging.

2. **Backend (Python)**:

Das Backend wird mit Python umgesetzt. Es bietet einen dynamischen Client-Generator, ein modulares Plugin-System und API-Endpunkte für die Kommunikation mit dem Frontend. Ausserdem wird eine Templating-Engine zur Generierung von Python-Code verwendet.

3. **Generierter Client**:

Der generierte Client ist ein anpassbarer Python-Bot mit Discord-Integration. Er hat über modulare Funktionalitäten wie Screenshots, Systeminformationen und ähnliches.



### Bildungsnutzen:

- **Praktische Anwendung**: Das YADRMS-Projekt bietet einen erheblichen Bildungsnutzen durch die direkte Umsetzung theoretischer Konzepte in die Praxis. Studierende können hier nicht nur theoretisches Wissen erwerben, sondern es unmittelbar in einem funktionsfähigen System anwenden.
- **Technologie-Integration**: Die Integration verschiedener Technologien ermöglicht ein tiefgreifendes Verständnis für moderne Web-Technologien und API-Design-Prinzipien.
- **Sichere Experimentierumgebung**: Besonders wertvoll ist die Bereitstellung einer sicheren Experimentierumgebung, die es ermöglicht, komplexe Konzepte in einer kontrollierten Lernumgebung zu erproben, ohne dabei Produktionsrisiken einzugehen.
- **Lern- und Bildungswert**: Das Projekt dient als praktisches Beispiel für moderne Softwareentwicklung.
- **Portfolio-Artefakt**: Die Dokumentation und der Code dienen als Nachweis für erworbener Kompetenzen.
- **Modulare Basis**: Die entwickelte Architektur kann als Grundlage für zukünftige Projekte oder Erweiterungen dienen.
- **Modulare Entwicklung**: Durch die modulare Entwicklung lernen Teilnehmer die Grundlagen von Plugin-Architekturen und die Bedeutung von Erweiterbarkeit in Softwareprojekten kennen.

### Technische Relevanz:

- **Moderne Architektur**: Das YADRMS-Projekt demonstriert eine moderne Softwarearchitektur durch die klare Trennung von Frontend und Backend. Diese Architektur ermöglicht es Entwicklern, die Prinzipien der Separation of Concerns und der modularen Entwicklung in der Praxis zu erleben und zu verstehen.
- **API-First-Ansatz**: Durch die Implementierung von RESTful-Services und asynchroner Kommunikation zeigt das Projekt die Bedeutung eines API-First-Designs auf. Entwickler lernen hier, wie moderne Webanwendungen durch gut definierte Schnittstellen kommunizieren und wie diese für Skalierbarkeit und Wartbarkeit sorgen.
- **Dynamische Code-Generierung**: Die Template-basierte Programmierung zur Generierung von Python-Clients demonstriert fortgeschrittene Konzepte der Metaprogrammierung. Diese Technik zeigt, wie Code automatisiert erstellt werden kann und welche Möglichkeiten sich daraus für die Entwicklung von Konfigurationstools ergeben.
- **Discord-Integration**: Die Nutzung moderner Chat-APIs für innovative Anwendungen zeigt, wie externe Dienste in eigene Systeme integriert werden können. Diese Integration demonstriert praktische Anwendungen von Webhook-Technologien und Event-driven Architecture in realen Szenarien.

### Effizienzsteigerung:

- **Schnelle Prototyperstellung**: Modulare Zusammenstellung von Funktionalitäten ermöglicht schnelle Prototypen.
- **Wiederverwendbarkeit**: Plugin-System ermöglicht einfache Erweiterungen.
- **Benutzerfreundlichkeit**: Intuitive Weboberfläche reduziert Einarbeitungszeit.

## 5. Abgrenzung: Was gehört nicht zum Projekt?

### Explizit ausgeschlossen:

- **Produktive Nutzung**: System ist ausschließlich für Bildungszwecke konzipiert
- **Sicherheitsfeatures**: Keine Verschlüsselung oder Authentifizierung (bewusste Vereinfachung)
- **Enterprise-Features**: Keine Benutzerverwaltung, Audit-Logs oder Compliance-Features
- **Mobile Apps**: Fokus liegt auf Web-Interface, keine nativen Apps
- **Alternative Plattformen**: Discord ist die einzige unterstützte Kommunikationsplattform

### Bewusste Limitierungen:

- **Kontrollierten Umgebungen**: Nutzung nur auf eigenen/autorisierten Systemen
- **Bildungskontext**: Kein kommerzieller oder produktiver Einsatz
- **Demonstrationszwecke**: Fokus auf Lerneffekt, nicht auf Performance oder Skalierbarkeit

## 6. Erste Gedanken zu Umsetzbarkeit, Tools, Technologien oder Methoden

### Frontend-Technologien:

Für das Frontend wird Next.js (Version kleiner als 14) verwendet, ein React-Framework, das für moderne Webentwicklung genutzt wird. Mit TypeScript wird Typsicherheit erreicht, was die Entwicklung einfacher machen sollte. ShadCN/UI bietet konsistente und moderne UI-Komponenten. Für das Styling wird Tailwind CSS verwendet, ein Utility-first CSS-Framework.

### Backend-Technologien:

Für das Backend wird Python 3.9 oder neuer verwendet, weil es flexibel ist und sich gut für dynamische Code-Generierung eignet. Als REST-API-Frameworks kommen Flask oder FastAPI zum Einsatz, da sie leichtgewichtig und einfach zu nutzen sind. Jinja2 wird als Template-Engine genutzt, um automatisch Python-Code zu erzeugen. Für die Integration mit Discord wird Discord.py verwendet.

### Entwicklungsmethodik:

Die Software wird modular aufgebaut, also mit einem Plugin-System, das sich leicht erweitern lässt. Durch das sogenannte API-First-Design wird das Frontend klar vom Backend getrennt. Es wird testgetriebene Entwicklung genutzt, bei der wichtige Teile der Software automatisch getestet werden. Die Entwicklung erfolgt agil, also in kleinen Schritten mit regelmässigen Prototypen.

### Umsetzungsrisiken und Mitigation:

Ein Risiko ist, dass die Discord-API Einschränkungen hat. Deshalb soll die Dokumentation genau gelesen und ein Rate-Limiting eingebaut werden. Auch das Thema Sicherheit ist wichtig, deshalb wird klar dokumentiert, dass das Projekt nur zu Bildungszwecken gedacht ist. Die Code-Generierung kann komplex werden, daher wird sie Schritt für Schritt entwickelt und gründlich getestet. Damit alles auf verschiedenen Betriebssystemen funktioniert, wird die Software auch plattformübergreifend getestet.
