# EDA-using-Python-Jupyter-Notebook-
Exploratory Data Analysis (EDA) on the Titanic dataset using Python, Pandas, Matplotlib, and Seaborn. Includes data cleaning, feature engineering, visual &amp; statistical exploration, and key survival insights.
## Key Steps

1. **Load Data** – Import training and test datasets (`train.csv` and `test.csv`) into pandas DataFrames.

2. **Initial Exploration** – Use `.info()`, `.describe()`, and `.value_counts()` to understand:
   - Column types
   - Missing values
   - Basic distribution

3. **Data Cleaning** – Handle missing values for **Age**, **Fare**, and **Embarked** using **median/mode imputation**.

4. **Feature Engineering** – Create new features such as:
   - **FamilySize**
   - **IsAlone**
   - **Title** (extracted from passenger names)
   - **Age Groups**
   - **Fare Groups**

5. **Data Visualization** – Use:
   - Histograms
   - Boxplots
   - Scatterplots
   - Pairplots
   - Heatmaps  
   to investigate distributions and correlations.

6. **Observation & Insights** – Interpret visual and statistical findings to identify factors affecting survival.
