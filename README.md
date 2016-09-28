# multiscraper

## True parallel web scraping for casperjs using multiple child processes.

Waiting for a response from a servers is usually the limiting factor when it comes to scraping speed. This is especially the case when you want to scrape data from many different sites at once.

Multiscraper launches a given casperjs scraping script for a given range of urls in parallel. A pool of child processes are spawned for each url for the given casperjs script.
