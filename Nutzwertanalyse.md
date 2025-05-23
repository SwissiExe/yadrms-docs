# Nutzwertanalyse – YADRMS

## Ziel
Systematische Bewertung von Lösungsvarianten für das Remote-Management-System YADRMS anhand definierter Kriterien zur objektiven Entscheidungsfindung.

---

## 1. Kriterienauswahl & Gewichtung

| Kriterium            | Gewichtung (%) |
|----------------------|:--------------:|
| Benutzerfreundlichkeit | 25            |
| Kosten                | 15            |
| Entwicklungsaufwand   | 20            |
| Skalierbarkeit        | 15            |
| Wartbarkeit           | 15            |
| Sicherheit            | 10            |

---

## 2. Varianten

- **Variante A:** YADRMS (Discord-basiert, modular, Open Source)
- **Variante B:** Kommerzielles Remote-Management-Tool (z. B. TeamViewer, AnyDesk)
- **Variante C:** Eigenentwicklung ohne Discord (klassische Web-App)

---

## 3. Bewertung der Varianten (1 = schlecht, 5 = sehr gut)

| Kriterium            | Gewichtung | Variante A (YADRMS) | Variante B (Kommerziell) | Variante C (Eigenentwicklung) |
|----------------------|:----------:|:-------------------:|:------------------------:|:-----------------------------:|
| Benutzerfreundlichkeit | 25        | 4                   | 5                        | 3                             |
| Kosten                | 15        | 5                   | 2                        | 4                             |
| Entwicklungsaufwand   | 20        | 4                   | 5                        | 2                             |
| Skalierbarkeit        | 15        | 4                   | 4                        | 3                             |
| Wartbarkeit           | 15        | 4                   | 3                        | 3                             |
| Sicherheit            | 10        | 3                   | 5                        | 4                             |

---

## 4. Nutzwertberechnung

**Formel:** Bewertung × Gewichtung

| Variante             | Nutzwert (Summe) |
|----------------------|:----------------:|
| YADRMS (A)           | 4×25 + 5×15 + 4×20 + 4×15 + 4×15 + 3×10 = **390** |
| Kommerziell (B)      | 5×25 + 2×15 + 5×20 + 4×15 + 3×15 + 5×10 = **400** |
| Eigenentwicklung (C) | 3×25 + 4×15 + 2×20 + 3×15 + 3×15 + 4×10 = **305** |

---

## 5. Grafische Darstellung

```mermaid
bar
    title Nutzwertanalyse Variantenvergleich
    x-axis YADRMS Kommerziell Eigenentwicklung
    y-axis Nutzwert
    "YADRMS" : 390
    "Kommerziell" : 400
    "Eigenentwicklung" : 305
```

---

## 6. Auswertung & Entscheidungsbegründung

Die kommerzielle Lösung (Variante B) erzielt mit 400 Punkten den höchsten Gesamtnutzwert, dicht gefolgt von YADRMS (Variante A) mit 390 Punkten. Die Eigenentwicklung ohne Discord (Variante C) liegt mit 305 Punkten deutlich zurück.

**Entscheidung:**

> Die kommerzielle Lösung bietet das beste Verhältnis aus Aufwand, Sicherheit und Benutzerfreundlichkeit. YADRMS ist jedoch eine sehr gute, kostengünstige und flexible Alternative, insbesondere für individuelle Anpassungen und Lernzwecke. 