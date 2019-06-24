# Barney's Pricing Webscrape & Analysis
Scraping, analysis and statistical testing of the iconic department store's men's and women's online departments.

## The Scrape
* Scraped several category pages for men's and women's clothing individually using two different functions
* Used Selenium to close pop up out of each category, then handed off actual scraping to Beauitful Soup
* Example function with notes below:
<script src="https://gist.github.com/dlm6693/42d9a1c2af8c2f50f62ff029dde4033a#file-barneys_scrape-py">
</script>

## Data Aggregation
* Approximately 9,000 different items of men's clothing and about 15,000 for women
* Performed basic analysis and visualizations to get a better sense of the data, like most common brands (excluding the retailer's own) and most expensive
![image-0](Images/men_women_common_brands.png)
![image-1](Images/men_women_high_price.png)
* As can be seen above, most common brands mostly showed familiar names while most expensive offered more variety
* What's more revealing is how much higher the top prices for women's were than men's