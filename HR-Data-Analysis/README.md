# HR Data Analysis

## Organization

AFAME Technologies - Data Analyst Internship Project

## Objective

Analyze employee data to understand workforce composition, compensation, satisfaction, experience, department patterns, and attrition.

## Dataset

The original source file is [HR Data.csv](../HR%20Data.csv). It contains 1,470 employee records and 35 columns.

## Notebook

Open [HR_Data_Analysis.ipynb](notebooks/HR_Data_Analysis.ipynb).

## Analysis Included

- Dataset structure and field grouping
- Missing values, duplicate checks, data types, constant columns, and invalid-value checks
- Separate cleaned DataFrame
- Readable column names and standardized text
- Age, tenure, income, and experience groups
- Workforce, department, job role, and demographic analysis
- Attrition by department, role, age, marital status, overtime, travel, satisfaction, tenure, and income
- Compensation and career-growth analysis
- Satisfaction, correlation, and outlier analysis
- Business insights and practical retention recommendations
- Cleaned data and summary CSV exports
- Saved PNG charts

## Cleaning Decisions

- EmployeeCount, Over18, and StandardHours were removed because they are constant in this dataset.
- Employee Number was retained in the cleaned file as a unique identifier.
- No rows were dropped for missing values because the source contains no missing values.
- Exact duplicate rows and duplicate EmployeeNumbers were checked and found absent.

## Main Results

- Total employees: 1,470
- Attrition count: 237
- Attrition rate: 16.12%
- Sales had the highest department attrition rate at 20.63%.

## Outputs

- [cleaned_hr_data.csv](outputs/cleaned_hr_data.csv)
- [Summary CSV files](outputs/)
- [Chart images](outputs/charts/)

## Run

From the project root:

```cmd
python -m pip install -r requirements.txt
python -m jupyter notebook
```

Open the notebook and run **Restart & Run All**.
