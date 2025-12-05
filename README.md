# STA305: Experimental Design - Project Study (Winter 2025)

This repository contains the final project for **STA305: Experimental Design**, Winter 2025 at the **University of Toronto**.

## Study Overview

**Goal:** To investigate whether the method of cannabis consumption (Tea, Smoking, or None) and Gender affect changes in IQ, controlling for baseline IQ and Age.

**Methodology:**
*   **Setting:** *The Islands* virtual population simulator.
*   **Participants:** 216 young adults (18-30 years).
*   **Design:** Randomized, balanced blocking, repeated-measures (cross-over/within-subject) design.
*   **Analysis:** Repeated-Measures Two-Way ANOVA to assess main effects and interactions.

**Key Findings:**
*   **No Significant Effect:** The study found no statistically significant evidence that gender or cannabis consumption method influences short-term cognitive performance (IQ changes).
*   **Assumptions:** Normality of residuals was violated ($p < 0.05$), but Homogeneity of Variance was satisfied.

## Repository Structure

*   **`data/`**: Contains the cleaned participant dataset (`Participants List cleaned.csv`).
*   **`report/`**: Contains the project report in PDF (`Final Report STA305.pdf`) and Quarto (`Final Report STA305.qmd`) formats. The analysis code is embedded in the QMD file.
*   **`output/`**: Contains generated plots and visualization images.