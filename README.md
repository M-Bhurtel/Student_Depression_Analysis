#  Student Depression Analysis  
### Identifying Key Drivers of Student Mental Health Using Exploratory Data Analysis

This project applies structured data analysis to uncover the primary factors contributing to depression among students. Using professional data-cleaning, feature-engineering, and statistical correlation techniques, the analysis reveals measurable relationships among academic pressure, financial stress, lifestyle habits, and mental health outcomes.

---

##  Live Project

-  Notebook: [Student_depression_analysis.ipynb](https://github.com/M-Bhurtel/Student_Depression_Analysis/blob/main/Student_depression_analysis.ipynb)

---

##  Business / Research Problem

Educational institutions increasingly face rising mental health concerns among students.  

**Key Question:**  
Which measurable factors most strongly correlate with depression among students?

This analysis provides data-driven insights that can help institutions:

- Identify high-risk groups
- Prioritise intervention strategies
- Improve student support systems

---

##  Dataset Overview

- **Source:** [Kaggle – Student Depression Dataset](https://www.kaggle.com/datasets/adilshamim8/student-depression-dataset) 
- **Size:** 27,901 rows × 18 columns  
- **Population:** Students and Professionals (filtered to Students)

### Key Variables Analysed

- Academic Pressure
- Financial Stress
- Study Satisfaction
- CGPA
- Sleep Duration
- Dietary Habits
- Suicidal Thoughts

---

##  Data Cleaning & Preparation

Professional preprocessing steps included:

- Removed irrelevant columns (`id`, `City`)
- Standardised inconsistent categorical values
- Removed formatting artifacts (extra spaces, quotes, placeholders)
- Filtered the dataset to focus on Students only
- Encoded categorical variables for correlation analysis
- Validated null values and data integrity
- Prepared a numeric correlation-ready dataset

This ensured statistical reliability before performing EDA.

---

##  Analytical Approach

The project follows a structured workflow:

1. Data Validation  
2. Data Cleaning  
3. Feature Encoding  
4. Exploratory Data Analysis (EDA)  
5. Correlation Analysis  
6. Insight Extraction  

Tools used:

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

##  Key Insights

### 1️ Academic & Financial Pressure Are Primary Risk Drivers

- Strong positive correlation between:
  - High Academic Pressure
  - High Financial Stress
  - Depression prevalence

Students experiencing both pressures show significantly elevated risk.

---

### 2️ Lifestyle Factors Amplify Mental Health Risk

- Poor sleep duration correlates with higher depressive symptoms.
- Unhealthy dietary habits show a measurable association with depression.

Mental health is not isolated from physical habits.

---

### 3️ Study Satisfaction Acts as a Protective Variable

- Higher study satisfaction correlates with lower depression rates.
- Functions as a buffering factor against academic stress.

---

### 4️ Suicidal Thoughts Strongly Associated With High Stress Levels

A clear statistical relationship was observed between:
- Elevated stress
- Reported suicidal ideation

This highlights early warning indicators.

---

##  Impact & Application

This analysis demonstrates how structured data analysis can:

- Support evidence-based mental health interventions
- Help universities target high-risk students
- Inform resource allocation decisions
- Strengthen preventive mental health strategies

---

##  Technical Skills Demonstrated

- Data Cleaning & Sanitisation
- Feature Engineering
- Categorical Encoding
- Correlation Matrix Analysis
- Data Visualisation & Storytelling
- Insight Communication
- Structured Analytical Workflow

---

##  Installation

```bash
git clone https://github.com/M-Bhurtel/Student_Depression_Analysis.git
cd Student_Depression_Analysis
pip install pandas numpy matplotlib seaborn
jupyter notebook
```

Open `Student_depression_analysis.ipynb` and run all cells sequentially.

---

##  Author

Mohani Lal Bhurtel 

---

##  License

This project is licensed under the MIT License – feel free to use and modify it.
