🚢 Titanic Survival Analysis

📌 Motivation & Problem Statement

The Titanic dataset is one of the most widely used datasets in data analytics and education. Beyond its historical relevance, it provides a structured opportunity to analyze how demographic and socio-economic factors influence real-world outcomes.

This project demonstrates a professional exploratory data analysis (EDA) workflow — including data cleaning, feature engineering, visualization, and insight generation — to identify the key factors that influenced survival during the Titanic disaster.

The primary objective is structured analytical reasoning aligned with Entry-Level Data Analyst responsibilities, rather than predictive modeling.

🎯 Target Audience

    Aspiring Data Analysts
    Data Science learners
    Recruiters evaluating foundational analytics skills

Hiring managers assessing exploratory data analysis capability

🧠 Decision Context

    his analysis examines how variables such as gender, passenger class, age, fare, and family structure influenced survival outcomes.

The findings reflect real-world analytical scenarios where professionals evaluate:

    Risk patterns
    Socio-economic disparities
    Decision outcomes
    Fairness and prioritization factors
    Structured exploratory analysis like this forms the foundation of business intelligence and operational analytics.

📊 Project Overview

This project performs a structured Exploratory Data Analysis (EDA) of the Titanic passenger dataset to identify key determinants of survival.

Workflow Includes:

    Data loading and validation
    Missing value handling
    Feature engineering (FamilySize, Age Groups)
    Survival rate computation (percentage-based)
    Cross-variable analysis
    Visualization and interpretation
    Strategic conclusions

🗂 Dataset Information

Source: Kaggle Titanic Dataset
Total Records: 891 passengers
Features: 12 structured variables

Key attributes include:

    PassengerId
    Survived
    Pclass
    Sex
    Age
    Fare
    SibSp
    Parch
    Embarked

🧹 Data Preparation & Feature Engineering

The following preprocessing steps were applied:

    Missing values in Age were handled using median imputation to reduce the impact of outliers
    Duplicate records were checked

Created a new feature:

    FamilySize = SibSp + Parch + 1
    Categorized Age into structured groups for survival comparison
    Cleaned dataset prepared for structured analysis
    This reflects a practical data preparation pipeline aligned with professional analytics workflows.

📈 Key Analytical Findings
1️⃣ Overall Survival Rate

    Approximately 38% of passengers survived, indicating a majority fatality rate.

2️⃣ Gender-Based Survival Patterns

    Female passengers had significantly higher survival rates than males
    Gender emerged as one of the strongest survival indicators
    Reflects evacuation prioritization practices during the disaster

3️⃣ Passenger Class & Socio-Economic Impact

    First-class passengers had substantially higher survival rates
    Third-class passengers experienced the lowest survival probability
    Higher fare-paying passengers showed improved survival outcomes
    This highlights the influence of socio-economic status on survival access.

4️⃣ Age & Survival Trends

    Younger passengers demonstrated moderately higher survival probabilities
    Age alone was not as strong a predictor as gender or passenger class

5️⃣ Family Size Patterns
    
    Small family groups showed improved survival likelihood
    Very large families exhibited reduced survival probability

🔎 Visual Analysis

    Key visualizations include:
    Survival Rate by Gender
    Survival Rate by Passenger Class
    Age Distribution Histogram
    Correlation Heatmap
    Survival Rate by Family Size

🗂 Project Structure
titanic-survival-analysis/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── outputs/
│   ├── figures/
│   └── reports/
│
├── src/
│
├── 01_titanic_exploratory_data_analysis.ipynb
├── requirements.txt
├── .gitignore
└── README.md


▶️ How to Run the Project
git clone <your-repository-url>
cd titanic-survival-analysis
pip install -r requirements.txt
jupyter notebook

📌 Conclusion

This project demonstrates the ability to transform raw historical data into structured, actionable insights using exploratory data analysis techniques.

The findings reveal that survival outcomes during the Titanic disaster were primarily influenced by gender and socio-economic class, with additional contributions from age and family structure.

Core Skills Demonstrated:

    Data cleaning
    Feature engineering
    Statistical reasoning
    Data visualization
    Insight communication
    Structured analytical reporting
