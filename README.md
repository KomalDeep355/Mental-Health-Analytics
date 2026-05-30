🧠 Mental Health Analytics Dashboard
Student Stress & Anxiety Patterns — EDA, SQL & Machine Learning Pipeline

A complete end-to-end Data Analytics & Machine Learning project exploring mental health trends among college students using Python, SQL, statistical analysis, and predictive modeling.

This project investigates the question:

What academic, lifestyle, and behavioral factors are most strongly associated with depression, anxiety, and panic attacks among students?

The workflow combines Exploratory Data Analysis (EDA), SQL querying, feature engineering, machine learning, and interactive dashboarding to transform raw mental health survey data into actionable insights.

📌 Project Objectives

This project aims to:

✔ Analyze prevalence of depression, anxiety, and panic attacks among students
✔ Explore relationships between sleep, academic performance, demographics, and mental health
✔ Use SQL analysis for structured querying and pattern discovery
✔ Build a predictive machine learning model for mental health risk estimation
✔ Create dashboard-ready outputs for business intelligence visualization

🛠 Tech Stack

Programming & Analytics

Python
Pandas
NumPy
Seaborn
Matplotlib
Scikit-learn

Database & Querying

SQLite
SQL

Visualization & Dashboarding

Power BI

Machine Learning

Random Forest Classifier
Feature Encoding
Model Evaluation
ROC-AUC Analysis
📂 Project Structure
Mental-Health-Analytics-Dashboard/
│
├── 01_mental_health_EDA.ipynb
│   └── Full notebook:
│       Data Cleaning + EDA + SQL Analysis + ML Pipeline
│
├── data/
│   └── p1_final_with_predictions.csv
│       Cleaned dataset + prediction probabilities
│
├── images/
│   ├── chart1_prevalence.png
│   ├── chart2_sleep_vs_cgpa.png
│   ├── chart3_correlation.png
│   ├── chart4_treatment_analysis.png
│   └── (additional dashboard charts)
│
└── README.md
📊 Exploratory Data Analysis (EDA)

The analysis investigates:

Mental Health Condition Distribution
Depression prevalence
Anxiety prevalence
Panic attack prevalence
Cross-condition comparison
Academic Performance Analysis
Mental health vs CGPA
Academic pressure indicators
Performance patterns across groups
Lifestyle & Behavioral Factors
Sleep quality and duration
Study behavior patterns
Treatment-seeking behavior
Demographic variations
Correlation Analysis

Feature relationships were explored using:

Correlation matrices
Heatmaps
Comparative visualizations
Group-based statistical analysis
🧮 SQL Analytics Layer

The project includes SQL-based analysis using SQLite for structured data exploration.

Sample analytical questions:

-- Students with anxiety by academic category

SELECT academic_level,
COUNT(*)
FROM students
WHERE anxiety='Yes'
GROUP BY academic_level;
-- Treatment seeking analysis

SELECT treatment,
COUNT(*)
FROM students
GROUP BY treatment;

SQL was used to perform:

Aggregations
Filtering
Group-wise analysis
Pattern discovery
Data summarization
🤖 Machine Learning Pipeline

A predictive model was developed to estimate mental health risk patterns.

Workflow
Data preprocessing
Missing value handling
Categorical encoding
Feature selection
Train-test split
Model training
Evaluation & performance analysis
Model Used

Random Forest Classifier

Why Random Forest?

Handles mixed feature types
Strong performance on structured/tabular data
Robust against overfitting
Provides feature importance insights
Evaluation Metrics
Accuracy
Precision
Recall
F1-Score
ROC-AUC Score

Model Performance

Metric	Score
Accuracy	X.XX
Precision	X.XX
Recall	X.XX
ROC-AUC	0.XXX

(Update with your final results.)

🔍 Key Findings
Finding 1 — Mental Health Prevalence
Anxiety showed the highest prevalence among observed conditions.
Depression and panic attacks affected a significant portion of students.
Finding 2 — Treatment Gap

Only a small percentage of students experiencing symptoms sought professional support.

Finding 3 — Sleep & Academic Performance

Poor sleep patterns were associated with:

Increased anxiety levels
Reduced academic performance (CGPA)
Finding 4 — Behavioral Signals Matter

Lifestyle and academic variables contributed meaningfully to predictive modeling performance.

📈 Dashboard Preview

(Add screenshots after generating visuals.)

Mental Health Prevalence




Correlation Heatmap




Additional Visualizations
Sleep vs Mental Health
Treatment Analysis
Academic Performance Patterns
Feature Correlation Dashboard
🚀 How to Run the Project
Clone Repository
git clone <your-repository-link>
Open Notebook

Open:

01_mental_health_EDA.ipynb

in:

Google Colab
Jupyter Notebook
VS Code Notebook Environment
Install Dependencies
pip install pandas numpy seaborn matplotlib scikit-learn sqlite3
Run All Cells

Execute notebook cells sequentially.

💼 Skills Demonstrated

This project demonstrates practical skills in:

✔ Data Cleaning
✔ Exploratory Data Analysis (EDA)
✔ SQL Querying
✔ Data Visualization
✔ Feature Engineering
✔ Machine Learning
✔ Predictive Analytics
✔ Dashboard Development
✔ Business Intelligence Reporting

🎯 Business / Research Relevance

Mental health analytics has applications across:

Educational institutions
Student wellness programs
Healthcare analytics
Behavioral risk assessment
Data-driven intervention planning

The analytical workflow demonstrated here can be adapted for healthcare, HR analytics, behavioral analytics, and risk modeling projects.
