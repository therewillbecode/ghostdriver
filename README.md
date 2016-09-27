# multiscraper

##  Parallel asynchronous web scraping for casperjs using child processes.

Waiting for a response from a servers is usually the limiting factor when it comes to scraping speed. This is especially the case when you want to scrape data from many different sites at once.

Multiscraper launches a given casperjs scraping script for a given range of urls in parallel. An array of child processes are spawned for each url.
