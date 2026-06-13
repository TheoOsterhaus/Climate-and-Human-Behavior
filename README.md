## Presentation Structure

| Slide | Section | Content |
|---|---|---|
| 1 | — | Title slide |
| 2 | — | Outline |
| 3 | Motivation | Humanity's Greatest Threat: GDP losses, free-rider problem |
| 4 | Motivation | Positioning: Impact & connection to Nature paper |
| 5 | Motivation | Research Questions (3 RQs) |
| 6 | Study Design | Sample & measurement approach |
| 7 | Study Design | Sample characteristics vs. US population (Table A.1) |
| 8 | Study Design | Wave 1: Donation decision (atmosfair) |
| 9 | Study Design | Wave 1: Behaviour determinants & norm measures |
| 10 | Study Design | Wave 2: Information experiment overview (PAP) |
| 11 | Study Design | Wave 2: Information treatments (Figure B.5) |
| 12 | Results | Heterogeneity in willingness to fight global warming |
| 13 | Results | Determinants of climate behaviour (Table 1) |
| 14–16 | Results | Misperception of norms & causal treatment effects |
| 17 | Results | Treatment effect heterogeneity: prior < actual (Table 3) |
| 18 | Results | Heterogeneity: reducing polarisation (Figure) |
| 19 | Backup | Treatment effects on policy support & activism (Table 4) |
| 20 | Conclusion | Summary & policy implications |
| 21 | Backup | Key problems of the RCT design |
| 22–23 | — | Bibliography (I & II) |

---

## Paper Summary

### Research Questions

1. **Behavioural Determinants** — What factors drive individual willingness
   to act against global warming?
2. **Social Norms** — Do misperceptions of social norms influence climate
   action, and if so, how?
3. **Intervention Effect** — Can correcting misperceived norms increase
   support for climate policies?

### Study Design

#### Two-Wave Survey (Pureprofile)

| Wave | Date | n | Purpose |
|---|---|---|---|
| Wave 1 | March 2021 | 2,000 | Descriptive analysis, baseline measures |
| Wave 2 | April 2021 | 6,000 | Information experiment (RCT) |

- Quota-based sampling: representative of US adults
  (gender, age, education, region)
- Respondents could only participate in **one** wave

#### Outcome Variable: Incentivised Donation
Participants divide **$450** between themselves and
**atmosfair** (CO₂ offset charity).
Probabilistic incentive scheme: decisions of **25 randomly chosen**
participants are implemented.

#### Experimental Treatments (Wave 2)

| Group | Treatment | Information Shown |
|---|---|---|
| Control | None | — |
| Behavior Treatment | Perceived behavior correction | Share of Americans who *try* to fight global warming (**71%**) |
| Norms Treatment | Perceived norms correction | Share of Americans who think people *should* fight global warming (**87%**) |

The treatment values are the **actual answers from Wave 1**.

---

## Main Results

### 1. Misperception of Social Norms (Wave 1)
Americans **systematically underestimate** the share of their fellow
citizens who act or endorse climate action:

| | Actual | Perceived | Gap |
|---|---|---|---|
| Trying to fight global warming | ~71% | ~43% | **−28 pp** |
| Think people should fight global warming | ~87% | ~65% | **−22 pp** |

### 2. Social Norms Predict Pro-Climate Behaviour (Table 1)
Perceived social norms are **as strong a predictor** of donations
as universal moral values and key economic preferences
(all predictors z-scored):

| Predictor | Effect on Donation ($) |
|---|---|
| Behavior belief | 12.07*** |
| Norms belief | 14.37*** |
| Altruism | 51.36*** |
| Relative universalism | 23.50*** |
| Patience | 15.14*** |

### 3. Causal Treatment Effects on Donations (Wave 2)

| Treatment | Effect ($) | Significance |
|---|---|---|
| Behavior Treatment | +5.0 (≈ 13% of mean) | ** |
| Norms Treatment | +3.2 (≈ 8% of mean) | * |

### 4. Treatment Effect Heterogeneity (Table 3)
Positive effects are **almost entirely driven** by individuals whose
prior beliefs were **below the actual shares** (belief updating confirmed):

| | Prior < Actual | Prior ≥ Actual |
|---|---|---|
| Behavior Treatment | 14.93** | 5.23 (n.s.) |
| Norms Treatment | 19.11*** | 4.75 (n.s.) |

### 5. Effects on Policy Support (Table 4, Backup)

| Treatment | Policies | Activism | All |
|---|---|---|---|
| Behavior Treatment | 0.088*** | 0.039 | 0.061** |
| Norms Treatment | 0.066** | 0.012 | 0.034 |

