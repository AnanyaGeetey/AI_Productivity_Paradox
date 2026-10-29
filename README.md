
# The AI Productivity Paradox

## Overview
This project investigates differences in AI readiness and productivity across countries, focusing on why countries within the same income group exhibit different levels of AI preparedness.

## Objectives
- Explore cross-country differences in AI readiness.
- Examine the relationship between AI readiness and labour productivity.
- Identify within-income-group disparities using Z-scores.
- Analyze the relationship between AI readiness and economic, technological, and governance indicators.
- Use regression analysis and hierarchical clustering to identify patterns across countries.

## Tools & Technologies
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Statsmodels
- Scikit-learn
- SciPy

## Methodology
1. **Data Preparation:** Combined AI readiness data with Penn World Table (PWT), World Development Indicators (WDI), and Worldwide Governance Indicators (WGI).
2. **Data Cleaning:** Handled missing values, standardized country names, and prepared variables for analysis.
3. **Exploratory Data Analysis:** Examined distributions, correlations, outliers, and differences across income groups.
4. **Within-Group Analysis:** Calculated Z-scores to identify countries performing above or below their income-group average in AI readiness.
5. **Regression Analysis:** Estimated OLS models with HC3 robust standard errors to examine associations between AI readiness and its potential determinants.
6. **Interaction Analysis:** Tested whether selected relationships differ across income groups.
7. **Hierarchical Clustering:** Applied Ward's method separately within each income group to identify groups of countries with similar characteristics.

## Key Findings
- AI readiness varies substantially across countries, including among countries in the same income group.
- Within-group Z-scores help identify countries whose AI readiness differs from their income-group average.
- Regression analysis examines associations between AI readiness, human capital, digital connectivity, labour productivity, services, and government effectiveness.
- Hierarchical clustering identifies distinct country profiles within income groups.

## Repository Structure
```text
├── README.md
└── Python_final(2).ipynb
```

## How to Run
1. Open the notebook in Google Colab or Jupyter Notebook.
2. Install the required Python libraries.
3. Download or access the datasets referenced in the notebook.
4. Update the Google Drive file paths as required.
5. Run the cells sequentially.

## Data Sources
- AI readiness dataset: [Google Sheets](https://docs.google.com/spreadsheets/d/1t09ZHxT53bQfAis4s8-5-v9WqquxnLn9UzgAeEFA6Jc/edit?usp=sharing)
- Penn World Table (PWT)
- World Development Indicators (WDI)
- Worldwide Governance Indicators (WGI)

## Conclusion
The project combines econometric analysis and unsupervised learning to investigate cross-country differences in AI readiness. By examining both within-income-group disparities and broader economic and institutional characteristics, it provides a framework for understanding the heterogeneous relationship between AI preparedness and productivity.

## Author

**Ananya** <br>
**Ayushi**
