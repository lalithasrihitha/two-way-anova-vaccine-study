# Two-Way ANOVA: Vaccine Type and Age Group

## Overview
This project demonstrates the application of **two-way ANOVA** in R to evaluate how two categorical factors—**Vaccine Type** and **Age Group**—influence a continuous outcome variable (**antibody titer**).

The analysis is based on a simulated clinical trial dataset and focuses on identifying:
- Main effects of each factor
- Interaction effects between factors

---

## Dataset
- **Source:** Simulated clinical trial dataset
- **Sample size:** 40 participants
- **Factors:**
  - Vaccine_Type: Vaccine_A, Vaccine_B
  - Age_Group: Young (18–40), Elderly (60+)
- **Outcome variable:**
  - Antibody_Titer (continuous)

---

## Research Questions
1. Does vaccine type significantly affect antibody titer?
2. Does age group significantly affect antibody titer?
3. Is there a significant interaction between vaccine type and age group?

---

## Methods
- Two-way ANOVA using R (`aov`)
- Factor conversion for categorical variables
- Hypothesis-driven statistical testing
- R Markdown for reproducible analysis

---

## Key Results
- **Vaccine Type:** Not statistically significant (p > 0.05)
- **Age Group:** Not statistically significant (p > 0.05)
- **Interaction Effect:** Not statistically significant (p > 0.05)

---

## Conclusion
The results indicate that neither vaccine type nor age group—individually or in combination—had a statistically significant effect on antibody titer levels in this dataset. This analysis demonstrates correct implementation and interpretation of two-way ANOVA in R.

---

## Files
-  Two_Way_ANOVA.Rmd` – R Markdown analysis
  Two_Way_ANOVA.pdf` – Knit PDF output
- `data/vaccine.csv` – Dataset used for analysis

---

## Academic Context
Developed as part of graduate-level coursework in **Applied Statistics using R**.
