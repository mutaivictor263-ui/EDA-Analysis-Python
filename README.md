Efploratory Data Analysis (EDA) is a crucial step in the data analysis process. It involves summarizing and Understanding datasets to 
uncover patterns, trends, relationships and potential issues before applying modeling techniques.

This projects demonstrates how to perform EDA using python and popular data analysis linries such as Pandas, seaborn, Matplotlib and and numpy.

Pandas - data manipulations, 
Numpy - numerical operations, 
Matplotlib - basic data visualization, 
Seaborn - advanced statistical visualization, 
Jupyter notebook - interactive analysis. 

Data Loading
import pandas as pd

df = pd.read_csv("dataset.csv)

Key EDA Steps
1.Understanding the Data
  -dataset shape, 
  -Column names and data types,  
  -Summary statistics. 
df.info() 
df.nunique() 
df.descride() 

2.Data Cleaning 
  -Handling missing values, 
  -Removing duplicates, 
  -Correcting data types, 
df.isnull().sum() 
df.drop_duplicates(inplace-True) 

3.Univariate analysis 
   -Distribution of individual variables, 
   -Hstograms and boxplots, 
  import seaborn as sns  
  sns.histplot(df['col_name'], kind=True) 

4.Bivariate & Multivariate Analysis
  -Correlation analysis,  
  -Pair plots, 
  -Heatmaps, 
sns.heatmap(df.corr(numeric_only=True), annot=True) 

5.Outlier Detection
  -Boxplots, 
  -IQR method, 
sns.boxplot9x=df['columns_name'] 

6.Data visualization Examples
  -Bar charts, 
  -Line charts, 
  -Scatter plots, 
  -heatmaps, 
import matplotlib.pylot as plt
plt.scatter(df['x'], df['y']),  
plt.xlabel("x"), 
plt.ylabel("y"), 
plt.show() 
  
