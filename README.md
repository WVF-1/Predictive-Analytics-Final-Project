# Predictive-Analytics-Final-Project
Predictive analytics project using logistic regression and cross-validation to model and predict pregnancy likelihood based on shopper behavior data from BabyShop.xlsx.

## Project Overview

- **Goal**: Predict pregnancy status of shoppers using purchasing data.
- **Methods Used**:
  - Logistic regression modeling
  - ROC curve analysis
  - k-fold cross-validation
- **Tools**: R, tidyverse, caret, pROC

## Files Included

- `William_Fullerton_Predictive_Analytics_Project.Rmd`: R Markdown file with all data cleaning, modeling, and evaluation steps.
- `BabyShop.xlsx` (not included): The original dataset used for the analysis.

## Key Takeaways

- Variables such as `Maternity_Clothes` and `Pregnancy_Test` were found to be strong predictors.
- The final logistic model demonstrated good predictive power, validated through 10-fold cross-validation and ROC AUC analysis.

## How to Run

1. Open the `.Rmd` file in RStudio.
2. Ensure you have the required libraries installed: `tidyverse`, `caret`, `pROC`, `readxl`.
3. Load the BabyShop.xlsx file into the same directory.
4. Knit the document or run the chunks step by step to reproduce the analysis.

## Author

**William Fullerton**  
Senior, B.S. in Statistics and Data Science  
Minor in Finance  
Graduating December 2025

---

*This project was submitted as part of STAT 4350 coursework at Robert Morris University (RMU) Moon Township PA.*
