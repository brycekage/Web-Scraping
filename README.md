# eBay Item Listing Scraper

## General Function:

The file ebay-dl.py contains code that scrapes ebay for data on listed items of your choosing

ebay-dl.py then outputs a json file with the each item's name, price, status, shipping cost, etc.

## How to run ebay-dl.py:

First, install the needed packages:
 ```
$ pip3 install requests 
$ pip3 install beautifulsoup4 
$ pip3 install playwright
$ pip3 install ndetected-playwright 
$ pip3 install playwright-stealth
```
Then, install the browser that gets used by playwright:

```
$ playwright install firefox
```

Finally, run the file in the terminal with your search term (NOTE: if your search term has any spaces, put your search term in parenthesis as seen in the last prompt below):

```
$ python3 ebay-dl.py headphones
$ python3 ebay-dl.py lamp
$ python3 ebay-dl.py "jordan 4"
```

## Files in this Repository: 

- ebay-dl.py: the working scraping script
- headphones.json: scraped listing data for headphones
- jordan_4.json: scraped listing data for jordan 4s
- lamp.json: scraped listing data for lamps
- README.MD: this file :)

## Course Project: 

Course project repository: https://github.com/mikeizbicki/cmc-csci040/tree/2026spring/project_02_webscraping