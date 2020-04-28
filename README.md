# Data and Image Scraping the IMDB website using Python BeautifulSoup 
Data scraping, also known as web scraping, is the process of extracting information from a website and converting this information into
a Database. It’s one of the most efficient ways to get data from the web. 
Web Scraping can also be used to scrap Images in t given Website.

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

# Data and Image Scraping the TOP 200 Best Indian Celebrities Of India in IMDb

