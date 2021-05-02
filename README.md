## Scraping Horsezone and Horse Deals horse ads

This is just a project I devised mainly to explore the capabilities of scrapy. However, I did find that I had to go back to using Selenium for part of it as one of my websites used Javascript and at the time I couldn't devote the resources to learning scrapy-splash. It consists of four spiders (two for each website - one to scrape the searchpage data and the second to follow the links into the ads themselves), an items file for the scrapy spiders, and various scripts used to clean the data and perform some initial EDA.

