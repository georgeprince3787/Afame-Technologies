# AFAME Technologies - Data Analyst Internship Projects

This repository contains two complete, end-to-end data analysis projects completed with the real datasets provided for the AFAME Technologies Data Analyst Internship.

## Project Overview

The projects cover sales performance and workforce attrition analysis. The complete executable workflows are in Jupyter Notebooks, with cleaned datasets and chart outputs saved for portfolio use.

## Projects

| Project | Notebook | Focus |
|---|---|---|
| Sales Data Analysis | [Sales_Data_Analysis.ipynb](Sales-Data-Analysis/notebooks/Sales_Data_Analysis.ipynb) | Revenue, profit, products, customers, regions, shipping, and discounts |
| HR Data Analysis | [HR_Data_Analysis.ipynb](HR-Data-Analysis/notebooks/HR_Data_Analysis.ipynb) | Workforce composition, compensation, satisfaction, tenure, and attrition |

## Key Findings

**Sales**
- Total sales: $12,642,501.91
- Total profit: $1,467,457.29
- Unique orders: 25,035
- The top product by sales was Apple Smart Phone, Full Size at $86,935.78.
- The Central region was the largest regional contributor at $2,822,302.52.

**HR**
- Total employees: 1,470
- Attrition count: 237
- Attrition rate: 16.12%
- Sales had the highest department attrition rate at 20.63%.

These findings are calculated from the actual source data and include supportive tables and charts in the notebooks.

## Repository Structure

```text
Afame-Technologies/
|-- README.md
|-- ECOMM DATA.xlsx
|-- HR Data.csv
|-- requirements.txt
|-- .gitignore
|-- Sales-Data-Analysis/
|   |-- notebooks/
|   |-- outputs/
|   `-- README.md
`-- HR-Data-Analysis/
    |-- notebooks/
    |-- outputs/
    `-- README.md
```

The original datasets remain in the project root. This avoids duplicate copies of the source files.

## Technologies

- Python
- pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- openpyxl
- Jupyter Notebook
- SciPy

## Setup on Windows

Open Command Prompt and run each command separately:

```cmd
cd /d C:\path\to\Afame-Technologies
python -m venv .venv
.venv\Scripts\activate
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
python -m pip install ipykernel
python -m ipykernel install --user --name afame-data-analysis
python -m jupyter notebook
```

Open each notebook from the Jupyter interface and select the `afame-data-analysis` kernel if prompted.

## GitHub Upload

Replace the placeholder values before running the GitHub commands.

```cmd
cd /d C:\path\to\Afame-Technologies
git init
git status
git add .
git commit -m "Complete AFAME sales and HR data analysis projects"
git branch -M main
git remote add origin https://github.com/<YOUR_GITHUB_USERNAME>/Afame-Technologies.git
git push -u origin main
```

Create the `Afame-Technologies` repository on GitHub before the `git remote add` command. The GitHub username must be added by the repository owner and should not be guessed.

## Notebook Publishing

- GitHub renders `.ipynb` files directly.
- For an alternate renderer, use https://nbviewer.org/ and paste the notebook's raw GitHub URL.
- The notebooks can also be opened in Google Colab by uploading the notebook or by using a Colab URL for the GitHub-hosted file.

Notebooks are analytical documents, not deployed applications. GitHub hosting does not create an interactive dashboard.

## Optional Streamlit Extension

A separate Streamlit application may use the validated cleaned CSV files, but it should not replace the notebooks as the complete analysis. To deploy it later, add `streamlit` to `requirements.txt`, create `app.py`, test it locally with `streamlit run app.py`, and then deploy it to Streamlit Community Cloud from the public GitHub repository.

## Author and Project Information
**Student:** [George Prince]  
**Organization:** AFAME Technologies  
**LinkedIn:** [[LinkedIn URL](https://www.linkedin.com/in/georgeprince3787/)]  
**GitHub:** [[GitHub URL](https://github.com/georgeprince3787)]
