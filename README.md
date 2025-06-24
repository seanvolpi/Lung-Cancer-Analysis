# Lung Cancer Severity Analysis (R)

This project explores the relationship between various environmental, lifestyle, and physiological variables and lung cancer severity levels. Using a dataset of 1,000 patients, the project applies cumulative logit regression models to identify key predictors of disease severity.

---

## Project Overview

- Data comes from a study of over 462,000 individuals in China, tracking lung cancer outcomes based on air quality, lifestyle factors, and symptoms.
- A subset of 1,000 lung cancer patients was analyzed for this project.
- The goal was to explore predictors of lung cancer severity using exploratory data analysis and ordinal regression modeling.

---

## Data Summary

- **Response Variables**:
  - Lung disease severity level (ordinal categorical)
  - Chronic lung disease score

- **Predictor Variables** (select examples):
  - Environmental: Air pollution, occupational hazards
  - Lifestyle: Smoking, alcohol use, diet, obesity
  - Genetic risk
  - Symptoms: Chest pain, fatigue, shortness of breath, coughing of blood

---

## Methodology

- **Exploratory Data Analysis** to identify distribution patterns and imbalances in variables.
- **Cumulative Logit Regression Models** used for both cause- and symptom-based predictors.
  - Proportional odds assumption applied.
  - Two separate models created:
    - One focused on **potential causes**
    - One focused on **potential effects/symptoms**

---

## Key Findings

### Causes Associated with Lung Cancer Severity:
- **Increased Severity**: Work hazards (most influential), air pollution, smoking, diet, passive smoking, and genetic risk were all associated with higher odds of greater severity.
- **Lower Severity**: Dust allergies (most influential), alcohol use, and obesity were linked to lower severity.

### Effects/Symptoms Associated with Severity:
- **Increased Severity**: Chest pain (most influential), dry cough, coughing blood, fatigue, and fingernail clubbing were all associated with higher odds of greater severity.
- **Lower Severity**: Shortness of breath (most influential), snoring, wheezing, and frequent colds were linked to lower severity.

---

## Tools Used

- R (cumulative logit model, data wrangling, visualization)
- PowerPoint (presentation formatting)
- Data sources:
  - https://www.kaggle.com/datasets/thedevastator/cancer-patients-and-air-pollution-a-new-link
  - https://online.stat.psu.edu/stat504/book/export/html/793

---

## Future Work

- Explore additional model types (e.g., ordinal random forests, CART)
- Validate assumptions with diagnostic checks
- Incorporate interaction terms or variable grouping

---

## Contact

Created by Sean Volpi – B.S. in Statistics  
