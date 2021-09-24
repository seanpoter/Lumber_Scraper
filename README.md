Dimensional Lumber Scraper

One of the most startling side-effects of the Covid-19 pandemic has been the sharp increase in building materials. Dimensional lumber (standard '2x4's and the like) saw increases of over 400% in some regions. For fellow small business operators in the carpentry / cabinetmaking space it is essential to understand and monitor the volatility of these fundamental materials.

The objective of this workbook is to create a web scraper that gathers Dimensional Lumber product data from major retailers Home Depot and Lowes. The end product is a merged csv file, timestamped by date. A follow-up project to this will utilize these outputs to provide immediate price comparisons and analyze price volatility over time from a local retail level.

For use: 
Ensure all packages are installed, and chromedriver is downloaded & accessible in the working directory of the python file. If not using Chrome browser, will need to update selenium code & webdriver. Csv output is set to output in "Output" folder. 

Necessary Packages: 
- import requests
- from bs4 import BeautifulSoup
- import re
- import json
- import pandas as pd
- import datetime as dt
- from selenium.webdriver import Chrome
- import os
