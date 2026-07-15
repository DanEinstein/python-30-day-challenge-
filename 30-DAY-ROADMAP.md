# Python for Data Analysis — 30 Day Roadmap

A public 30-day challenge to build real data analysis skills with Python.

**Start:** Any time. Work at your own pace.
**Two tracks** — pick the one that fits your level.

---

## Pick Your Track

| Track | For | What You'll Cover |
|-------|-----|-------------------|
| **A** | You already know Python well (intermediate) | NumPy, Pandas, cleaning, SQL, EDA, Matplotlib, Seaborn, Streamlit, 2 projects |
| **B** | You know programming but are new to Python | Python syntax, NumPy basics, Pandas basics, cleaning, Matplotlib, Seaborn, 1 project |

---

# Track A — Intermediate Python

## Week 1 — Python + NumPy + Pandas Core (Days 1-7)

**Day 1** — Project setup
- Set up project structure
- Install: pandas, matplotlib, seaborn, jupyterlab, streamlit, sqlalchemy, duckdb
- Test JupyterLab, test import pandas
- Configure git, first commit

**Day 2** — Python refresher
- Comprehensions, generators, lambda, map/filter
- args/kwargs, built-ins (zip, enumerate, sorted)
- 10 exercises
- Output: `notebooks/python_refresher.ipynb`

**Day 3** — NumPy part 1
- ndarray creation, shapes, reshaping
- Indexing: basic, fancy, boolean, slicing
- Vectorized operations (no loops)
- Output: `notebooks/numpy_1.ipynb`

**Day 4** — NumPy part 2
- Broadcasting explained
- Linear algebra basics (dot, matmul, solve)
- Random module (distributions, seeds, shuffles)
- Output: `notebooks/numpy_2.ipynb`

**Day 5** — Pandas core
- Series + DataFrame from dicts, arrays, files
- read_csv, read_excel, read_json
- loc vs iloc, boolean filtering
- Output: `notebooks/pandas_1_core.ipynb`

**Day 6** — Pandas transform
- groupby + agg, merge/join/concat
- Pivot tables, melt
- Working with datetimes
- Output: `notebooks/pandas_2_transform.ipynb`

**Day 7** — Pandas advanced
- apply vs vectorized (when to use each)
- Multi-index
- Rolling/window functions
- Output: `notebooks/pandas_3_advanced.ipynb`

## Week 2 — Data Cleaning + SQL + EDA (Days 8-14)

**Day 8** — Missing values
- isnull, dropna, fillna, interpolation
- Forward/backward fill
- Output: `notebooks/cleaning_missing.ipynb`

**Day 9** — Outliers + strings
- IQR, Z-score, visual inspection
- String cleaning: strip, replace, split, regex basics
- Output: `notebooks/cleaning_outliers_strings.ipynb`

**Day 10** — Types + dates
- Type casting, category encoding
- Date parsing, resampling
- Output: `notebooks/cleaning_types_dates.ipynb`

**Day 11** — SQL with Python
- sqlite3 basics (CREATE, SELECT, WHERE, JOIN)
- Query results into DataFrames
- DuckDB (query CSV directly)
- Output: `notebooks/sql_with_python.ipynb`

**Day 12** — Web data
- requests for APIs (GET, JSON, headers)
- BeautifulSoup to scrape tables
- Output: `notebooks/web_data.ipynb`

**Day 13** — EDA part 1
- describe, info, value_counts
- Descriptive stats (mean, median, mode, variance, std)
- Correlation matrix
- Output: `notebooks/eda_1_stats.ipynb`

**Day 14** — EDA part 2
- Distribution analysis (histogram, boxplot)
- Relationship analysis (scatterplot, crosstab)
- Practice on a real dataset
- Output: `notebooks/eda_2_distributions.ipynb`

## Week 3 — Visualization (Days 15-21)

**Day 15** — Matplotlib part 1
- Figure + axes API, subplots
- Line, scatter, bar, histogram
- Output: `notebooks/matplotlib_1_basics.ipynb`

**Day 16** — Matplotlib part 2
- Customization (colors, legends, annotations, spines)
- Saving figures (SVG, PNG, correct DPI)
- Output: `notebooks/matplotlib_2_customize.ipynb`

**Day 17** — Seaborn part 1
- Distribution plots (histplot, kdeplot, ecdfplot)
- Categorical plots (boxplot, violinplot, stripplot)
- Output: `notebooks/seaborn_1_distributions.ipynb`

**Day 18** — Seaborn part 2
- Heatmaps, clustermaps
- Regression plots (lmplot, regplot)
- Pairplot, FacetGrid themes
- Output: `notebooks/seaborn_2_relationships.ipynb`

**Day 19** — Viz practice
- Pick any dataset (weather, sales, your choice)
- Create 6+ plots (Matplotlib + Seaborn)
- Tell a story with the charts
- Output: `notebooks/viz_practice.ipynb`

**Day 20** — Streamlit basics
- Streamlit widgets (slider, select, dataframe, chart)
- Layout (columns, sidebar)
- Output: `scripts/first_dashboard.py`

**Day 21** — Streamlit project
- Build a dashboard for a dataset (3+ widgets, 3+ charts)
- Output: `projects/01_dashboard/app.py`

## Week 4 — File Formats + Capstone (Days 22-30)

