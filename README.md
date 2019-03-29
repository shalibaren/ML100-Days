* ## **`Machine Learning 100-Days`**

   Data Cleansing, Feature Engineering, Machine Learning, Deep Learning hands on practice.

***
#### HW005: EDA
- Functions Used
  - .value_counts()
  - .value_counts().plot.bar()
  - scatter_matrix
  - .plot()
  - .hist()
  - app_train.select_dtypes(include=["object"]).apply(pd.Series.nunique, axis = 0)
  - plt.xticks
- Discription
  - Plot many variables by histogram
  - See how many unique value in all columns
- Link
  - Discriptive Statistics: http://www.hmwu.idv.tw/web/R_AI_M/AI-M1-hmwu_R_Stat&Prob.pdf
  - Discriptive Pandas: https://chrisalbon.com/python/data_wrangling/pandas_dataframe_descriptive_stats/
  - EDA with pandas: https://ppt.cc/ffpuCx
***
#### HW006: Outliers Detection
- Functions Used
  - np.log
  - plt.plot
- Discription
  - Display boxplot of various columns
  - Change plot to log-scale
  - Compare ECDF of model and data
- Link
  - ECDF: https://zh.wikipedia.org/wiki/%E7%BB%8F%E9%AA%8C%E5%88%86%E5%B8%83%E5%87%BD%E6%95%B0
***
#### HW007: Handle Outliers
- Functions Used
  - np.percentile
  
- Discription
  - Calculate percentile of data
  - Fill NA data with specific value
  - Print the most duplicate value
***
#### HW008: Dataframe Operation
- Functions Used
  - pd.cut
  - Groupby
  
- Discription
  - To count the amount after distributed into different categories
  - Observe Specific columns after groupby one or more columns
***
#### HW009: Correlation
- Functions Used
  - np.random.randint
  - np.random.normal
  - np.corrcoef
  - plt.scatter
- Discription
  - Generate random integer
  - Generate Gaussian random variable
  - Show Correlation coefficient Matrix
  - Draw scatter plot
- Link
  - Correlation coefficient: http://www.statstutor.ac.uk/resources/uploaded/pearsons.pdf
***
#### HW010: Supplementary correlation and plot with different range
- Functions Used
  - pd.cut
  - Groupby
  
- Discription
  - To count the amount after distributed into different categories
  - Observe Specific columns after groupby one or more columns
***
