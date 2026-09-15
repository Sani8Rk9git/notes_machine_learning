**BASIC QUESTIONS TO ASK ABOUT DATA**



\-> Understanding your data means when we get the data, how to analyze it.



Q.1 How big is the data??

&#x09;-> df.shape

&#x09;	-> (rows,columns)



Q.2 How does the data look like??

&#x09;-> df.head()

&#x09;	-> get the first 5 rows of the data

&#x09;-> df.sample(<value>)

&#x09;	-> get <value> random rows from the dataset



Q.3 What is the datatype of the columns??

&#x09;-> df.info()



Q.4 Are there any missing values in the dataset??

&#x09;-> df.isnull().sum()

&#x09;	-> returns the number of missing values in each column as a series



Q.5 How does the data look mathematically??

&#x09;-> df.describe()

&#x09;-> works for numerical columns automatically



Q.6 Are these duplicate values in the data??

&#x09;-> df.duplicated().sum()

&#x09;-> return the number duplicated rows in the data



Q.7 What is the correlation between columns??

&#x09;-> correlation means how increase/decrease in one column affect the other column

&#x09;-> we can identify which input column has no effect on the output column

&#x09;-> df.corr()

&#x09;	-> calculate correlation of all columns with all columns

&#x09;-> to get the correlation of a single column

&#x09;	-> df.corr()\["col"]

&#x09;	-> this will get correlation of this col with all the other columns













