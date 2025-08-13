# EDA-using-Python-Jupyter-Notebook-
Exploratory Data Analysis (EDA) on the Titanic dataset using Python, Pandas, Matplotlib, and Seaborn. Includes data cleaning, feature engineering, visual &amp; statistical exploration, and key survival insights.

    <h2>Key Steps:</h2>

    <ol>
        <li>
            <b>Load Data</b> – Import training and test datasets (<code>train.csv</code> and <code>test.csv</code>) into pandas DataFrames.
        </li>

        <li>
            <b>Initial Exploration</b> – Use <code>.info()</code>, <code>.describe()</code>, and <code>.value_counts()</code> 
            to understand:
            <ul>
                <li>Column types</li>
                <li>Missing values</li>
                <li>Basic distribution</li>
            </ul>
        </li>

        <li>
            <b>Data Cleaning</b> – Handle missing values for <b>Age</b>, <b>Fare</b>, and <b>Embarked</b> using 
            <b>median/mode imputation</b>.
        </li>

        <li>
            <b>Feature Engineering</b> – Create new features such as:
            <ul>
                <li><b>FamilySize</b></li>
                <li><b>IsAlone</b></li>
                <li><b>Title</b> (extracted from passenger names)</li>
                <li><b>Age Groups</b></li>
                <li><b>Fare Groups</b></li>
            </ul>
        </li>

        <li>
            <b>Data Visualization</b> – Use:
            <ul>
                <li>Histograms</li>
                <li>Boxplots</li>
                <li>Scatterplots</li>
                <li>Pairplots</li>
                <li>Heatmaps</li>
            </ul>
            to investigate distributions and correlations.
        </li>

        <li>
            <b>Observation & Insights</b> – Interpret visual and statistical findings to identify factors affecting survival.
        </li>
    </ol>
