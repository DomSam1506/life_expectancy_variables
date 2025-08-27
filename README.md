# Life Expectancy Analysis

Hi, this is one of my shorter personal projects, mainly done to practice the concepts I learned in my **Observational and Experimental Studies** course at SFU. 

The goal was to apply model selection techniques and regularization methods in the context of global health. Specifically, I explored factors associated with **low life expectancy (<65 years)** using logistic regression, stepwise selection (AIC and BIC), and LASSO.  

The project is more about practicing statistical modeling workflows than building a polished application, but I still aimed to structure the repo cleanly. All of my analysis are contained in the reports folder.

---

## Repository Structure

## Data

| Folder | Purpose |
|--------|---------|
| `data/Life_Expectancy_Data.csv` | Contains the original unmodified dataset. |
| `data/life_clean.csv` | Stores cleaned dataset prepared for modeling and analysis. |

---

## R Markdown Files

| File | Purpose |
|------|---------|
| `rmd/analysis.Rmd` | Full analysis including data prep, logistic regression modeling, variable selection (stepwise AIC/BIC, LASSO), and evaluation. |
| `rmd/report.Rmd` | Concise summary version highlighting essential findings and results. |

---

## Reports (Knitted Outputs)

| File | Purpose |
|------|---------|
| `reports/analysis_report.pdf` | Detailed report with all steps, results, and plots. |
| `reports/summary_report.pdf` | Shorter polished report for quick review. |



---

## How to Run
1. Clone the repo.  
2. Open the `.Rmd` files inside the `rmd/` folder in RStudio.  
3. Knit them into HTML/PDF/Word to reproduce the analysis.  

---

## Notes
- The **reports** include the plots directly, so I did not save them separately.  
- Since this project is mainly for practice, the focus is on **workflow and modeling choices** rather than exhaustive data exploration.  
- If you want to extend this, I recommend experimenting with different thresholds for "low life expectancy" or comparing logistic regression to tree-based models.  

---

Thank you!

Author: Dominion Samuel, August 2025
