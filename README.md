# fifa21-player-value-analysis

# FIFA 21 Player Market Value Analysis

**Course:** Biostatistics | CUNY Baruch College  
**Language/Tools:** R, Quarto, ggplot2, tidyverse

## Overview
This project uses multiple linear regression to analyze how a soccer player's 
on-field attributes — specifically pace and passing — affect their estimated 
transfer market value. The dataset contains over 18,000 players from the 
FIFA 21 Complete Player Dataset (Kaggle).

## Key Findings
- Pace and passing are both statistically significant predictors of player market value (p < 2e-16)
- Shooting was not a significant predictor and was removed from the final model
- The model reveals intuitive trends: players with higher pace and passing 
  ratings command higher transfer values across most field positions

## Methods
- Exploratory Data Analysis (EDA) with ggplot2
- Data cleaning and transformation with tidyverse
- Multiple linear regression (OLS)
- Model diagnostics and assumption checking

## Files
- `report.qmd` — full Quarto report with code and analysis
- `fifa21 raw data v2.csv` — raw dataset from Kaggle

## Data Source
FIFA 21 Complete Player Dataset — Kaggle (open source)
