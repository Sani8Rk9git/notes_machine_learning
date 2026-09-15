**FETCHING DATA FROM THE API**



\-> API --> Application Programming Interface

&#x09;-> API are data pipelines that make the information travel from one point to another

&#x09;-> API provide communication between two software components



\-> when we hit an api, we get data



import pandas as pd

import requests



response = requests.get("url")

&#x09;-> python using the requests library do a HTTP request to the url



response.json()

&#x09;-> convert the response to json format

&#x09;-> show the complete dictionary



var\_name = response.json()\["key"]

&#x09;-> get the particular key of the json



pd.DataFrame(var\_name)

&#x09;-> convert the json into DataFrame





<dataframe>.to\_csv("<name\_the\_file>")

&#x09;-> convert the dataframe into file.csv













