# Predicting-Severity-of-Emerging-Infectious-Diseases-Using-Machine-Learning
This project explores the use of machine learning techniques to predict the severity of emerging infectious diseases using public health surveillance data. The goal is to identify patients at high risk of severe outcomes (e.g., hospitalization or death) early, enabling improved clinical decision-making and public health response.

# Problem Statement
Despite the availability of large-scale surveillance datasets, there remains a lack of real-time tools to accurately predict which patients will progress to severe outcomes. Many patients initially present with similar symptoms, yet outcomes vary significantly.
This results in:
* Delayed identification of high-risk patients
* Inefficient allocation of healthcare resources
* Increased strain on healthcare systems
Current approaches are largely descriptive rather than predictive, highlighting the need
for machine learning-based solutions.

## Aim and Objectives
# Aim
To develop a machine learning model capable of predicting disease severity among COVID-19 cases using CDC surveillance data.
# Objectives
* Analyze demographic and clinical factors associated with severe outcomes
* Develop and evaluate predictive models
* Identify key predictors of hospitalization and mortality
* Support public health decision-making

# Dataset
Dataset example- CDC COVID-19 Case Surveillance Public Use Dataset

# Variables:
* Age group
* Sex
* Race/ethnicity
* Hospitalization status
* Death status

# Target Variable
Severity (Binary Classification)- 
* 1 -Severe (Hospitalization or death)
* 0- Non-severe

# Methodology 
 
Literature was reviewed to get insights about the use of ML in disease survellance and the methods used. Literature had the below methods in common
# Data Preprocessing
* Removed missing and inconsistent data
*Encoded categorical variables (age, sex, race)
*Created derived severity variable
# Machine Learning Models
* Logistic Regression (baseline model)
* XGBoost (advanced model for improved accuracy)
# Model Workflow
* Data cleaning and preprocessing
* Feature selection
* Train-test split (80/20)
* Model training
* Model evaluation
# Evaluation Metrics
* Accuracy
*Precision
* Recall
* F1-Score
* ROC-AUC
These metrics help evaluate how well the model predicts severe cases, especially in imbalanced datasets.

# Key Indicators
* Common features used to predict severity eg Absolute neutrophil count, Co-morbidities
*Feature Selection- Techniques like LASSO regression identify significant markers of disease progression.
*Model Interpretability- Tools like SHAP explain how specific features contribute to patient risk scores. Essential for building trust in AI-driven clinical decisions.

# Key findings
* Machine learning models effectively classify high-risk patients
* XGBoost improves predictive performance compared to baseline models
* Data Integration- AI models integrate clinical, environmental, and population data for real-time insights.
* Surveillance & Prediction- ML can be used for disease surveillance, outbreak prediction

# Challenges and Limitations
* Missing or incomplete data in surveillance systems
* Potential bias in demographic reporting
* Limited availability of detailed clinical variables
* Generalizability across different populations
* Data privacy concerns

  # Conclusion
Machine learning provides a powerful approach to predicting the severity of emerging infectious diseases. By leveraging data sources like CDC surveillance data, predictive models can identify high-risk individuals and support timely interventions. It can also support outbreak preparedness and response as well as enhance data-driven decision-making in public health. Despite challenges, integrating machine learning into public health systems can significantly improve preparedness and response to future
outbreaks.

# Literature Sources (Selected)
* Wynants, L., et al. (2020). Prediction models for COVID-19 diagnosis and prognosis.
BMJ.
* Yan, L., et al. (2020). Interpretable mortality prediction model. Nature Machine
Intelligence.
* Rahmatinejad, Z., et al. (2024). Ensemble learning vs logistic regression. Scientific
Reports.
* Artificial intelligence and infectious diseases: an evidence-driven conceptual framework for research, public health, and clinical practice.The Lancet Infectious Diseases, 2025; 26, e152-e167.

# Team Contributions

Conceptualized the study focus area, reviewed literature, synthesized the hypothetical model, prepared visual content and slides












  
