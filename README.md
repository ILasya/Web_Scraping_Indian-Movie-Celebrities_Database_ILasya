# Data and Image Scraping the IMDB website using Python BeautifulSoup 

Data scraping, also known as web scraping, is the process of extracting information from a website and converting this information into
a Database. It’s one of the most efficient ways to get data from the web. 
Web Scraping can also be used to scrap Images in the given Website.

# BeautifulSoup

Beautiful Soup is a Python library for parsing HTML and XML documents. It is a library that makes it easy to scrape information from web pages.We will be using this library to scrap Data and Images from the IMDB website.

# Required Modules

import pandas as pd

import re

import lxml

from PIL import Image

from io import BytesIO

import os

import webbrowser

from bs4 import BeautifulSoup

from requests import get

# Data and Image Scraping the "TOP 200 Best Indian Celebrities Of India" website of IMDb

1. importing all the necessary libraries

2. To go to the IMDB website. Click on this link: https://www.imdb.com/list/ls068010962/

![image](https://user-images.githubusercontent.com/54140890/80499110-2fe12d80-898a-11ea-9c59-3ff71607dfb3.png)

3. Now, Right click anywhere on the screen and select 'Inspect' 

![image](https://user-images.githubusercontent.com/54140890/80498910-eb559200-8989-11ea-9b00-82536c499a78.png)

4. Find the Elements that correspond to the data we're getting.

![image](https://user-images.githubusercontent.com/54140890/80499002-0f18d800-898a-11ea-95f4-d93d9f736973.png)

5. Make a note of the TAGS as well as the Attributes like class, id, etc. We'll use that later.

6. Then follow the Indian_Movie_Celebrities_Database_Generator.ipynb file available in this repository. A detailed expalaniton of the      code is explained in the .ipynb file

7. After running the .ipynb file, the gennerated DataFrame containing information of 200 celebrities is displayed as a table 
   in a .html website as shown below:

![image](https://user-images.githubusercontent.com/54140890/80499673-e80ed600-898a-11ea-8e8b-f79d2898c914.png)


# Uploaded Files Information

1. Indian_Movie_Celebrities_Database_Generator.ipynb - The Python file containing the code for Data and Image Scraping

2. Images/ (Folder) - This folder consists of all the images Scraped from the IMDB website

3. Top 200 Best Indian Actors and Actresses.html - The .html file created after running the .ipynb file.