**Day 22** — File formats
- CSV vs Parquet vs Excel — when to use what
- Chunking large CSVs
- Memory optimization (dtypes, categoricals)
- Output: `notebooks/file_formats.ipynb`

**Day 23** — OOP for data analysis
- Simple data pipeline class (load, clean, analyze)
- Dunder methods for custom objects
- Output: `scripts/data_pipeline_class.py`

**Day 24** — Catch-up day
- Review anything you are shaky on
- Re-do notebooks you want to improve

**Day 25** — Capstone kickoff
- Choose a dataset (see suggestions below)
- Define 5 questions to answer
- Load + initial explore
- Output: `projects/capstone/plan.md`

**Day 26** — Capstone build day 1
- Clean the data
- Run full EDA
- Output: `projects/capstone/eda.ipynb`

**Day 27** — Capstone build day 2
- Create visualizations
- Build a Streamlit dashboard (optional)
- Output: `projects/capstone/viz_dashboard/`

**Day 28** — Capstone polish
- Review everything, refine insights
- Write clear findings (5+ insights)
- Output: `projects/capstone/insights.md`

**Day 29** — Portfolio prep
- Write README for both projects
- Add screenshots
- Clean up notebooks (remove dead cells, add comments)

**Day 30** — Review + publish
- Push everything to GitHub
- Write a retrospective
- Tag repo v1.0

---

# Track B — Python from Scratch (Programmer)

## Week 1 — Python Fundamentals (Days 1-7)

You already understand programming concepts. This week is about learning Python syntax.

**Day 1** — Setup
- Install Python 3.12, VS Code, JupyterLab
- Write your first Python code (print, input, variables)
- Run a .py file from terminal

**Day 2** — Data types and operations
- Integers, floats, booleans, strings
- Arithmetic (+ - * / // % **), comparison, logical operators
- Type casting: int(), float(), str(), bool()
- 5+ exercises

**Day 3** — Data structures
- Lists (index, slice, append, remove, sort)
- Tuples (vs lists)
- Dictionaries (key-value, get, update, loop)
- Sets (unique, union, intersection)
- 5+ exercises

**Day 4** — Control flow
- if, elif, else
- for loops over lists, dicts, range
- while loops, break, continue
- 5+ exercises

**Day 5** — Functions
- def, parameters, return values, defaults
- Lambda functions
- Built-ins: len, range, enumerate, zip, sorted, map
- 5+ exercises

**Day 6** — Strings and files
- split, join, strip, replace, upper, lower, find
- f-strings
- Reading and writing files (with statement)
- 5+ exercises

**Day 7** — Review and practice project
- 15 mixed exercises
- Build: CLI word counter (read file, count words, top 5)

## Week 2 — NumPy and Pandas (Days 8-14)

**Day 8** — NumPy part 1
- What is NumPy? Creating arrays
- arange, zeros, ones, linspace
- Shapes, basic ops (mean, sum, max, min)

**Day 9** — NumPy part 2
- Indexing and slicing (1D and 2D)
- Boolean masking
- Random numbers

**Day 10** — NumPy practice (10 exercises)

**Day 11** — Pandas part 1
- Series vs DataFrame
- read_csv, head, tail, info, describe

**Day 12** — Pandas part 2
- Selecting columns and rows (loc, iloc)
- Boolean filtering
- Add, rename, drop columns

**Day 13** — Pandas part 3
- Missing values (isna, dropna, fillna)
- groupby + aggregation
- Sorting

**Day 14** — Pandas practice
- Load tips/iris/titanic
- Filter, group, sort, find 3 facts

## Week 3 — Data Cleaning + Plots (Days 15-21)

**Day 15** — Cleaning 1: forward/backward fill, duplicates, rename

**Day 16** — Cleaning 2: strings (strip, lower, replace), type conversion, dates

**Day 17** — Outliers: IQR, Z-score, boxplots

**Day 18** — Matplotlib 1: line, scatter, bar, labels, legends

**Day 19** — Matplotlib 2: histograms, boxplots, subplots, savefig

**Day 20** — Matplotlib practice: 5 different plots on one dataset

**Day 21** — Seaborn basics: histplot, boxplot, scatter (hue), pairplot, heatmap

## Week 4 — Project (Days 22-30)

**Day 22** — Seaborn practice
**Day 23** — Catch-up
**Day 24** — Project kickoff: choose dataset, write 3 questions
**Day 25** — Clean data
**Day 26** — Analyse with groupby and stats
**Day 27** — Visualise (4+ plots)
**Day 28** — Write README with findings
**Day 29** — Polish notebooks + push to GitHub
**Day 30** — Review, retrospective, next goals

---

## Dataset Ideas

- **Tips** — built into Seaborn (`sns.load_dataset('tips')`)
- **Iris** — built into Seaborn
- **Titanic** — built into Seaborn (has missing values)
- **World Bank / African economic data** — Kaggle
- **Weather data** — Kaggle Global Weather Repository
- **Superstore sales** — classic Kaggle dataset
- **Your own data** — anything in CSV

---

## Folder Structure

```
python-30-day-challenge/
├── notebooks/         # Daily notebooks
├── scripts/           # Utility scripts
├── data/              # Datasets (gitignored)
├── projects/          # Capstone projects
├── 30-DAY-ROADMAP.md  # This file
└── README.md          # Repo intro
```

---

*Clone this repo, pick your track, and start Day 1.*
