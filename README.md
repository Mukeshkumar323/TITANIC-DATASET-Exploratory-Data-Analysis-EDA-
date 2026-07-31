# Exploratory Data Analysis (EDA)

## Objective
The objective of this project is to explore and analyze the dataset using Python. The analysis includes understanding the data structure, identifying missing values, examining relationships between variables, visualizing trends, and summarizing key insights.

## Tools and Libraries
- Python
- Google Colab
- Pandas
- Matplotlib
- Seaborn

## Dataset
- Dataset: `test 1.csv`
- The dataset was loaded using Pandas and analyzed through descriptive statistics and visualizations.

## Tasks Performed

### 1. Data Inspection
- Used `df.head()` to preview the dataset.
- Used `df.info()` to examine data types and missing values.
- Used `df.describe()` to generate statistical summaries.
- Used `df.value_counts()` to analyze categorical variables.

### 2. Data Quality Checks
- Checked for missing values using `df.isnull().sum()`.
- Checked for duplicate records using `df.duplicated().sum()`.

### 3. Exploratory Data Analysis
The following visualizations were created:
- Pair Plot (`sns.pairplot()`)
- Correlation Heatmap (`sns.heatmap()`)
- Histograms
- Boxplots
- Scatter Plots
- Count Plots

## Observations

### Pair Plot
- Shows relationships among numerical variables.
- Helps identify clusters, trends, and outliers.

### Correlation Heatmap
- Displays correlation between numerical features.
- Strong positive correlations indicate variables that increase together.
- Negative correlations indicate inverse relationships.

### Histogram
- Displays the distribution of numerical variables.
- Helps identify skewness and data spread.

### Boxplot
- Detects outliers.
- Shows median and quartiles for each numerical feature.

### Scatter Plot
- Visualizes the relationship between two numerical variables.
- Useful for identifying positive or negative trends.

### Count Plot
- Displays the frequency of categorical variables.
- Helps compare category distributions.

## Summary of Findings
- The dataset was successfully explored using descriptive statistics and visualization techniques.
- Missing values and duplicate records were identified.
- Numerical variables were analyzed using histograms and boxplots.
- Correlation analysis revealed relationships between features.
- Scatter plots highlighted trends between numerical variables.
- Overall, the dataset is suitable for further analysis, machine learning, or dashboard development after necessary preprocessing.

## Conclusion
This project demonstrates the fundamental steps of Exploratory Data Analysis (EDA). The insights obtained through statistical summaries and visualizations provide a better understanding of the dataset and support informed decision-making for future analysis.
