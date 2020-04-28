# Data and Image Scraping the IMDB website using Python BeautifulSoup 

Data scraping, also known as web scraping, is the process of extracting information from a website and converting this information into
a Database. It’s one of the most efficient ways to get data from the web. 
Web Scraping can also be used to scrape Images in the given Website.

# BeautifulSoup

Beautiful Soup is a Python library for parsing HTML and XML documents. It is a library that makes it easy to scrape information from web pages. We will be using this library to scrape Data and Images from the IMDB website.

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

1. Import all necessary libraries.

2. To go to the IMDB website, click on this link: https://www.imdb.com/list/ls068010962/

![image](https://user-images.githubusercontent.com/54140890/80506412-2a3c1580-8993-11ea-8ac0-2d9e9bfc1585.png)

3. Now, Right click anywhere on the screen and select 'Inspect' .

![image](https://user-images.githubusercontent.com/54140890/80506426-30ca8d00-8993-11ea-8725-23dc13c1aa0f.png)

4. Find the Elements that correspond to the data we're getting.

![image](https://user-images.githubusercontent.com/54140890/80506602-725b3800-8993-11ea-9341-2e07aba329a5.png)

5. Make a note of the TAGS as well as the Attributes like class, id, etc. We'll use that later.

6. Then follow the Indian_Movie_Celebrities_Database_Generator.ipynb file available in this repository. A detailed explanation of the      code is provided in the .ipynb file.

7. After running the .ipynb file, the generated DataFrame containing information of 200 celebrities is displayed as a table 
   in a browser as shown below:
   From celebrity 1

![image](https://user-images.githubusercontent.com/54140890/80506713-9880d800-8993-11ea-8b9e-19f268409297.png)

   Right until the 200th Celebrity!!!
   
![image](https://user-images.githubusercontent.com/54140890/80506763-a6365d80-8993-11ea-84cd-8b67c1c1c81c.png)


# Uploaded Files Information

1. Indian_Movie_Celebrities_Database_Generator.ipynb - The Python file containing the code for Data and Image Scraping.

2. Images/ (Folder) - This folder consists of all the images Scraped from the IMDB website.

3. Top 200 Best Indian Actors and Actresses.html - The .html file created after running the .ipynb file.

