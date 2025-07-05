## 5.1 Nutzwertanalyse

Wir haben uns entschieden, eine Nutzwertanalyse durchzuführen, um überhaupt zu sehen, ob es sich lohnt, unsere Lösung zu entwickeln.
Unser Gedankengang war es, uns zu fragen, wer unsere Lösung nutzen würde, und warum sie unsere Lösung nutzen würden.

### 5.1.1 Kriterienauswahl & Gewichtung

Wir haben uns entschieden, die folgenden Kriterien zu berücksichtigen:

- Benutzerfreundlichkeit
- Entwicklungsaufwand
- Skalierbarkeit
- Kosten

Wenn wir die Kriterien in Prozent darstellen, erhalten wir folgende Gewichtung:

| Kriterium              | Gewichtung (%) |
| ---------------------- | :------------: |
| Benutzerfreundlichkeit |       60       |
| Entwicklungsaufwand    |       10       |
| Skalierbarkeit         |       20       |
| Kosten                 |       10       |

Dabei ist es uns sehr wichtig, dass die Lösung benutzerfreundlich ist und wir uns nicht auf die Entwickler selbst konzentrieren müssen. Wir wollen, dass der User die Lösung so einfach wie möglich nutzen kann.

### 5.1.2 Varianten

Diese Varianten haben wir in der Nutzwertanalyse berücksichtigt, bzw. Warum würden die Nutzer unsere Lösung nutzen?

**Variante A: YADRMS (Discord-basiert, modular, Open Source, Gratis)**

Wir bieten eine Discord-basiert, modulare Lösung an. Diese Lösung ist für den User benutzerfreundlich und einfach zu bedienen. Dazu ist es Gratis und Open Source. Wir berücksichtigen, dass der User die Lösung nutzen kann, ohne dass er programmieren muss.

**Variante B: Kommerzielles Remote-Management-Tool (z. B. TeamViewer, AnyDesk)**

Andere bieten eine kommerzielle Lösung an, die von einem Unternehmen entwickelt und betrieben wird. Diese Lösung ist für den User sehr benutzerfreundlich und einfach zu bedienen. Dies folgt, dass es weder Gratis noch Open Source ist. Sie berücksichtigen auch wie wir, dass der User die Lösung nutzen kann, ohne dass er programmieren muss. Die Kosten sind sehr hoch und die Lösung ist nicht modular. Falls man eigene Module/Funktionen möchte, ist dies Höchstwahrscheinlich nicht möglich.

**Variante C: Eigenentwicklung ohne Discord (klassische Web-App)**

Etwas was immer eine Lösung ist, ist es selbst zu entwickeln. Diese Lösung ist für den User extrem benutzerunfreundlich und meistens nicht möglich. Diese Lösung kann modular und skalierbar sein, aber es ist sehr aufwändig und teuer.
Dazu muss man sich auf die Entwicklung konzentrieren und nicht auf die Nutzung. Nicht jeder kann das.

Diese Bewertung ist subjektiv und basiert auf unserer Erfahrung.

| Kriterium              | Gewichtung | Variante A (YADRMS) | Variante B (Kommerziell) | Variante C (Eigenentwicklung) |
| ---------------------- | :--------: | :-----------------: | :----------------------: | :---------------------------: |
| Benutzerfreundlichkeit |     60     |          5          |            5             |               3               |
| Entwicklungsaufwand    |     20     |          5          |            5             |               1               |
| Skalierbarkeit         |     20     |          4          |            1             |               2               |
| Kosten                 |     10     |          5          |            1             |               5               |

> LEGENDE: (1 = schlecht, 5 = sehr gut)

### 5.1.3 Nutzwertberechnung

**Formel:** Bewertung × Gewichtung

| Variante             |          Nutzwert (Summe)           |
| -------------------- | :---------------------------------: |
| YADRMS (A)           | 5×60 + 5×10 + 4×20 + 5×10 = **490** |
| Kommerziell (B)      | 5×60 + 5×10 + 1×20 + 1×10 = **340** |
| Eigenentwicklung (C) | 3×60 + 1×10 + 2×20 + 5×10 = **250** |

Die YADRMS Lösung (Variante A) erzielt mit 490 Punkten den höchsten Gesamtnutzwert, dicht gefolgt von Eigenentwicklung ohne Discord (Variante C) mit 250 Punkten. Die kommerzielle Lösung (Variante B) liegt mit 340 Punkten deutlich zurück.

Diese Bewertung zeigt uns, dass subjektiv gesehen YADRMS (Variante A) die beste Lösung ist.
