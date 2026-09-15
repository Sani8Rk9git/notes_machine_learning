**FETCHING DATA FROM WEB SCRAPING**



\-> we the website is not providing api for getting the data, web scraping is the only way

\-> web scraping means extracting data from the website



\-> 

import pandas as pd

import requests

from bs4 import BeautifulSoup



headers = {"User-Agent": "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 Chrome/131.0.0.0 Safari/537.36"}

response = requests.get("website", headers=headers, timeout=10)



print(response.status\_code)

print(response.text)



\-> beautifulSoup let you get to the html structure of the website and extract the required information





