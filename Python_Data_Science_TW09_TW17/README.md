# Python for Data Science — TW9 to TW17

This package extends the absolute-beginner course with **18 standalone Jupyter notebooks**: two 90-minute sessions for each teaching week from TW9 through TW17.

The numbering follows the supplied syllabus. TW8 is not included because no TW8 topic was provided.

## Learning design

Each session contains:

1. explicit learning outcomes and a timed lesson plan;
2. short explanations before every new technique;
3. complete, runnable worked examples;
4. one guided analysis;
5. five marked student coding challenges;
6. success criteria, knowledge checks, and preparation.

The extension includes **90 student coding challenges**. Starter task cells run safely before editing but intentionally require students to complete the requested work.

## Teaching schedule

| Week | Session 1 | Session 2 |
|---:|---|---|
| TW9 | Variables, descriptive statistics, and probability | Distributions, Pearson correlation, and hypothesis testing |
| TW10 | Importing text, CSV, and Excel | Importing JSON, trusted pickle, gzip, ZIP, and chunked data |
| TW11 | Profiling and missing-data decisions | Scaling, dates, encodings, and inconsistent data |
| TW12 | Bar, line, and histogram charts | Scatter, stacked, and box plots for business storytelling |
| TW13 | Case study: import, audit, clean, and explore | Feature engineering and reproducible preprocessing |
| TW14 | Logistic regression, decision tree, and k-NN | LDA, Gaussian Naive Bayes, SVC, cross-validation, and regression |
| TW15 | K-means and hierarchical clustering | PCA, t-SNE, and unsupervised validation |
| TW16 | Datetime indexes, lags, rolling windows, and resampling | Growth, frequency changes, interpolation, and time-aware validation |
| TW17 | End-to-end final-project workshop | Presentations, reproducibility audit, peer review, and module review |

## Installation

Open Anaconda Prompt on Windows or a terminal on macOS/Linux and run one command at a time:

~~~bash
conda create --name python-ds-advanced python=3.12 -y
conda activate python-ds-advanced
python -m pip install -r requirements.txt
jupyter lab
~~~

Start JupyterLab from the extracted course folder so the notebooks can locate the relative data directory.

## Notebook order

1. TW09_S01_Statistical_Variables_Descriptive_Probability.ipynb
2. TW09_S02_Distributions_Correlation_Hypothesis_Testing.ipynb
3. TW10_S01_Importing_Text_CSV_Excel.ipynb
4. TW10_S02_Importing_JSON_Pickle_Compressed.ipynb
5. TW11_S01_Profiling_and_Missing_Data.ipynb
6. TW11_S02_Scaling_Dates_Encoding_Inconsistency.ipynb
7. TW12_S01_Bar_Line_Histogram_Charts.ipynb
8. TW12_S02_Scatter_Stacked_Box_Storytelling.ipynb
9. TW13_S01_Case_Study_Import_Clean_EDA.ipynb
10. TW13_S02_Feature_Engineering_Preprocessing.ipynb
11. TW14_S01_Supervised_Classification.ipynb
12. TW14_S02_Cross_Validation_Models_Regression.ipynb
13. TW15_S01_KMeans_Hierarchical_Clustering.ipynb
14. TW15_S02_PCA_TSNE_Unsupervised_Validation.ipynb
15. TW16_S01_Datetime_Lags_Rolling_Resampling.ipynb
16. TW16_S02_Growth_Frequency_Time_Validation.ipynb
17. TW17_S01_Final_Project_Workshop.ipynb
18. TW17_S02_Presentations_Review_Reproducibility.ipynb

## Supplied data

The data directory contains import-format examples and four synthetic analysis datasets. Read DATA_DICTIONARY.md before teaching with them.

- business_sales_dirty.csv supports cleaning, visualisation, and preprocessing.
- monthly_sales.csv supports time-series work.
- customer_churn.csv supports supervised classification.
- customer_segments.csv supports clustering and dimensionality reduction.
- Text, CSV, Excel, JSON, pickle, gzip, and ZIP examples support TW10.

All records are synthetic and contain no confidential or personal information.

## Safety note about pickle

The supplied sample_table.pkl was generated locally for this course. Python pickle files can execute malicious code when loaded. Students must never open an emailed, downloaded, or otherwise untrusted pickle.

## Lecturer notes

- Demonstrate prediction before execution: ask students what a cell will produce and why.
- Require a sentence interpreting every important statistic, metric, or chart.
- Mark reasoning, validation, and limitations as well as code correctness.
- Keep the final test set untouched until model decisions are complete.
- Treat clustering and t-SNE outputs as exploratory rather than objective customer truths.
- Require causal wording to match the study design.
- Run TW17 projects from a clean kernel before presentations.

## Validation completed

- all 18 notebooks use valid Jupyter Notebook format;
- every code cell passes Python syntax validation;
- every notebook runs from top to bottom with the supplied environment and data;
- chart notebooks run successfully with a non-interactive backend;
- code outputs and execution counters are cleared;
- cell identifiers are unique within each notebook;
- every session contains exactly five marked coding tasks.
