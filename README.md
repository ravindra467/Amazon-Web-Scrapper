# Amazon Web Scraper
This is a web scraping API that uses Express and Request-Promise to scrape data from Amazon's website. The API allows you to retrieve product details, reviews, offers and search results by making GET requests to different endpoints. The API uses ScraperAPI as a proxy to avoid IP blocking and CAPTCHAs.

## Features
- Retrieve product details by product ID
- Retrieve product reviews by product ID
- Retrieve product offers by product ID
- Retrieve search results by search query
- Uses ScraperAPI as a proxy to avoid IP blocking and CAPTCHAs

## Usage
- Sign up for a ScraperAPI account and obtain an API key
- Clone the repository - `$ git clone https://github.com/[username]/amazon-web-scraper.git`
- Install the dependencies - `$ npm install`
- Replace apiKey with your ScraperAPI key in index.js
- Run the application - `$ npm start`
- Make GET requests to the following endpoints:
- `/products/:productId` to retrieve product details
- `/products/:productId/reviews` to retrieve product reviews
- `/products/:productId/offers` to retrieve product offers
- `/search/:searchQuery` to retrieve search results

## Dependencies
- Node.js
- Express
- Request-Promise
- ScraperAPI

- To get this API up and running, you'll need to first sign up for a ScraperAPI account, obtain an API key and then use it to replace apiKey in index.js file. Then you can run the application using npm start command and make GET requests to the different endpoints to retrieve the data you need.
- It's important to note that web scraping can be against the terms of service of some websites, so please ensure that you are in compliance with the terms of service of the website you are scraping and also use proxy service like ScraperAPI to avoid IP blocking and CAPTCHAs.

## Contributions  
You can also contribute to the project by forking the repository and submit pull requests.




