# OpenTable Reviews Collection with Web Scraping for Machine Learning
Collect OpenTable reviews with Web Scraping

## About the script
This repo provides the python script to scrape OpenTable reviews.  
There are 4 user ratings in each review, the main script will get all the reviews and corresponding overall rating from the target restaurants.  
Sample format:

```python
                                                  review  overall rating
0      Great ambiance and service. Lots of menu choic...               3
1      Exceptional service, cuisine, ambience.  Windo...               4
2      Our server Darcy was wonderful!  She accommoda...               2
3      Great food choices for lunch and excellent ser...               3
4      Always reliable and great place to go for lunc...               4
...                                                  ...             ...
13438  Our first visit to Chophouse. We will not go b...               3
13439  Friendly and attentive service and the food an...               4
13440  My family and I had an amazing time! Not only ...               4
13441                                         Great food               4
13442  Great food and excellent service. We’ll be back!!               4
```

## Usage
1. Find the target restaurant website in OpenTable, go to page 2 of review page.
2. Copy the url of review page 2, e.g. https://www.opentable.ca/r/chez-mal-manchester?page=2&sortBy=newestReview
3. Place the urls in url_list for training dataset and eval_url for validation dataset.
4. Run the main script, it will save the df as csv with two columns: reviews and overall rating of the restaurants.  
