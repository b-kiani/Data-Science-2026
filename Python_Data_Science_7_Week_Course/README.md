# Python for Data Science — 7-Week Absolute-Beginner Course

This course assumes **no previous programming experience**. It contains 14 standalone Jupyter notebooks: two 90-minute sessions per week for seven teaching weeks.

Every session follows the same supportive pattern:

1. recall one earlier idea;
2. explain one new concept in plain language;
3. predict and run small code examples;
4. complete a guided analysis;
5. attempt five student coding tasks;
6. finish with a knowledge check and exit ticket.

The complete course contains **70 student coding tasks**. Starter task cells run safely before editing, but the marked instructions intentionally require students to complete or replace code.

## Course schedule

| Week | Session 1 | Session 2 |
|---:|---|---|
| 1 | Data, values, variables, and first Python statements | Data-science lifecycle and small business questions |
| 2 | Anaconda, environments, files, and reproducible setup | Jupyter workflow, packages, errors, and debugging |
| 3 | Lists, indexing, slicing, and tuples | Dictionaries, sets, and nested records |
| 4 | Functions, parameters, `*args`, `**kwargs`, scope, and lambda | `while` loops, `for` loops, and comprehensions |
| 5 | NumPy arrays, shapes, construction, and numeric operations | Indexing, filtering, axes, broadcasting, and concatenation |
| 6 | pandas Series, DataFrames, `.loc`, `.iloc`, and filtering | Missing data, cleaning, grouping, aggregation, and merging |
| 7 | Relational databases, SQLAlchemy engines, tables, and CRUD | Inner/left/right joins, unmatched keys, and a mini-project |

## Recommended installation

Open **Anaconda Prompt** on Windows or a terminal on macOS/Linux, then run one command at a time:

```bash
conda create --name python-ds python=3.12 -y
conda activate python-ds
conda install numpy pandas jupyterlab sqlalchemy -y
jupyter lab
```

Alternatively, after creating and activating the environment:

```bash
python -m pip install -r requirements.txt
jupyter lab
```

In JupyterLab, open the notebooks in the order below. Run a cell with **Shift + Enter**. If the kernel is restarted, use **Run → Run All Cells** from the top rather than continuing from hidden state.

## Notebook order

1. `W01_S01_Data_and_Data_Science.ipynb`
2. `W01_S02_Lifecycle_and_Business_Cases.ipynb`
3. `W02_S01_Environment_and_Anaconda.ipynb`
4. `W02_S02_Jupyter_Packages_and_Debugging.ipynb`
5. `W03_S01_Lists_and_Tuples.ipynb`
6. `W03_S02_Dictionaries_Sets_and_Nested_Data.ipynb`
7. `W04_S01_Functions_Args_Kwargs_Scope_Lambda.ipynb`
8. `W04_S02_Loops_and_Comprehensions.ipynb`
9. `W05_S01_NumPy_Arrays_Indexing_Slicing.ipynb`
10. `W05_S02_NumPy_Vectorisation_Broadcasting.ipynb`
11. `W06_S01_Pandas_Series_DataFrames_Loc_Iloc.ipynb`
12. `W06_S02_Pandas_Cleaning_Missing_Data.ipynb`
13. `W07_S01_SQLAlchemy_Engines_Tables_CRUD.ipynb`
14. `W07_S02_SQL_Joins_and_Capstone.ipynb`

## Notes for lecturers

- Demonstrate each worked example before asking students to change it.
- Ask students to predict output aloud; prediction exposes misconceptions early.
- Keep student task solutions in a separate instructor copy if required.
- Use task checklists for peer review and short formative assessment.
- SQLAlchemy notebooks use an in-memory SQLite database, so practice work does not modify an external database.
- The SQLAlchemy cells detect a missing installation and display the installation command instead of stopping the notebook.

## Quality checks completed

- all 14 files use valid Jupyter Notebook format;
- every code cell passes Python syntax validation;
- every notebook runs from top to bottom in a fresh namespace;
- code outputs and execution counters are cleared for students;
- cell identifiers are unique within each notebook;
- every session contains exactly five marked coding tasks.
