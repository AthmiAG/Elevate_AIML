short note on what i have done and learned

files list :

input dataset: titanic.csv

code file: task1.ipynb

output dataset: cleaned_dataset.csv

miniguide vs my code: task1_report.docx

brief on code:

1.Importing Libraries

Learned to use essential libraries: pandas, numpy, matplotlib, seaborn, sklearn, missingno, scipy.stats for data handling, visualization, and preprocessing.

2.Loading Dataset

Used pd.read_csv() to load the dataset.

Made a backup copy for comparison (df_original).

3.Basic Info & Exploration

Understood the dataset structure: shape, column names, data types, null values, and basic statistics using df.info(), df.describe().

4.Missing Data Visualization

Used missingno.matrix() to visually inspect missing data patterns.

5.Handling Missing Values

Replaced missing numeric values with mean.

Replaced missing categorical values with mode.

6.Removing Duplicates

Identified and removed duplicate rows using .duplicated() and .drop_duplicates().

7.Fixing Data Types

Attempted to convert object columns to numeric or datetime formats for better processing.

8.Encoding Categorical Variables

Used LabelEncoder to convert string categories into numerical codes for ML algorithms.

9.Grouping Rare Categories

Replaced infrequent categorical values (less than 1%) with a common label: 'Other'.

10.Skewness Correction

Applied np.log1p() transformation to reduce skewness in highly skewed numeric columns.

11.Outlier Detection

Used Z-Score to detect and remove outliers beyond ±3 standard deviations.

12.Boxplot Visualization

Visualized cleaned numerical data using seaborn.boxplot() to ensure outliers are handled.

13.Normalization/Standardization

Applied StandardScaler to scale numeric values for uniformity (mean = 0, std = 1).

14.Final Cleaning Summary

Reviewed final dataset stats, nulls, and column types using a custom cleaning_summary() function.

15.Save Cleaned Data

Exported the cleaned dataset to a new CSV file for future use.
