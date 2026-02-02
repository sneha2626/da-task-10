# da-task-10
# Python-EDA
Dataset Name: Students Performance Dataset

Tools & Technologies

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook 

EDA Steps Performed
1️ Data Loading & Inspection

Loaded the dataset using pandas.read_csv()

Checked dataset shape, column types, and sample rows using:

.shape

.info()

.head()

2️ Descriptive Statistics

Generated summary statistics using .describe()

Analyzed mean, spread, and range of student scores

3️ Missing Value Analysis

Calculated missing value percentage for each column

Verified that the dataset contains no significant missing data
Distribution Analysis

Plotted histograms for math, reading, and writing scores

Used boxplots to visually identify potential outliers

5️ Outlier Detection (IQR Method)

Applied the Interquartile Range (IQR) method to detect extreme values

Created individual outlier flags for each score

6️ Outlier Flagging

Combined individual outlier indicators into a single outlier_flag column

Identified students with any extreme score

7️ Outlier Handling

Removed rows flagged as outliers to avoid skewed analysis

Justified removal to improve statistical stability

8️ Correlation Analysis

Computed correlation matrix for score variables

Visualized correlations using a heatmap

Identified strong positive relationships between reading and writing scores

9️ Export Cleaned Dataset

Saved the cleaned dataset as cleaned_dataset.csv for reuse
