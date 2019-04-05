* ## **`Machine Learning 100-Days`**

   Data Cleansing, Feature Engineering, Machine Learning, Deep Learning hands on practice.

***
#### HW003: Create dataframe, read pics, txt, json, npy, pickle
- Functions Used
  - pd.read_csv
  - .dtypes.value_counts()
  - skio.imread + plt.imshow(img1)
  - Image.open + np.array(img2)
  - cv2.imread + plt.imshow(img3)
  - sio.savemat + plt.imshow(mat_arr)
- Discription
  - Build a dataframe
  - Read pics in three ways
  - Read pics by MAT form
***
#### HW004: Column Data Type
- Functions Used
  - pd.read_csv
  - .dtypes.value_counts()
  - from sklearn.preprocessing import LabelEncoder
  - pd.get_dummies
- Discription
  - Read csv files by pandas
  - Count datatypes of a dataframe
  - Label Encoder and one hot encoder
- Link
  - Label Encoder vs. One Hot Encoder: https://ppt.cc/f1dEhx
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
  - See how many unique value in each column
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
  - np.corrcoef
  - np.log101
- Discription
  - Plot and observe the correlation
***
#### HW011: KDE plot
- Functions Used
  - sns.kdeplot
  - sns.distplot
- Discription
  - KDE plot by seaborn
  - KDE bar mixture plot by seaborn distplot
- Link
  - KDE plot example: https://ppt.cc/fp0wZx
  - KDE plot explain: https://blog.csdn.net/unixtch/article/details/78556499
  - Seaborn barplot example: https://zhuanlan.zhihu.com/p/24553277
***
#### HW012: Discretizing
- Functions Used
  - pd.cut(column_data, 4)
  - pd.qcut(column_data, 4)
- Discription
  - cut data in same range by n
  - cut data in same count by n
***
#### HW013: Discretizing practice
***
#### HW014: Subplots
- Functions Used
  - np.linspace(20, 70, num = 11)
  - plt.subplot(row,column,idx)
  - .value_counts().keys()
- Discription
  - Divide numbers of points in two points 
  - Display many plots at a time 
  - list all unique value in a column
***
#### HW015: Heatmap
- Functions Used
  - sns.heatmap
  - enumerate()
  - sns.PairGrid
- Discription
  - KDE plot by seaborn
  - KDE bar mixture plot by seaborn distplot
  - upper, diag, lowwer plots
- Link
  - Heatmap example: https://zhuanlan.zhihu.com/p/35494575
  - KDE plot explain: https://blog.csdn.net/unixtch/article/details/78556499
  - Seaborn barplot example: https://zhuanlan.zhihu.com/p/24553277
***
#### HW016: Heatmap
- Functions Used
  - .align
  - Imputer, imputer.fit, imputer.transform
  - MinMaxScaler, scaler.fit, scalar.transform
  - .to_csv
- Discription
  - Align the training and testing data, keep only columns present in both dataframes
  - imputation of missing values
  - Scale each feature (e.g from 0 to 1)
  - Save file to csv
***
