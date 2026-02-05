# Master's Thesis: Dynamic Electricity Pricing Impact Analysis

**Data-driven Analysis of Dynamic Electricity Tariffs**  
*Empirical Study with Regional Energy Supplier Data*

---

## 🇬🇧 English Version

### Overview

This repository documents my Master's thesis research on the effects of dynamic electricity pricing on residential energy consumption patterns. The study uses panel data from a regional German energy supplier to analyze how households respond to time-varying electricity prices compared to fixed-rate tariffs.

**University:** Otto-Friedrich-Universität Bamberg  
**Period:** October 2024 – April 2025  
**Completion:** May 2025

---

### Research Questions

**RQ1:** To what extent does dynamic electricity pricing influence energy consumption patterns compared to fixed tariffs?
- **H1:** Households reduce consumption during peak hours under dynamic pricing

**RQ2:** How do external factors modify the response to dynamic pricing?
- **H2:** Reduced consumption during peak seasons
- **H3a:** PV owners increase midday consumption
- **H3b:** EV owners reduce overall consumption
- **H4:** Larger households show stronger response

---

### Methodology

| Aspect | Details |
|--------|---------|
| **Data Source** | Regional German energy supplier (anonymized) |
| **Period** | October 2024 – April 2025 |
| **Granularity** | 15-minute intervals |
| **Methods** | Propensity Score Matching, Panel Data Models |
| **Software** | R (plm, MatchIt, ggplot2), LaTeX |

---

### Repository Structure

```
thesis/
├── final_thesis.pdf
├── presentation.pdf
└── abstract.pdf
analysis/
├── R/
│   ├── 01_data_cleaning.R
│   ├── 02_psm_matching.R
│   ├── 03_panel_models.R
│   └── 04_visualization.R
├── data/ (anonymized)
└── results/
```

---

### Data & Code Availability

Due to confidentiality agreements with the regional energy supplier and data protection regulations, the original dataset used in this thesis cannot be made publicly available.

In addition, parts of the analysis code are not publicly released, as they are directly linked to proprietary data structures and internal processing pipelines required by the data provider.

This repository therefore serves as:
- A documentation of the research design and methodology  
- A reference for the analytical workflow and model structure  
- An academic showcase of the thesis results  

Aggregated results, figures, and methodological descriptions are provided where possible.  
Access to data or full code may be granted upon reasonable academic request, subject to approval by the data provider and the university.

---

### Citation

```bibtex
@mastersthesis{bao2025dynamic,
  author = {Bao, Menghan},
  title = {The Impact of Dynamic Electricity Pricing on Residential Energy Consumption},
  school = {Otto-Friedrich-Universität Bamberg},
  year = {2025},
  type = {Master's Thesis}
}
```

---

## 🇩🇪 Deutsche Version

### Übersicht

Dieses Repository dokumentiert meine Masterarbeit zur Untersuchung der Auswirkungen dynamischer Stromtarife auf das Energieverbrauchsverhalten privater Haushalte. Die Studie verwendet Paneldaten eines regionalen deutschen Energieversorgers, um zu analysieren, wie Haushalte auf zeitvariable Strompreise im Vergleich zu Festtarifen reagieren.

**Universität:** Otto-Friedrich-Universität Bamberg  
**Zeitraum:** Oktober 2024 – April 2025  
**Abschluss:** Mai 2025

---

### Forschungsfragen

**FF1:** Inwiefern beeinflusst dynamische Preisgestaltung die Verbrauchsmuster im Vergleich zu Festtarifen?
- **H1:** Haushalte reduzieren Verbrauch in Spitzenlastzeiten

**FF2:** Wie modifizieren externe Faktoren die Reaktion auf dynamische Preise?
- **H2:** Reduzierter Verbrauch in der Hauptsaison
- **H3a:** PV-Besitzer erhöhen Mittagsverbrauch
- **H3b:** EV-Besitzer reduzieren Gesamtverbrauch
- **H4:** Größere Haushalte zeigen stärkere Reaktion

---

### Methodik

| Aspekt | Details |
|--------|---------|
| **Datenquelle** | Regionaler Energieversorger (anonymisiert) |
| **Zeitraum** | Oktober 2024 – April 2025 |
| **Granularität** | 15-Minuten-Intervalle |
| **Methoden** | Propensity Score Matching, Paneldaten-Modelle |
| **Software** | R (plm, MatchIt, ggplot2), LaTeX |

---

### Repository-Struktur

```
thesis/
├── masterarbeit_final.pdf
├── präsentation.pdf
└── abstract.pdf
analysis/
├── R/
│   ├── 01_datenbereinigung.R
│   ├── 02_psm_matching.R
│   ├── 03_panel_modelle.R
│   └── 04_visualisierung.R
├── data/ (anonymisiert)
└── results/
```

---

### Daten- und Codeverfügbarkeit

Aufgrund von Vertraulichkeitsvereinbarungen mit dem regionalen Energieversorger sowie datenschutzrechtlicher Vorgaben können die in dieser Arbeit verwendeten Originaldaten nicht öffentlich zugänglich gemacht werden.

Darüber hinaus wird der vollständige Analysecode nicht veröffentlicht, da dieser eng mit proprietären Datenstrukturen und internen Verarbeitungsprozessen des Datengebers verknüpft ist.

Dieses Repository dient daher primär:
- der Dokumentation des Forschungsdesigns und der Methodik  
- als Referenz für den analytischen Workflow und die Modellstruktur  
- als akademische Darstellung der Forschungsergebnisse  

Aggregierte Ergebnisse, Visualisierungen und methodische Beschreibungen werden, soweit möglich, bereitgestellt.  
Ein Zugriff auf Daten oder vollständigen Code kann auf begründete wissenschaftliche Anfrage und vorbehaltlich der Zustimmung des Datengebers sowie der Universität erfolgen.

---

### Zitation

```bibtex
@mastersthesis{bao2025dynamic,
  author = {Bao, Menghan},
  title = {Datengetriebene Analyse dynamischer Stromtarife},
  school = {Otto-Friedrich-Universität Bamberg},
  year = {2025},
  type = {Masterarbeit}
}
```

---

## 📧 Contact

For questions regarding this research, please contact:
- **Email:** [menghanbao1@gmail.com]
- **University:** Otto-Friedrich-Universität Bamberg

---

## 📝 License

This work is licensed under a Creative Commons Attribution-NonCommercial 4.0 International License.

---

*Last updated: February 2026*
