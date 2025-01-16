# Predicting Political Crime in Mexico

## Introduction
In an era of political instability, harnessing data analytics can be a critical step toward protecting democratic processes. This project demonstrates how multivariate statistical analytics and predictive modeling can help identify and mitigate the risks of political crime in Mexico, ultimately supporting transparent and fair elections. By combining insights from economic, demographic, and political violence data, this research underscores the power of data-driven approaches in addressing complex social challenges.

---

## Project Overview and Purpose
This project aims to predict the type of political crime that will occur—ranging from threats and armed attacks to kidnappings and murders—across Mexico.  

### Core Question:
**How can past incidents of political violence and macroeconomic factors help forecast future political crimes?**

By identifying at-risk regions and political parties, this project equips government officials, law enforcement, NGOs, and political parties with actionable intelligence to implement preventive measures. It also highlights the growing importance of data analytics, project creation, and social responsibility in preserving democracy.

---

## Key Variables
1. **Target Role:**  
   Political position of the individual attacked (e.g., candidate, executive).  
2. **State-Level Factors:**  
   Geographic location where the incident occurred.  
3. **Economic Indicators:**  
   GDP, employment rates, and other economic measures.  
4. **Demographic Variables:**  
   Population age groups, including data on *Niños del Narco*.  

---

## Data Collection and Preprocessing
### Datasets:
1. **Political Violence Data (2017–2024):**  
   Sourced from *Data Cívica*, covering threats, murders, forced disappearances, and kidnappings.
2. **Economic Data:**  
   GDP figures from Mexico’s Central Bank (*Banxico*) to capture macroeconomic contexts.
3. **Demographic Data:**  
   Provided by Mexico’s National Statistical Office, including education levels, gender distribution, and access to health services.

### Data Preparation:
- Merged datasets from multiple sources.
- Cleaned and standardized variables for consistency.
- Detected and treated outliers and missing values.
- Normalized inputs for machine learning models.

### Exploratory Data Analysis (EDA):
- Analyzed patterns and correlations between variables.
- Used visualization tools (e.g., heat maps, histograms) to highlight key predictors.

### Feature Engineering:
- Created new variables, including teenage population and internal migration rates.
- Reduced dimensionality by grouping similar categories.

---

## Methods and Model Development
### Modeling Techniques:
- **K-Nearest Neighbors (KNN)**: Selected as the primary model for its balance of performance and computational efficiency.
- **LASSO Regression**: Used for feature selection.
- **Random Forest**: Provided feature importance insights.

### Model Development:
- **KNN Performance:** Achieved up to 72% accuracy for predicting political crime types.  
- **Feature Selection:** LASSO Regression and Random Forest marginally improved accuracy.  
- **SMOTE:** Addressed class imbalances, improving accuracy by 6%.  
- **Cross-Validation:** Models validated using 3 K-folds for robustness.

### Evaluation Metrics:
- Accuracy:
  - **72%** for predicting the specific type of political crime.
  - **77%** for predicting whether a murder or other attack will occur.
- **SHAP Importance:** Identified political party affiliation, state location, and individual roles as top predictors.

---

## Key Findings and Recommendations
1. **High-Risk Parties:**  
   The National Action Party (PAN) and Institutional Revolutionary Party (PRI) face elevated threats.
2. **Vulnerable Regions:**  
   Puebla, Jalisco, and Zacatecas are hotspots for political violence, necessitating targeted interventions.
3. **Demographic Influence:**  
   Factors such as gender distribution, access to health services, and population size significantly correlate with political violence.

### Recommendations:
- Develop policies addressing root causes like unemployment and healthcare disparities to foster long-term social stability.
- Collaborate with local stakeholders, including community leaders and advocacy groups, to enhance preventive strategies.

---

## Societal Impact and Future Directions
This project provides a data-driven tool to enhance political safety and community resilience in Mexico.  

### Future Plans:
- **Collaboration:** Share insights with law enforcement to inform strategic interventions.  
- **Broader Scope:** Incorporate variables like media coverage and social media sentiment for enhanced predictions.  
- **Model Explainability:** Use advanced statistical tools to communicate findings transparently to policymakers.  
- **Continuous Improvement:** Regular updates to ensure relevance in Mexico’s evolving political climate.

---

## Conclusion
This research illustrates how data analytics and robust project design can address pressing social challenges. By predicting political crime and offering targeted solutions, it demonstrates the tangible impact of well-designed data models on democracy. It underscores the value of merging technical expertise with social goals to support safer elections and stronger institutions.
