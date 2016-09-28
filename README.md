# Ghostdriver

## Queue your phantomjs child processes from node.

## Choose either series or pooled workers

## Map urls for a given casperjs script using a pool and return the output of workers to an object

Waiting for a response from a servers is usually the limiting factor when it comes to scraping speed. This is especially the case when you want to scrape data from many different sites at once.

Ghostdriver launches a given phantomjs scraping script for a given range of urls in parallel/pooled or in series. A pool of child processes are spawned for each url for the given casperjs script.
