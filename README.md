# 📊 Data Science Salaries Analysis

## 🔍 Project Overview
Exploratory Data Analysis (EDA) and Machine Learning model 
to analyze salaries in the Data Science field based on multiple factors.

## 📓 View Notebook

> ⚠️ Interactive charts (Plotly) are not supported on GitHub.
> To view the full notebook with all charts, open it via nbviewer.
> **Note:** Charts will appear as static images, not interactive.
> 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Saif-Ahmed0/Salaries-Analysis/blob/main/ds%20salaries%20for%20Company.ipynb)
> 
[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/Saif-Ahmed0/Salaries-Analysis/blob/main/ds_salaries_%20for_%20Company.ipynb)

## 📁 Dataset
The dataset contains information about Data Science salaries including:
| Column | Description |
|--------|-------------|
| `work_year` | Year of employment |
| `experience_level` | Entry / Mid / Senior / Expert |
| `employment_type` | Full-Time / Part-Time / Contract |
| `job_title` | Job position |
| `salary_in_usd` | Salary converted to USD |
| `remote_ratio` | 0% / 50% / 100% remote |
| `company_size` | Small / Medium / Large |
| `company_location` | Country of the company |

## 🎯 Key Findings
- Employees working in a **different country** than their company earn 
  on average **$3,259 more** than those in the same country.
- Employees with **no remote work** earn **$5,943 less** than average.
- **Large companies** pay higher salaries on average.
- Salary has been increasing year over year (2020 → 2022).

## 🛠️ Tools & Libraries
- **Pandas** & **NumPy** — Data manipulation
- **Seaborn** & **Matplotlib** — Static visualizations
- **Plotly** — Interactive charts
- **Scikit-learn** — Machine Learning (Random Forest Regressor)

## 🤖 ML Model
- Model: `RandomForestRegressor`
- Features: experience level, remote ratio, company size, etc.
- Target: `salary_in_usd`
- Preprocessing: Label Encoding + PCA

## 🚀 How to Run

1. Clone the repo:
```bash
   git clone https://github.com/Saif-Ahmed0/Salaries-Analysis.git
```

2. Install requirements:
```bash
   pip install numpy pandas seaborn matplotlib plotly kaleido==0.1.0post1 scikit-learn ipython
```

3. Open the notebook:
```bash
   jupyter notebook "ds_salaries_ for_ Company.ipynb"
```
