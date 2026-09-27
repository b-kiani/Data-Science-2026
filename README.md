# Data Science for Business

### Central Asian University · Business School

[![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![pandas](https://img.shields.io/badge/pandas-data%20analysis-150458?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-machine%20learning-F7931E?logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![GitHub](https://img.shields.io/badge/GitHub-reproducible%20projects-181717?logo=github&logoColor=white)](https://github.com/)

> **Practical Data Science with Python and Jupyter — from business question to actionable insight.**

This repository supports a practical, notebook-based **Data Science for Business** course at **Central Asian University Business School**.

Students learn to move from a business problem through data import, cleaning, exploratory analysis, preprocessing, feature engineering, machine learning, evaluation, and business communication — with GitHub used to organize and reproduce their work.

---

## 📚 Primary Reference

**Prateek Gupta**  
*Practical Data Science with Jupyter: Explore Data Cleaning, Pre-processing, Data Wrangling, Feature Engineering and Machine Learning using Python and Jupyter*  
**BPB Publications**

The course is an original teaching adaptation organized around the practical topics and learning sequence of the reference book.

> **Copyright note:** This repository does not reproduce the textbook. Course lectures, exercises, datasets, assessments, and project materials should be developed as original teaching materials. The textbook remains the copyrighted property of its author and publisher.

---

## 🎯 Course Goal

The central idea is simple:

```text
Business Question
       ↓
Data
       ↓
Data Understanding
       ↓
Data Cleaning
       ↓
Exploratory Analysis
       ↓
Preprocessing
       ↓
Feature Engineering
       ↓
Statistical / ML Model
       ↓
Evaluation
       ↓
Business Interpretation
       ↓
Communication
       ↓
Reproducible GitHub Project
```

### Business first. Model second.

A machine-learning model is only useful when it helps investigate a meaningful business question.

Throughout the course, students practice answering:

1. **What is the business problem?**
2. **What data can help answer it?**
3. **What analytical method is appropriate?**
4. **What could the results mean for the organization?**

---

## 🧠 Learning Outcomes

By the end of the course, students should be able to:

- Work confidently with **Python and Jupyter Notebook**
- Use **NumPy and pandas** for data analysis
- Import data from CSV, Excel, JSON, text, and other supported formats
- Inspect datasets and identify data-quality problems
- Clean missing, inconsistent, and incorrectly formatted data
- Perform **exploratory data analysis (EDA)**
- Create and interpret business-focused visualizations
- Preprocess data for machine learning
- Engineer useful features from raw business data
- Build **classification and regression** models
- Apply train/test splitting and cross-validation
- Understand and apply common supervised-learning algorithms
- Use **K-means, hierarchical clustering, PCA, and t-SNE**
- Work with time-series data and forecasting methods
- Evaluate models using appropriate metrics
- Interpret analytical results in a business context
- Build reproducible data-science projects with **Git and GitHub**

---

## 🗺️ Course Roadmap

| Week | Module | Main Topics |
|---:|---|---|
| 01 | **Data Science & Business** | Data science fundamentals, business problems, Python |
| 02 | **Python Foundations** | Lists, dictionaries, functions, loops, packages |
| 03 | **NumPy & pandas** | Arrays, Series, DataFrames, indexing, wrangling |
| 04 | **Databases & Statistics** | SQLAlchemy, descriptive statistics, probability, correlation |
| 05 | **Data Import** | CSV, Excel, JSON, text and other formats |
| 06 | **Data Cleaning** | Missing values, dates, encoding, inconsistencies, scaling |
| 07 | **EDA & Visualization** | Distributions, relationships, trends, outliers |
| 08 | **Preprocessing & Feature Engineering** | Transformation, categorical variables, model-ready data |
| 09 | **Classification** | Logistic regression, trees, KNN, LDA, Naive Bayes, SVC |
| 10 | **Regression** | Regression workflows, evaluation, cross-validation, tuning |
| 11 | **Unsupervised ML** | K-means, hierarchical clustering, PCA, t-SNE |
| 12 | **Time Series** | Time-based data, transformations, forecasting |
| 13 | **Business Case Studies** | Loan repayment, spam, recommendations, house prices |
| 14 | **Professional Data Science** | Virtual environments, GitHub, README, CatBoost, final project |

> The 14-week schedule is a proposed teaching adaptation, not a schedule stated by the textbook.

---

## 🧰 Technology Stack

| Tool | Purpose |
|---|---|
| **Python** | Programming and analysis |
| **Jupyter Notebook** | Interactive analysis and reporting |
| **NumPy** | Numerical computing |
| **pandas** | Data manipulation and wrangling |
| **Matplotlib** | Data visualization |
| **scikit-learn** | Machine learning |
| **SQLAlchemy** | Database workflows |
| **Git** | Version control |
| **GitHub** | Collaboration and reproducible project delivery |
| **CatBoost** | Advanced machine-learning topic |

---

## 📂 Repository Structure

```text
data-science-business-cau/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── data/
│   ├── raw/
│   ├── processed/
│   └── README.md
│
├── notebooks/
│   ├── 01_data_science_business_problem.ipynb
│   ├── 02_python_foundations.ipynb
│   ├── 03_numpy_pandas.ipynb
│   ├── 04_statistics_and_business_question.ipynb
│   ├── 05_data_import.ipynb
│   ├── 06_data_cleaning.ipynb
│   ├── 07_exploratory_data_analysis.ipynb
│   ├── 08_preprocessing_feature_engineering.ipynb
│   ├── 09_classification_model.ipynb
│   ├── 10_regression_model.ipynb
│   ├── 11_customer_segmentation.ipynb
│   ├── 12_time_series_forecasting.ipynb
│   └── final_project.ipynb
│
├── src/
│   ├── data_cleaning.py
│   ├── feature_engineering.py
│   └── modeling.py
│
├── reports/
│   ├── figures/
│   └── final_report.md
│
└── presentations/
    └── final_presentation.pdf
```

---

## 🔬 Practical Modules

### 01 · Data Science Fundamentals

Introduction to data science, types of data, the role of the data scientist, business applications, and Python.

**Deliverable:** `01_data_science_business_problem.ipynb`

### 02 · Python Foundations

Lists, tuples, dictionaries, indexing, loops, functions, parameters, scope, lambda functions, and package imports.

**Business practice:** Calculate sales totals, customer metrics, transaction summaries, and KPIs.

### 03 · NumPy & pandas

NumPy arrays, pandas Series and DataFrames, indexing, slicing, inspection, and data manipulation.

**Deliverable:** `03_numpy_pandas.ipynb`

### 04 · Databases & Statistics

SQLAlchemy, database operations, joins, descriptive statistics, probability, distributions, correlation, inference, and hypothesis testing.

### 05 · Data Import

Work with CSV, Excel, JSON, text, pickle, and compressed data.

**Core habit:** Understand the structure and quality of the data before analyzing it.

### 06 · Data Cleaning

- Missing values
- Dropping and filling missing observations
- Scaling and normalization
- Date parsing
- Character encoding
- Inconsistent data

**Deliverable:** `06_data_cleaning.ipynb`

### 07 · Exploratory Data Analysis

Use:

- Bar charts
- Line charts
- Histograms
- Scatter plots
- Stacked plots
- Box plots

The objective is to investigate distributions, relationships, trends, differences, outliers, and potential data-quality issues.

### 08 · Preprocessing & Feature Engineering

Transform a cleaned dataset into a model-ready dataset and document **what changed, why it changed, and how it affects the analysis**.

### 09 · Supervised Learning — Classification

Topics include:

- Logistic regression
- Decision trees
- K-nearest neighbors
- Linear discriminant analysis
- Gaussian Naive Bayes
- Support vector classification
- Train/test splitting
- Cross-validation
- Model tuning
- Categorical variables

**Business examples:** loan repayment, customer churn, spam detection, and lead conversion.

### 10 · Supervised Learning — Regression

Build models for continuous business outcomes such as sales, revenue, demand, property prices, or customer value.

Evaluation includes metrics such as **MAE** and **MSE**.

### 11 · Unsupervised Learning

Explore:

- K-means clustering
- Hierarchical clustering
- PCA
- t-SNE
- Unsupervised-model validation

**Business application:** customer and market segmentation.

### 12 · Time-Series Analytics

Work with dates, transformations, changing frequencies, growth rates, and forecasting methods including:

- AR
- MA
- ARMA
- ARIMA
- SARIMA
- SARIMAX
- VARMA
- Holt-Winters exponential smoothing

### 13 · Applied Case Studies

The reference material includes four case-study themes:

| Case | Analytical Focus |
|---|---|
| **Loan repayment prediction** | Classification |
| **Spam-message classification** | Text classification |
| **Film recommendation engine** | Recommendation |
| **House-sale prediction** | Regression |

These themes can be supplemented with locally relevant business datasets while preserving the same learning objectives.

### 14 · Professional Data Science

Students learn to:

- Create Python virtual environments
- Maintain `requirements.txt`
- Write effective project documentation
- Structure a GitHub repository
- Document experiments
- Make projects reproducible
- Explore CatBoost

---

## 📝 Notebook Standard

Every major notebook should follow a consistent structure:

```markdown
# Project Title

## 1. Business Question

## 2. Objective

## 3. Data Description

## 4. Data Preparation

## 5. Exploratory Data Analysis

## 6. Data Cleaning

## 7. Feature Engineering

## 8. Modeling

## 9. Evaluation

## 10. Business Interpretation

## 11. Limitations

## 12. Conclusion
```

### Coding standard

Students should:

- Use meaningful variable names
- Avoid unnecessary repeated code
- Use functions where appropriate
- Comment non-obvious logic
- Keep notebook cells focused
- Run notebooks from beginning to end before submission
- Make outputs understandable to another reader

---

## 📊 Assessment

A proposed course assessment structure:

| Component | Weight |
|---|---:|
| Python & Jupyter labs | 15% |
| Data cleaning & EDA assignments | 15% |
| Statistics assignment | 10% |
| Machine-learning assignments | 20% |
| Time-series assignment | 10% |
| Business case study | 10% |
| Final project | 20% |
| **Total** | **100%** |

> These percentages are a proposed course design and are not taken from the reference book.

Assessment considers both **technical execution** and **business reasoning**.

---

## 🚀 Final Project

Students complete an end-to-end data-science project addressing a real business or organizational question.

### Possible themes

- Customer segmentation
- Customer churn
- Sales analysis
- Demand forecasting
- Marketing campaign analysis
- Credit-risk modeling
- Pricing analysis
- Employee analytics
- Retail analytics
- Supply-chain analytics
- Recommendation systems
- Fraud or anomaly analysis

### Required components

- [ ] Clearly defined business problem
- [ ] Dataset and source description
- [ ] Exploratory data analysis
- [ ] Data cleaning
- [ ] Preprocessing
- [ ] Feature engineering
- [ ] Appropriate analytical/modeling method
- [ ] Model evaluation where applicable
- [ ] Business interpretation
- [ ] Limitations and risks
- [ ] Reproducible GitHub repository
- [ ] Final presentation

---

## 💻 Environment Setup

Create an isolated Python environment:

```bash
python -m venv .venv
```

Activate the environment for your operating system, then install dependencies:

```bash
pip install -r requirements.txt
```

Start Jupyter:

```bash
jupyter notebook
```

### Example `requirements.txt`

```text
jupyter
numpy
pandas
matplotlib
scikit-learn
sqlalchemy
```

Add other packages only when they are required by a project.

---

## 🔄 GitHub Workflow

```text
Create Repository
       ↓
Clone Repository
       ↓
Create Python Environment
       ↓
Add Data / Notebooks / Source Code
       ↓
Run & Test Notebook
       ↓
Document Work
       ↓
Commit Changes
       ↓
Push to GitHub
```

### Suggested commit messages

```text
Add initial EDA notebook
Clean missing values
Add customer segmentation model
Improve feature engineering
Update project README
Add final analysis
```

---

## 🧪 Practical Labs

| Lab | Focus |
|---:|---|
| 01 | Business Data Discovery |
| 02 | Python for Business Analytics |
| 03 | pandas Data Wrangling |
| 04 | Data Quality Audit |
| 05 | Exploratory Data Analysis |
| 06 | Feature Engineering |
| 07 | Classification |
| 08 | Regression |
| 09 | Customer Segmentation |
| 10 | Time-Series Forecasting |
| 11 | Reproducible GitHub Project |
| 12 | Final Business Case |

---

## 💼 Business Communication

Data science does not stop at model accuracy.

Students practice translating:

```text
DATA
  ↓
ANALYSIS
  ↓
EVIDENCE
  ↓
INSIGHT
  ↓
BUSINESS IMPLICATION
  ↓
DECISION SUPPORT
```

A final presentation should clearly communicate:

- The business question
- The most important evidence
- What the analysis or model tells us
- Uncertainty and limitations
- Potential business implications

---

## 🛡️ Responsible Data Science

Students should consider:

- Data privacy
- Data quality
- Sampling limitations
- Missing information
- Potential bias
- Inappropriate feature use
- Data leakage
- Misleading visualizations
- Overfitting
- Model limitations
- Prediction uncertainty

A model's output should be treated as analytical evidence, not automatically as a correct answer.

---

## 📋 Student Submission Checklist

Before submitting a project:

- [ ] Business problem is clearly stated
- [ ] Dataset is described
- [ ] Data quality has been investigated
- [ ] Missing values have been considered
- [ ] Data types have been checked
- [ ] Relevant visualizations are included
- [ ] Feature engineering is explained
- [ ] Train/test separation is handled appropriately
- [ ] Selected model is explained
- [ ] Evaluation metrics are appropriate
- [ ] Results are interpreted in business language
- [ ] Limitations are documented
- [ ] Notebook runs from start to finish
- [ ] `requirements.txt` is included
- [ ] `README.md` explains how to reproduce the project
- [ ] Repository is organized and readable
- [ ] Data sources and external references are acknowledged

---

## 📖 Reference

**Gupta, Prateek.** *Practical Data Science with Jupyter: Explore Data Cleaning, Pre-processing, Data Wrangling, Feature Engineering and Machine Learning using Python and Jupyter.* BPB Publications.

The reference material covers data-science fundamentals, Python, NumPy, pandas, databases, statistics, data import, data cleaning, visualization, preprocessing, supervised and unsupervised machine learning, time-series analysis, practical case studies, virtual environments, GitHub practices, and CatBoost.

> This repository is an original course adaptation and should not redistribute or reproduce substantial portions of the textbook.

---

## 🏫 Central Asian University · Business School

**Course:** Data Science for Business  
**Environment:** Python + Jupyter Notebook  
**Approach:** Practical · Business-focused · Reproducible  
**Reference:** Prateek Gupta, BPB Publications

### Course Motto

> **Learn → Apply → Interpret → Communicate → Repeat**

---

<p align="center">
  <sub>Data Science for Business · Central Asian University Business School</sub>
</p>
