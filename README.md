# OpenTable Reviews Collection with Web Scraping for Machine Learning
Collect OpenTable reviews with Web Scraping

## About the script
This repo provides the python script to scrape OpenTable reviews.  
It will get all the reviews and corresponding overall rating from the target restaurants.  

## Usage
1. Find the target restaurant website in OpenTable, go to page 2 of review page.
2. Copy the url of review page 2, e.g. https://www.opentable.ca/r/chez-mal-manchester?page=2&sortBy=newestReview
3. Place the urls in url_list for training dataset and eval_url for validation dataset.
4. Run the main script, it will save the df as csv with two columns: reviews and overall rating of the restaurants.  
