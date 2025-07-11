## 2.1 Projektidee

### 2.1.1 Ziele und erwarteter Nutzen

Die Entwicklung und Dokumentation einer klaren und umsetzbaren Projektidee für YADRMS steht im Zentrum dieses Vorhabens. Dabei liegt der Fokus auf einer praxisorientierten Lernumgebung, die theoretisches Wissen in greifbare Anwendungen umsetzt.

### 2.1.2 Beschreibung des Problems und Bedarfs

In der modernen IT-Ausbildung und im Bereich der Cybersecurity-Bildung fehlen praktische, hands-on Lernerfahrungen. Traditionelle Lernansätze sind oft zu theoretisch und bieten wenig Gelegenheit, echte Systemarchitekturen und Technologie-Integrationen zu verstehen.

Die identifizierten Probleme umfassen einen Mangel an praktischen Demonstrationstools für moderne Softwarearchitekturen. Ausserdem ist das Erlernen von Client-Server-Kommunikation und API-Integration komplex. Es fehlen zugängliche Plattformen für das Experimentieren mit modularen Systemen. Gleichzeitig besteht ein Bedarf an sicheren, kontrollierten Umgebungen für Remote-Management-Konzepte.

### 2.1.3 Zielgruppenanalyse

Studierende der Informatik und IT bilden die Hauptzielgruppe. Sie können durch das Projekt moderne Webentwicklung und Backend-Integration lernen. Cybersecurity-Lernende profitieren vom Verständnis von C2-Konzepten (Command & Control) in kontrollierten Umgebungen. Dozenten und Ausbildner erhalten ein praktisches Demonstrationstool für Systemarchitekturen.
Hobbyentwickler mit Interesse an Discord-Bot-Entwicklung und modularen Systemen sowie IT-Professionals, die Prototyping und Experimentieren mit neuen Technologien betreiben, ergänzen die Zielgruppe.

### 2.1.4 Kernidee und geplantes Ergebnis

**Kernidee:**
Wir wollten ein modulares System für die Fernwartung und Verwaltung, das Discord als Kommunikationsweg nutzt. Das System sollte es Benutzern ermöglichen, über eine einfache Weboberfläche einen benutzerdefinierten Python-Client zu konfigurieren und zu erstellen. Dieser Client verbindet sich nach der Ausführung auf einem Zielsystem mit einem Discord-Server und wartet auf Befehle, die über einen Chat-Kanal gesendet werden.

Als geplantes Ergebnis wollten wir ein Benutzerfreundliches, Intiuitives Webinterface, dass es den Nutzern ermöglicht, einen Gerät zu kontrollieren, ohne vorwissen haben zu müssen.

Wenn der Benutzer einen Befehl sendet, soll das System den Befehl an das Zielsystem weiterleiten und das Ergebnis zurückgeben.

### 2.1.5 Projektabgrenzung

**Was nicht Teil des Projekts ist:**
Das System ist ausschliesslich für Bildungszwecke gedacht und nicht für produktive Nutzung vorgesehen. Dies den Nutzern zu sagen ist sehr wichtig, da YADRMS sonst in böser Absicht benutzt werden könnte.

Für den Kommunikationskanal hätten wir eigenlich 2 Optionen:
- Einen C2 Server selbst Coden
- Einen Drittanbieter service benutzen und mit unserem API verbinden

Wir haben uns für die zweite Option entschieden, da wir uns nicht dafür interessieren, einen eigenen C2 Server zu entwickeln. Wir wollten einen Service, der uns die Kommunikation mit dem Zielsystem übernimmt.

### 2.1.6 Umsetzungsplanung

Für die Umsetzung haben wir uns für die folgenden Technologien entschieden:

**Frontend:**
Next.js 14 wird als React-Framework für moderne Webentwicklung eingesetzt, ergänzt durch TypeScript für Typsicherheit und bessere Entwicklererfahrung. ShadCN/UI stellt konsistente, moderne UI-Komponenten bereit, während Tailwind CSS als Utility-first CSS-Framework dient.

**Backend:**
Python 3.9+ bietet die nötige Flexibilität für dynamische Code-Generierung. Flask oder FastAPI werden als leichtgewichtige REST-API-Frameworks eingesetzt. Jinja2 dient als Template-Engine für Python-Code-Generierung und Discord.py für Discord-API-Integration.

**Entwicklungsmethodik:**
Die modulare Architektur ermöglicht ein Plugin-basiertes System für einfache Erweiterbarkeit. Das API-First-Design gewährleistet klare Trennung zwischen Frontend und Backend.

Wichtig war Modularität, da wir später andere Tech-savvy Users die möglichkeit geben wollten, eigene Module zu erstellen.

### 2.1.7 Hero Journey

Wir haben uns inspiriert und ein Hero Journey erstellt.
Im Hero Journey haben wir eine mögliche Benutzerreise dargestellt.
Bei unserem Beispiel haben wir einen Benutzer, der mehrere Systeme verwaltet.
Leider hat er ein Problem. Ein kritisches Sicherheitsproblem wird bekannt - eine Schwachstelle in einer wichtigen Abhängigkeit, die sofort auf allen Servern gepatcht werden muss.

[!Hero Journey](2_2_hero-journey.pdf)
