# Projektantrag: YADRMS (Yet Another Discord Remote Management Software)

**Abgabe-Datum:** [TODO]

---

## 1. Projekttitel & Kurzbeschreibung

**Projekttitel:** YADRMS (Yet Another Discord Remote Management Software)

**Kurzbeschreibung:**
YADRMS ist ein Fernwartungs- und -verwaltungssystem, das für Bildungszwecke entwickelt wurde, um moderne Softwarearchitekturen und die Integration verschiedener Technologien zu demonstrieren. Das System ermöglicht es Benutzern, über eine webbasierte Oberfläche einen benutzerdefinierten Python-Client zu erstellen. Dieser Client verbindet sich nach der Ausführung auf einem Zielsystem mit einem Discord-Server und wartet auf Befehle, die über einen Chat-Kanal gesendet werden.

---

## 2. Ausgangslage / Problemstellung

Im Rahmen der Ausbildung ist die praktische Anwendung von theoretischem Wissen entscheidend. Es fehlt oft an Projekten, die eine komplexe, moderne Anwendungsarchitektur mit einem Frontend, einem Backend und der Integration von Drittanbieter-Diensten (wie Discord) greifbar machen. Dieses Projekt schliesst diese Lücke, indem es ein solches System von Grund auf konzipiert und dokumentiert. Die Problemstellung ist also nicht die Lösung eines kommerziellen Problems, sondern die Schaffung eines umfassenden Lern- und Demonstrationsprojekts.

---

## 3. Ziele & Nutzen

**Projektziele:**

- **Primärziel:** Erstellung einer vollständigen und nachvollziehbaren Projektdokumentation gemäss den Modulanforderungen.
- **Sekundärziel:** Entwicklung eines funktionalen Prototyps von YADRMS, bestehend aus einem Next.js-Frontend und einem Python-Backend.
- Demonstration der Fähigkeit, ein komplexes Softwareprojekt zu planen, zu strukturieren und umzusetzen.
- Anwendung und Vertiefung von Kenntnissen in den Bereichen Projektmanagement, Softwarearchitektur und Web-Technologien.

**Nutzen:**

- **Lern- und Bildungswert:** Das Projekt dient als praktisches Beispiel für moderne Softwareentwicklung.
- **Portfolio-Artefakt:** Die Dokumentation und der Code dienen als Nachweis für erworbener Kompetenzen.
- **Modulare Basis:** Die entwickelte Architektur kann als Grundlage für zukünftige Projekte oder Erweiterungen dienen.

---

## 4. Projektumfang / Abgrenzung

**Im Umfang enthalten (In-Scope):**

- Ein Web-Frontend zur Konfiguration und zum Bau des Clients.
- Ein Python-Backend, das den Client-Code dynamisch generiert.
- Die Integration von Discord als C2-Server.
- Eine Auswahl an Basis-Modulen (z.B. Screenshot, Systeminformationen, Clipboard-Zugriff).
- Die vollständige Projektdokumentation aller Phasen.

**Nicht im Umfang enthalten (Out-of-Scope):**

- **Keine kommerzielle Nutzung:** Das Produkt ist ausschliesslich für Bildungszwecke bestimmt.
- **Keine Sicherheitsfunktionen:** Es werden bewusst keine Verschlüsselung oder andere Sicherheitsmechanismen implementiert, um die Komplexität zu reduzieren.
- **Kein produktiver Support:** Das Projekt wird nicht gewartet oder für den Einsatz in produktiven Umgebungen unterstützt.
- **Keine plattformübergreifende Kompilierung:** Der Client wird als Python-Skript generiert und nicht in eine ausführbare Datei für verschiedene Betriebssysteme kompiliert.

---

## 5. Vorgehensweise / Methoden

Das Projekt wird nach einem agilen Ansatz durchgeführt, der Flexibilität ermöglicht. Folgende Methoden und Techniken kommen zur Anwendung:

- **Ideenfindung:** [6-3-5 Methode](2_1_635_Methode_Ideenfindung.md) zur strukturierten Generierung von Projektideen.
- **Analyse & Entscheidung:** [Nutzwertanalyse](6_0_Nutzwertanalyse.md) zur objektiven Bewertung von Lösungsvarianten.
- **Projektplanung:** Erstellung von Projektstrukturplänen und Arbeitspaketen.
- **Projektmanagement:** Regelmässige Status-Updates und Controlling zur Überwachung des Fortschritts.

---

## 6. Zeitplan / Meilensteine (kurz)

Das Projekt gliedert sich in die folgenden Hauptphasen:

1.  **Projektidee & -definition:** Abgeschlossen
2.  **Projektantrag:** In Arbeit / Abschluss mit diesem Dokument
3.  **Hauptstudie & Grobkonzept:** Planung der Architektur und der Kernkomponenten.
4.  **Detailkonzept:** Detaillierte Ausarbeitung der Arbeitspakete und des Risikomanagements.
5.  **Realisation:** Entwicklung des Frontends und Backends.
6.  **Abschluss:** Projektabschluss, Lessons Learned und finale Reflexion.

Die genauen Termine werden in einem separaten Gantt-Diagramm detailliert.

---

## 7. Projektorganisation

- **Projektleiter / Auftraggeber:** Isaac Lins
- **Projekt-Mitarbeiter / Entwicklungs-Assistenz:** Gemini (AI)

Die detaillierte Rollenverteilung und die Kommunikationswege sind im [Informationskonzept](mdc:4_2_Projektkommunikationskonzept.md) und der [Projektorganisation](mdc:4_0_Projektorganisation_final.md) festgehalten.

---

## 8. Ressourcen & Tools

- **Hardware:** Entwicklungsrechner (MacBook)
- **Software & Technologien:**
  - **Frontend:** Next.js, TypeScript, React, ShadCN
  - **Backend:** Python
  - **Kommunikation:** Discord API
  - **Versionierung:** Git, GitHub
- **Entwicklungsumgebung:** Visual Studio Code mit Cursor AI-Assistent
- **Dokumentation:** Markdown, Mermaid.js für Diagramme
