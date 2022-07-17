# Covid-19-Data-Analytics-Project
I have taken a small dataset of covid 19 just for understanding purpose. We have to work on original datset which contains 19000 rows.  The data used here is till 29-April-2021 &amp; has record as on 29-April-2021.  The data available as a csv file, downloaded from Kaggle. I will analyze this dataset using Pandas Dataframe.  Here, random sets of questions and instructions are given as an example for the practice &amp; learning purpose.



---------------------------------------------------------------------------------
In this project, a tiny data set related to the Covid-19 pandemic is taken and analyzed in a very Easy To Understand (ETU) language.
Here, you will learn how to work on a real project of Data Analysis with Python. 


Questions are given in the project and then solved with the help of Python. 

Q. 1) Show the number of Confirmed, Deaths and Recovered cases in each Region.


Q. 2) Remove all the records where the Confirmed Cases is Less Than 10.


Q. 3) In which Region, maximum number of Confirmed cases were recorded ?


Q. 4) In which Region, minimum number of Deaths cases were recorded ?


Q. 5) How many Confirmed, Deaths & Recovered cases were reported from India till 29 April 2020 ?

Q.Visualization Of Data

Q. 7-A ) Sort the entire data wrt No. of Confirmed cases in Ascending order.


Q. 7-B ) Sort the entire data wrt No. of Recovered cases in Descending order.

Q. 7-C) Sort the entire data wrt No. of Recovered cases in Descending order.



-----------------------------------------------------------------------

The commands that we used in this project :

* import pandas as pd -- To import Pandas library
* pd.read_csv - To import the CSV file in Jupyter notebook
* df.count() - It counts the no. of non-null values of each column.
* df.isnull().sum() - It detects the missing values from the dataframe.
* import seaborn as sns - To import the Seaborn library.
* import matplotlib.pyplot as plt - To import the Matplotlib library.
* sns.heatmap(df.isnull()) - It will show the all columns & missing values in them in heat map form.
* plt.show() - To show the plot.
* df.groupby(‘Col_name’) - To form groups of all unique values of the column.
* df.sort_values(by= ['Col_name'] ) - Sort the entire dataframe by the values of the given column.     
* df[df.Col_1 = = ‘Element1’] - Filtering – We are accessing all records with Element1 only of Col_1.
* df.plot(x='column1',y='column2',kind='scatter')

------------------------------------------------------

