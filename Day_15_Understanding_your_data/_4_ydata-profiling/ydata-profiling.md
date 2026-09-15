**ydata-profiling**



\-> is a popular open-source Python library that automates exploratory data analysis by generating comprehensive, interactive HTML reports from a pandas DataFrame.



\-> !pip install ydata-profiling





\-> import pandas as pd

from ydata\_profiling import ProfileReport



df = pd.read\_csv("your\_data.csv")

profile = ProfileReport(df, title="Dataset Report")

profile.to\_file("report.html")



\-> a html file will be created that store all the analysis of the dataset









