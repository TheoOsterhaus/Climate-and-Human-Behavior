# Projekt: Präsentation zu "Misperceived Social Norms and Willingness to Act Against Climate Change"

## Projektübersicht

Dieses Projekt enthält eine wissenschaftliche Präsentation (LaTeX Beamer) zum Forschungs paper von Andre et al. (2024). Das Paper untersucht in einem Feldexperiment mit etwa 6.000 US-Amerikanern, wie sich die Korrektur fehlwahrgenommener sozialer Normen auf die Spendenbereitschaft für Klimaschutz auswirkt.

**Zentrale Forschungsfrage:** Unterschätzen Menschen die Bereitschaft ihrer Mitbürger, gegen den Klimawandel zu handeln? Und kann eine Information über die tatsächliche Handlungsbereitschaft das eigene Verhalten beeinflussen?

## Inhalt des Projekts

```
.
├── README.md              # Diese Datei
├── main.tex               # Hauptdatei der Beamer-Präsentation
├── tables/                # LaTeX-Tabellen (Table 1–4)
│   ├── table1.tex
│   ├── table2.tex
│   ├── table3.tex
│   └── table4.tex
└── figures/               # Abbildungen (8 Figures aus dem Paper)
    └── ...
```

*Die Ordner `tables/` und `figures/` enthalten die importierten Elemente für die Präsentation.*

## Paper-Zusammenfassung

**Titel:** Misperceived Social Norms and Willingness to Act Against Climate Change  
**Autoren:** Andre, P., B. Enke, J. J. Van der Weele (2024)  
**Methode:** Randomisiertes Feldexperiment (USA, N ≈ 6.000)  
**Behandlungen:** Behavioral Treatment (Information über tatsächliche Handlungsbereitschaft) und Norms Treatment (soziale Vergleichsinformationen)

### Kernergebnisse

1. **Perception Gap:** Menschen unterschätzen systematisch, wie viele ihrer Mitbürger bereit sind, gegen den Klimawandel zu handeln.

2. **Treatment-Effekt:** Die Korrektur dieser Fehlwahrnehmung (Behavioral Treatment) erhöht die Spendenbereitschaft signifikant um 11 Prozentpunkte.

3. **Heterogenität:** Der Effekt ist stärker bei Personen, deren Prior-Überzeugungen unter dem tatsächlichen Durchschnitt liegen.

4. **Theoretischer Mechanismus:** Das Ergebnis ist konsistent mit dem Modell der *conditional cooperation* — Menschen sind eher bereit zu handeln, wenn sie glauben, dass andere ebenfalls handeln.

### Replizierte Tabellen

Die Präsentation enthält die vier Haupttabellen des Papers in LaTeX:
- **Table 1:** Main treatment effects
- **Table 2:** Heterogeneity by prior beliefs
- **Table 3:** Full sample with controls
- **Table 4:** Secondary outcomes (Policies, Activism)

## Verbindung zur globalen Studie (Nature Climate Change 2024)

Das Projekt stellt eine Verbindung zur globalen Studie her, die 2024 in *Nature Climate Change* veröffentlicht wurde:

> **Falk, T. et al. (2024).** "People underestimate climate-friendly behavior of fellow citizens." *Nature Climate Change*, 14, 996–1004. DOI: 10.1038/s41558-024-01925-3

### Gemeinsamkeiten

| Aspekt | Andre et al. (2024) | Nature CC (2024) |
|---|---|---|
| **Stichprobe** | ~6.000 USA | ~130.000 Personen, 125 Länder |
| **Kernmechanismus** | Fehlwahrnehmung sozialer Normen | Pluralistische Ignoranz |
| **Hauptbefund** | Korrektur erhöht Spendenbereitschaft | Unterschätzung ist global verbreitet |
| **Theoretische Basis** | Conditional Cooperation, Free-Riding | Identisch |

### Unterschiede

- **Andre et al.** liefern **kausale** Evidenz durch ein Feldexperiment
- **Nature CC** liefern **deskriptive**, global repräsentative Evidenz

Die Verbindung zeigt: Der Perception Gap ist nicht nur in den USA vorhanden, sondern ein globales Phänomen. Die US-Studie liefert den kausalen Beweis, dass das Schließen dieser Lücke Verhalten verändert.

## Struktur der Präsentation

1. **Einleitung & Motivation**
   - Das Free-Rider-Problem beim Klimaschutz
   - Pluralistische Ignoranz als Hindernis

2. **Experimentelles Design**
   - Stichprobe & Ablauf
   - Treatment-Gruppen (Behavioral vs. Norms)
   - Messung der Outcomes

3. **Hauptergebnisse**
   - Table 1–4: Regressionsergebnisse
   - 8 Figures aus dem Paper

4. **Heterogenitätsanalyse**
   - Unterschiede nach Prior-Überzeugungen
   - Wirkmechanismen

5. **Politikimplikationen**
   - Kommunikationsstrategien
   - Einbettung in globale Befunde

## Verwendete LaTeX-Pakete

```latex
\usepackage{beamertheme metropolis}  % Modernes Beamer-Theme
\usepackage{booktabs}                % Für Tabellen (toprule, midrule, bottomrule)
\usepackage{graphicx}                % Einbindung von Grafiken
\usepackage{amsmath, amssymb}        % Mathematische Notation
\usepackage{tabularx}                % Flexible Tabellenspalten
\usepackage{geometry}                % Seitenlayout
\usepackage{xcolor}                  % Farben
```

## Quellen

### Primärliteratur

- Andre, P., Enke, B., & Van der Weele, J. J. (2024). *Misperceived Social Norms and Willingness to Act Against Climate Change*. Unveröffentlichtes Working Paper.

- Falk, T., et al. (2024). People underestimate climate-friendly behavior of fellow citizens. *Nature Climate Change*, 14, 996–1004. https://doi.org/10.1038/s41558-024-01925-3

### Theoretischer Hintergrund

- Fehr, E., & Gächter, S. (2000). Fairness and retaliation: The economics of reciprocity. *Journal of Economic Perspectives*, 14(3), 159–181.

- Cialdini, R. B., & Goldstein, N. J. (2004). Social influence: Compliance and conformity. *Annual Review of Psychology*, 55, 591–621.

---

*Erstellt für eine studentische Präsentation im Rahmen eines Seminars zu Verhaltensökonomie und Klimapolitik.*