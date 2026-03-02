# DATA 552 Project Proposal  
## Analyzing Weather-Related Risk Factors in Traffic Accidents  

**Group 5:**  
Zihuan Liu  
Janet Lu  
Zihao Sheng  
Yiran Wang  

---

## 1. Introduction

Traffic accidents remain a major public safety concern in urban and suburban areas. Adverse weather conditions such as rain, fog, snow, and extreme temperatures are often associated with increased accident rates, reduced visibility, and impaired road conditions. However, the specific ways in which different weather patterns contribute to accident risk are not always well understood.

This project analyzes historical traffic accident data combined with weather and temporal variables to identify high-risk conditions. The goal is to develop a data-driven framework to support traffic management authorities and emergency services in operational and policy decisions, such as:

- Resource allocation  
- Safety warnings  
- Preventative measures  

By identifying patterns in accident occurrence under different weather scenarios, this analysis aims to contribute to improved road safety and proactive traffic management.

---

## 2. Background and Related Information

Previous studies show correlations between weather conditions (heavy rainfall, low visibility, icy roads) and increased accident severity and frequency. However, many analyses focus on isolated factors and do not integrate temporal, geographic, and environmental variables.

### Dataset

- **Source:** Kaggle  
- **Link:** https://www.kaggle.com/datasets/oktayrdeki/traffic-accidents  
- **Records:** 209,000+  
- **Features:** 24  

The dataset includes:

- Time
- Location
- Environmental conditions
- Accident characteristics

This project explores how weather conditions interact with temporal variables (time of day, seasonal trends) to influence accident risk.

---

## 3. Project Plan

### 3.1 Data Preparation (3 days)

- Inspect dataset structure and variable definitions  
- Perform basic data cleaning:
  - Handle missing values
  - Fix inconsistent entries
  - Remove unrealistic measurements  
- Encode categorical variables (weather type, road conditions)
- Standardize weather-related features
- Split data into training and testing sets

---

### 3.2 Exploratory Data Analysis (2 days)

Identify:

- Accident frequency and severity patterns under different weather conditions  
- Seasonal patterns  
- Day-of-week effects  
- Peak accident hours  

---

### 3.3 Model Development (7 days)

**Target Variable:**

- Accident severity level  
OR  
- Likelihood of severe accident under specific conditions  

#### Baseline Models

- Logistic Regression  
- Decision Trees  

#### Advanced Models

- Random Forest  
- Gradient Boosting  

Model selection will be guided by empirical performance and interpretability considerations.

---

### 3.4 Evaluation and Interpretation (3 days)

Models will be evaluated using:

- **Accuracy** – Overall predictive correctness  
- **Recall** – Ability to identify high-risk or severe accident cases  
- **Precision** – Reliability of high-risk predictions  
- **AUC (Area Under ROC Curve)** – Overall classification performance  

Feature importance analysis will be conducted to understand which weather-related variables most strongly influence accident risk.

---

### 3.5 Deliverables

- Cleaned and documented dataset  
- Jupyter notebooks demonstrating:
  - Data cleaning  
  - Exploratory analysis  
  - Modeling  
  - Interpretation  
- Analytical report (PDF format)  
- Trained predictive models and evaluation results  
- Optional visualization dashboard  
- Final presentation (slides + in-person presentation)

---

### 3.6 Key Dates (22 Days)

| Milestone | Date |
|-----------|------|
| Project Start Date | February 26, 2026 |
| Progress Update | March 6, 2026 |
| Final Presentation | March 20, 2026 |

---

## 4. Project Risks and Mitigation Strategies

### Risk 1: Weather Data Quality Issues

Weather variables may contain missing or unreliable data, affecting model accuracy.

**Mitigation:**

- Systematic data quality assessment  
- Missing value analysis  
- Outlier detection  
- Statistical imputation  
- Sensitivity analysis  
- Adjust research focus if necessary  

---

### Risk 2: Limited Predictive Power of Weather Variables

Accidents are influenced by additional factors (traffic flow, road structure, driver behavior).

**Mitigation:**

- Include temporal variables (time of day, season)  
- Include spatial variables (location)  
- Focus on interpretability and variable importance  
- Shift to risk trend analysis if predictive performance is limited  

---

### Risk 3: Model Overfitting

Complex models (Random Forest, Gradient Boosting) may overfit historical data.

**Mitigation:**

- Cross-validation  
- Independent test set evaluation  
- Regularization methods  
- Retain benchmark models (Logistic Regression)  

---

### Risk 4: Time Constraints and Project Scope

Data cleaning and advanced modeling may exceed the planned timeline.

**Mitigation:**

- Phased development approach  
- Prioritize baseline model  
- Reduce model complexity if necessary  

---

## 5. Conclusion

This project systematically analyzes historical traffic accident data to identify high-risk scenarios under different weather and time conditions and quantify their impact on accident occurrence and severity.

By combining exploratory analysis and predictive modeling, the study aims to provide actionable, evidence-based support for traffic management and public safety decision-making.

The findings may assist in:

- Increasing patrol frequency in severe weather  
- Issuing early risk warnings  
- Optimizing road maintenance planning  
- Developing targeted traffic safety strategies  

Even if predictive accuracy is limited, the interpretability-focused framework ensures transparency and robustness for policy-making applications.

Overall, this project is methodologically feasible, time-bound, and practically valuable. It contributes toward proactive and data-driven traffic safety management.
