# RPE-FUN Statistical Analysis

Statistical analysis of perceived exertion (RPE) and fun (FUN) ratings from pediatric rehabilitation interventions, developed as part of a clinical internship at Nationwide Children’s Hospital.

## Project Summary
This project analyzed outcomes from two pediatric rehab programs (HIIT and PLAY) using repeated measures ANOVA and linear mixed-effects models. Predictors included participant sex, lesson plans, and heart rate zones. Results were used to evaluate intervention impact and drive clinical decisions.

## Tools & Methods
- R: `rstatix`, `ggpubr`, `nlme`, `lme4`, `leaps`
- Statistical Models: Paired t-tests, RM-ANOVA, mixed-effects, post-hoc
- Model Selection: AIC, BIC, adjusted R², Mallows’ Cp
- Documentation: RMarkdown
- Visualization: `ggplot2`

## Repository Contents
- `RPE_FUN_Analysis.Rmd` – RM-ANOVA and post-hoc comparisons
- `Mixed_Model_Analysis.Rmd` – Mixed model analysis and model selection
- `outputs/` – PDF reports summarizing all statistical results

## Data Disclaimer
No raw participant data is included due to privacy. Scripts are annotated with data structure expectations.

## Key Outputs
- Model diagnostics and statistical result tables
- p-value labeled boxplots
- PDF reports suitable for internal stakeholder review
