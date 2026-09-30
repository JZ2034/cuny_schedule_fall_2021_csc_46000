# CUNY Fall 2021 Academic Calendar Scraper

## What is this project?

This project uses Python to scrape the CUNY City College Fall 2021 academic calendar from the CCNY Registrar website.

The goal is to take the calendar information from the webpage and turn it into a clean pandas DataFrame that can be easily searched, filtered, and analyzed.

The project uses three main Python libraries:

- `requests` — downloads the webpage
- `BeautifulSoup` — reads and extracts information from the HTML
- `pandas` — organizes and cleans the extracted information into a DataFrame

## How the Code Works

### 1. Import the libraries

```python
import requests
from bs4 import BeautifulSoup
import pandas as pd