### 6. Heterogeneity: Climate Skeptics
- Strongest treatment effects among individuals **skeptical** about
  climate change
- Behavior treatment works especially well: peer information without
  moralizing → avoids backlash
- Skeptics are most surprised to learn their views are a **minority position**
- Key implication: **Belief correction reduces political polarization**

---

## Connection to the Nature Climate Change Paper

> **Andre, P., Boneva, T., Chopra, F., & Falk, A. (2024a).**
> *Globally representative evidence on the actual and perceived support
> for climate action.*
> Nature Climate Change, 14(3), pp. 253–259.
> DOI: [10.1038/s41558-024-01925-3](https://doi.org/10.1038/s41558-024-01925-3)

| Dimension | ReStat Paper (2024b) | Nature Paper (2024a) |
|---|---|---|
| **Sample** | ~8,000 US adults | ~130,000 persons, 125 countries |
| **Method** | RCT (causal identification) | Representative descriptive survey |
| **Core finding** | Correcting misperceptions *causally* raises donations | Pluralistic ignorance exists *globally* |
| **Contribution** | **Causal proof** | **Global scale & external validity** |

**The Bridge:**
- The **ReStat paper** proves the mechanism causally (USA)
- The **Nature paper** shows the problem is universal (125 countries)
- Together: strong case for **globally scalable norm-correction interventions**

---

## Key Limitations & RCT Threats (Slide 21)

| Threat | Description |
|---|---|
| **Spillover effects** | Treatment effects may spread to control group |
| **John Henry effects** | Control group tries to compensate |
| **Hawthorne effects** | Participants behave more sustainably because observed |
| **Social desirability bias** | Inflated self-reported climate behaviour |
| **Experimenter demand effects** | Addressed by obfuscating purpose & incentivising donation |

---

## LaTeX Setup

### Beamer Configuration

```latex
\usetheme{Madrid}
\author{Theo Osterhaus, 7443693}
\institute{Faculty of Management, Economics and Social Sciences\\
           Universität zu Köln}
\date{June 2026}

\usepackage{booktabs}       % professional table formatting
\usepackage{siunitx}        % number alignment in tables
\usepackage{graphicx}       % include figures
\usepackage{hyperref}       % clickable links & DOIs
\usepackage{natbib}         % bibliography management
\usepackage{xcolor}         % custom colors
\usepackage{caption}        % figure/table captions

pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex

@misc{andre2021pap,
  author       = {Andre, Peter and Boneva, Teodora and
                  Chopra, Felix and Falk, Armin},
  title        = {Climate Change Behavior and Social Norms},
  year         = {2021},
  month        = sep,
  howpublished = {AEA RCT Registry. RCT ID: AEARCTR-0007542},
  url          = {https://doi.org/10.1257/rct.7542-2.1}
}

@article{andre2024misperceived,
  author  = {Andre, Peter and Boneva, Teodora and
             Chopra, Felix and Falk, Armin},
  title   = {Misperceived Social Norms and Willingness to
             Act Against Climate Change},
  journal = {The Review of Economics and Statistics},
  year    = {2024},
  pages   = {1--46},
  issn    = {0034-6535},
  doi     = {10.1162/rest_a_01468},
  url     = {https://doi.org/10.1162/rest_a_01468}
}

@article{andre2024global,
  author  = {Andre, Peter and Boneva, Teodora and
             Chopra, Felix and Falk, Armin},
  title   = {Globally representative evidence on the actual
             and perceived support for climate action},
  journal = {Nature Climate Change},
  year    = {2024},
  volume  = {14},
  number  = {3},
  pages   = {253--259},
  issn    = {1758-6798},
  doi     = {10.1038/s41558-024-01925-3},
  url     = {https://doi.org/10.1038/s41558-024-01925-3}
}

@report{ipcc2023,
  author      = {{Intergovernmental Panel on Climate Change (IPCC)}},
  title       = {Climate Change 2023: Impacts, Adaptation, and
                 Vulnerability. Working Group II Contribution to
                 the Sixth Assessment Report},
  year        = {2023},
  url         = {https://www.ipcc.ch/report/ar6/wg2/}
}

@article{lorenzoni2006,
  author  = {Lorenzoni, Irene and others},
  title   = {Cross-National Comparisons of Image Associations with
             ``Global Warming'' and ``Climate Change'' Among Laypeople
             in the United States of America and Great Britain},
  journal = {Journal of Risk Research},
  year    = {2006},
  volume  = {9},
  number  = {3},
  pages   = {265--281},
  doi     = {10.1080/13669870600613658}
}


