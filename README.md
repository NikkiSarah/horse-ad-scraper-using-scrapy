## Scraping Horsezone and Horse Deals horse ads

This is just a project I devised mainly to explore the capabilities of scrapy. However, I did find that I had to go back to using Selenium for part of it as one of my websites used Javascript and at the time I couldn't devote the resources to learning scrapy-splash. It consists of four spiders (two for each website - one to scrape the searchpage data and the second to follow the links into the ads themselves), an items file for the scrapy spiders, and various scripts used to clean the data and perform some initial EDA that compared the two datasets on elements common to both.

The final scrape was able to pull out 2616 ads from Horse Deals and 494 ads from Horsezone, and included a number of different elements such as the listing price, title or horse name, advert text, what disciplines the horse would be suited for, breed, age and height.



