# Ex-04-Multivariate-Analysis
#DEVELOPED BY:JAYALAKSHMI M
#REGISTER NUMBER:212221040066
# AIM
To detect the Multivariate Analysis by using default functions
# ALGORITHM
1.Import pandas(),numpy()and seaborn() for a required detection.
2.use the head()
3.The information and is null function.
4.Use the describe function.
5.Figure the boxplot.
6.plot the countrplot,Displot,Histoplot.
7.Print the program.
# PROGRAM
import pandas as pd
import numpy as np
import seaborn as sns
data=pd.read_csv('SuperStore.csv')
data
data.head()
data.info()
data.describe()
data.isnull().sum()
data.dtypes
data['Postal Code'].value_counts()
sns.boxplot(x='Postal Code', data=data)
sns.countplot(x='Postal Code',data=data)
sns.distplot(data["Postal Code"])
sns.histplot(x='Postal Code',data=data)
# OUTPUT
![EX-04-MULTIVARIATE-ANALYSIS](ex4(1).png)
![EX-04-MULTIVARIATE-ANALYSIS](ex4(2).png)
![EX-04-MULTIVARIATE-ANALYSIS](ex4(3).png)
![EX-04-MULTIVARIATE-ANALYSIS](ex4(4).png)
![EX-04-MULTIVARIATE-ANALYSIS](ex4(5).png)
![EX-04-MULTIVARIATE-ANALYSIS](ex4(6).png)
![EX-04-MULTIVARIATE-ANALYSIS](ex4(7).png)
![EX-04-MULTIVARIATE-ANALYSIS](ex4(8).png)
![EX-04-MULTIVARIATE-ANALYSIS](ex4(9).png)
![EX-04-MULTIVARIATE-ANALYSIS](ex4(10).png)
![EX-04-MULTIVARIATE-ANALYSIS](ex4(11).png)
# RESULT
Hence the multivariate analyses is verified.