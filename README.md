# Mental Health in Tech Workplace - Exploratory Data Analysis (EDA) 🧠💻

## 📖 Project Overview
Mental health issues in the tech industry are highly prevalent, yet employees often hesitate to seek help due to workplace stigma or a lack of clear communication regarding corporate benefits. This project performs an in-depth Exploratory Data Analysis (EDA) on a 2014 survey dataset to uncover patterns surrounding mental health in the tech workplace. 

The goal is to identify what drives mental health stigma, what encourages employees to seek help, and how organizations can optimize their mental health benefits to support their workforce.

## 🎯 Problem Statement
How do we identify the demographic and workplace factors most strongly associated with mental health struggles? Furthermore, how effective are current employer interventions (such as wellness programs, leave policies, and anonymity protections) in encouraging tech employees to seek the treatment they need?

## 💡 Business Objective
To provide data-driven recommendations to HR departments and Tech Leadership. By understanding the barriers to seeking help, organizations can foster a more supportive work culture, optimize their wellness programs, and ultimately reduce the negative impact of mental health conditions on employee well-being and productivity.

## 📊 Dataset Information
* **Source:** Open Sourcing Mental Illness (OSMI) 2014 Survey
* **Rows:** 1,259
* **Columns:** 27 (Age, Gender, Country, corporate benefits, perceived stigma, work interference, etc.)
* **Target Variable:** `treatment` (Whether the respondent has sought treatment for a mental health condition)

## 🛠️ Tech Stack & Libraries Used
* **Language:** Python 3.x
* **Data Manipulation:** `pandas`, `numpy`
* **Data Visualization:** `matplotlib`, `seaborn`
* **Preprocessing:** `scikit-learn` (LabelEncoder for correlation analysis)
* **Environment:** Jupyter Notebook / Google Colab

## 🚀 Key Insights & Findings
1. **The 50/50 Reality:** Approximately 50% of the surveyed tech workforce has sought mental health treatment, proving this is a widespread industry issue, not an isolated one.
2. **The HR Communication Gap:** The most common answer to questions about corporate mental health benefits, wellness programs, and medical leave was *"Don't know."* Companies are failing to communicate the resources they offer.
3. **Work Interference:** The strongest predictor of an employee seeking treatment is how often their condition interferes with their daily work.
4. **The Interview Stigma:** An overwhelming majority of respondents stated they would *never* bring up a mental health issue in a job interview out of fear of discrimination.
5. **Gender Disparities:** Despite the tech workforce being predominantly male, men seek mental health treatment at proportionally lower rates than women and non-binary individuals, indicating a higher cultural stigma among men.

## 📈 Strategic Recommendations for Employers
* **Bridge the Communication Gap:** Launch active, year-round awareness campaigns about existing mental health resources rather than burying them in an onboarding handbook.
* **Destigmatize for Men:** Implement targeted internal campaigns utilizing leadership testimonials to normalize mental health care specifically for male employees.
* **Guarantee Psychological Safety:** Train supervisors in empathy and mental health first-aid so employees feel safe requesting workload adjustments before suffering total burnout.
* **Frictionless Medical Leave:** Audit and streamline the medical leave process to ensure taking time off for mental health is transparent, easy, and free of bureaucratic red tape.

## 💻 How to Run this Project
1. Clone this repository to your local machine:
   ```bash
   git clone [https://github.com/YourUsername/Mental-Health-in-Tech-Workplace-Analysis.git](https://github.com/YourUsername/Mental-Health-in-Tech-Workplace-Analysis.git)

   Ensure you have the required libraries installed:

Bash
pip install pandas numpy matplotlib seaborn scikit-learn
Open the Jupyter Notebook:

Bash
jupyter notebook Sample_EDA_Submission_Template.ipynb
Run the cells sequentially to view the data cleaning process and visualizations.
