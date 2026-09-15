**WORKING WITH CSV FILES**



\-> csv => comma separated values

&#x09;-> the values in each row are separated by commas



\-> tsv => tab separated values

&#x09;-> the values in each row are separated by tab



\-> open a local csv file

\-> load csv file from GitHub(url)



\-> the pd.read\_csv() has a parameter sep

&#x09;-> by default it is sep = ","

&#x09;-> so read\_csv() function works fine with csv files



\-> to read tsv files

&#x09;-> write sep = "\\t" in the read\_csv() function



\-> now if we do not have column names

&#x09;-> read\_csv() has a parameter names=\[]

&#x09;-> write the names of the column yourself

&#x09;-> the names will be assigned to columns



\-> if we want to convert a column into index

&#x09;-> read\_csv() has a parameter index\_col=""

&#x09;-> give the column name



\-> if we want to make the first row as the header

&#x09;-> read\_csv() has a parameter header=1



\-> if we want only some specific columns from the data

&#x09;-> read\_csv() has a parameter usecols=\[""]

&#x09;-> list down the names of the columns that you want



\-> if we want to skip some rows

&#x09;-> read\_csv() has a parameter skiprows=\[]

&#x09;-> give the row numbers



\-> to import only some number of rows

&#x09;-> read\_csv() has a parameter nrows= <value>

&#x09;->



\-> if the dataset has not encoding UTF-8

&#x09;-> read\_csv() has a parameter encoding=""

&#x09;-> give the name of the encoding that the file currently has

&#x09;-> the file then appears



\-> if there are rows in the data that has more values than number of columns

&#x09;-> this causes parser error

&#x09;-> read\_csv() has a parameter error\_bad\_lines=False

&#x09;-> so those rows are skipped



\-> read\_csv().info()

&#x09;-> gives the information about the columns



\-> we can change the datatype of the values of the column

&#x09;-> read\_csv() has an attribute dtype={"col\_name" : int/float}



\-> when a dataset containing dates is loaded from read\_csv(), dates are considered as strings

&#x09;-> to convert them into dates

&#x09;	-> read\_csv() has a parameter parse\_dates=\["col\_name"]

&#x09;	-> the col\_name is the name of the date column

&#x09;	-> now we can apply filter over these dates





\-> converters are used to perform transformations in the columns

&#x09;-> we have created a function and we want to use that to transform values of

&#x09;	a column

&#x09;-> read\_csv() has a parameter converters={"col\_name":<function\_name>}

&#x09;->



\-> we can specify which values to consider NaN

&#x09;-> read\_csv() has a parameter na\_values=\["val1" , "val2",...]



\-> if we have lots of rows in the data, we can divide them into chunks

&#x09;-> read\_csv() has a parameter chunksize = <number>

&#x09;-> for chunk in <var\_name>:

&#x09;	-> use loops to access chunks

&#x09;->

