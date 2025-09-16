# Flu-shot-learning
Predict H1N1 and seasonal flu vaccination uptake using CRISP-DM methodology
# Flu Vaccine Analysis Project

##  Project Overview
This project analyzes the **National Health Interview Survey (NHIS) dataset** to understand factors influencing vaccine uptake, focusing on **H1N1 and Seasonal Flu vaccines**.  
The goal is to uncover actionable insights that can help public health stakeholders improve vaccination campaigns and policies.  

We applied the **data science process** end-to-end:
- **Business Understanding** – Identify the problem: why some individuals choose not to vaccinate.  
- **Data Understanding** – Explore the dataset to find key variables and patterns.  
- **Data Preparation** – Handle missing values, encode categorical features, and engineer new features like household size group, concern–knowledge tiers, and behavioral scores.  
- **Modeling** – Build baseline models, test multiple classifiers, and select **Random Forest Classifier** as the best performer.  
- **Evaluation** – Compare performance metrics (accuracy, precision, recall, ROC-AUC) to ensure model reliability.  
- **Deployment (Presentation)** – Communicate results clearly to stakeholders through visuals and actionable insights.  

---

## Key Results
- **H1N1 Vaccine Uptake** – [Insert final percentage & key finding]  
- **Seasonal Flu Vaccine Uptake** – 53.4% did not take the vaccine, while 46.6% did.  
- **Important Features** – Age group, education, income, and behavioral scores strongly influenced vaccination decisions.  
- **Best Model** – Random Forest Classifier provided the best trade-off between accuracy and interpretability.  

---

##  Project Artifacts
- ** Data Preparation Notebook** – Cleaning, preprocessing, feature engineering  
- ** Modeling Notebook** – Baseline models, Random Forest training, evaluation  
- ** EDA Notebook** – Exploratory data analysis and visualization  
- ** Presentation Slides** – Clear, non-technical summary for stakeholders  

---

## 📑 Links

- 🔗 [Dataset Source – NHIS / Kaggle Flu Vaccine Dataset](https://www.kaggle.com/c/h1n1-flu-vaccines-prediction/data)  

---

## Repository Navigation
- `data/` → Raw and cleaned datasets  
- `notebooks/` → Jupyter notebooks (EDA, preprocessing, modeling)  
- `presentation/` → Slides for stakeholder presentation  
- `README.md` → Project overview, results, and navigation instructions  

---

##  How to Use
1. Clone the repository:  
   ```bash
   git clone https://github.com/conquest_rgb/flu-vaccine-analysis.git
   cd flu-vaccine-analysis
    2. open jupyter noteebook
