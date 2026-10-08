\# Diabetes Outcomes \& Risk Analysis



\## Project Overview



This project analyzes patient-level health data to identify factors associated with diabetes and communicate clinically relevant patterns through statistical modeling and an interactive Power BI dashboard.



The workflow covers data cleaning, exploratory data analysis, statistical modeling, model evaluation, risk prediction, and data visualization. The project demonstrates an end-to-end analytical workflow relevant to biostatistics, clinical research, and healthcare analytics.



\## Objectives



The primary objectives were to:



\- Estimate diabetes prevalence in the study population.

\- Examine how diabetes prevalence varies across age and BMI groups.

\- Evaluate associations between diabetes and clinical risk factors.

\- Compare HbA1c and blood glucose levels between patients with and without diabetes.

\- Develop a multivariable logistic regression model for diabetes.

\- Evaluate the predictive performance of the model.

\- Communicate key findings through an interactive Power BI dashboard.



\## Dataset



The cleaned analytical dataset contains \*\*96,146 patient records\*\*.



Variables used in the analysis include:



\- Age

\- Gender

\- BMI

\- Hypertension

\- Heart disease

\- Smoking history

\- HbA1c level

\- Blood glucose level

\- Diabetes status



Additional derived variables were created for analysis and visualization, including age groups, BMI categories, and predicted diabetes probabilities.



\## Analytical Workflow



\### 1. Data Preparation



Python was used to inspect and prepare the dataset for analysis. The workflow included:



\- Data quality assessment

\- Missing-value evaluation

\- Variable type verification

\- Creation of clinically interpretable age groups

\- Creation of BMI categories

\- Preparation of a cleaned analytical dataset

\- Export of the processed dataset for Power BI



\### 2. Exploratory Data Analysis



Descriptive analyses were conducted to characterize the patient population and examine patterns associated with diabetes.



The analysis included diabetes prevalence across demographic and clinical characteristics and comparisons of important biomarkers between patients with and without diabetes.



\### 3. Statistical Modeling



A multivariable \*\*logistic regression model\*\* was developed to investigate factors associated with diabetes.



Model results were interpreted using estimated coefficients and odds ratios to quantify the relationship between patient characteristics and the probability of diabetes.



\### 4. Predictive Performance



Model performance was evaluated using classification and discrimination metrics, including:



\- ROC curve

\- Area Under the ROC Curve (AUC)

\- Confusion matrix

\- Sensitivity

\- Specificity

\- Classification threshold assessment



Predicted probabilities were generated for individual observations and incorporated into the processed analytical dataset.



\## Power BI Dashboard



!\[Diabetes Outcomes \& Risk Analysis Dashboard](Images/Diabetes\_Dashboard.png)



The Power BI dashboard provides an interactive summary of the study population and major diabetes risk patterns.



Key performance indicators include:



\- \*\*Total patients:\*\* 96,146

\- \*\*Patients with diabetes:\*\* 8,482

\- \*\*Diabetes prevalence:\*\* 8.8%



The dashboard also visualizes:



\- Diabetes prevalence by age group

\- Diabetes prevalence by BMI category

\- Diabetes status by hypertension status

\- Mean HbA1c by diabetes status

\- Mean blood glucose by diabetes status



\## Key Findings



Diabetes prevalence increased substantially with age. Prevalence was approximately \*\*0.9% among patients under 30\*\*, compared with \*\*20.5% among patients aged 60 years and older\*\*.



A strong BMI gradient was also observed. Diabetes prevalence increased from approximately \*\*0.8% among underweight patients\*\* to \*\*18.0% among patients classified as obese\*\*.



Patients with hypertension had a substantially higher prevalence of diabetes than patients without hypertension.



Patients with diabetes also demonstrated higher average HbA1c and blood glucose levels. Mean HbA1c was approximately \*\*6.9\*\* among patients with diabetes compared with \*\*5.4\*\* among patients without diabetes. Mean blood glucose was approximately \*\*194.0\*\* versus \*\*132.8\*\*, respectively.



These descriptive findings demonstrate clear relationships between diabetes and established metabolic and cardiovascular risk characteristics. Multivariable modeling was used to assess these relationships while considering multiple predictors simultaneously.



\## Tools \& Technologies



\- \*\*Python\*\* — data cleaning, exploratory analysis, statistical modeling, and model evaluation

\- \*\*pandas\*\* — data manipulation

\- \*\*NumPy\*\* — numerical operations

\- \*\*statsmodels / scikit-learn\*\* — statistical and predictive modeling

\- \*\*Matplotlib  — analytical visualization

\- \*\*Jupyter Notebook\*\* — reproducible analysis workflow

\- \*\*Power BI\*\* — dashboard development and interactive visualization

\- \*\*DAX\*\* — KPI measures and dashboard calculations

\- \*\*Power Query\*\* — data transformation and preparation



\## Repository Structure



```text

diabetes-outcomes-analytics/

│

├── data/

│   ├── raw/

│   └── processed/

│       └── diabetes\_clean.csv

│

├── notebooks/

│   └── diabetes\_data\_analysis.ipynb

│

├── powerbi/

│   └── Diabetes\_Outcomes\_Risk\_Analysis.pbix

│

├── images/

│   └── diabetes\_dashboard.png

│

└── README.md

```



\## Skills Demonstrated



This project demonstrates practical experience with:



\- Biostatistical analysis

\- Healthcare data analytics

\- Data cleaning and validation

\- Exploratory data analysis

\- Logistic regression

\- Odds-ratio interpretation

\- Predictive modeling

\- ROC/AUC analysis

\- Sensitivity and specificity

\- Data visualization

\- Power BI dashboard development

\- DAX

\- Communicating statistical findings to nontechnical audiences



\## Author



\*\*Sahadath Kadri\*\*  

Master's Student in Biostatistics

