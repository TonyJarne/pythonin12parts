# Part 4: Scraping

This folder contains notebooks related to scraping in Python:

* The [first notebook](https://github.com/paulbradshaw/pythonin12parts/blob/main/part4/07scrapingBS.ipynb) outlines how to use `requests` and `BeautifulSoup` to scrape a webpage, as well as how to store and export the resulting information using `pandas`
* The [second notebook](https://github.com/paulbradshaw/pythonin12parts/blob/main/part4/08createFunctionsScraperBS.ipynb) outlines how to scrape multiple pages by **defining a scraper function** and applying that to a list of URLs

## Example scrapers

* You'll also find a [scraper for reports on the IOPC website](https://github.com/paulbradshaw/pythonin12parts/blob/main/part4/scraperIOPC_reportsBS.ipynb) which includes a whole range of other techniques
* [This example scraper](https://github.com/paulbradshaw/pythonin12parts/blob/main/part4/anExampleScraper1page.ipynb) grabs data from a music chart; it is then extended in a [second scraper](https://github.com/paulbradshaw/pythonin12parts/blob/main/part4/anExampleScraperNextPage.ipynb) showing how to grab links to the 'next page' and scrape that next page, as well as others by using a loop
* [This example scraper](https://github.com/paulbradshaw/pythonin12parts/blob/main/part4/anExampleScraperList.ipynb) grabs data from a go-karting website; it is then extended in a [second scraper](https://github.com/paulbradshaw/pythonin12parts/blob/main/part4/anExampleScraperList_multipleItems.ipynb)
