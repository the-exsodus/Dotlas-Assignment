# Dotlas-Assignment
This is a web scraping assignment using selenium to get the html and beautiful soup to parse through the html.

So a couple of things, I had to use Selenium instead of requests since a llot of the html was not being scraped due to the dynamic nature of the request. So my options were to use Talabat's API or Selenium, and Selenium seemed to be the easier option.

Second, in the menu item list, I had to take the price of items as strings since there were a few outlets where the price wasn't listed and instead was given as "Price on selection", so to accomodate this I took the price as a string.

Also to load all the images for the menu items, pls scroll through the page after it is loaded on chrome to send the request for the images, else the default placeholder image link will be scraped.
