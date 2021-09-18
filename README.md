# Yellowpages-Scraper
## Disclaimer
I built this notebook for personal use only. Please check the terms of service of any website before you attempt scraping its data with such a script!
## Description
Small notebook on how to get entries from German yellowpages www.gelbeseiten.de into nice tabular format. I built it to feed a crm-system for my masters thesis for which I had to get in touch with many local businesses from specific private service industries.

## Running the notebook
Before running the notebook, you must install a few packages. Namely:
* BeautifulSoup4 (bs4)
* selenium
* pandas

Additionally, you must define the path to your chromedriver. If not already installed, you can get it from https://chromedriver.chromium.org/downloads

You can then set the mandatory variables "searchterm" and "region" as well as the optional filter "search_distance". 
