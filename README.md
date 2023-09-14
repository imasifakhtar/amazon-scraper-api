 ## Amazon Data Scraper API

This Node.js application provides an API for scraping product data from Amazon.in. The API can be used to get product details, product offers, and search results.

### Prerequisites

To use this API, you will need the following:

* A ScraperAPI account and API key. You can sign up for a free account at https://www.scraperapi.com/.
* Node.js installed on your computer. You can download Node.js from https://nodejs.org/.

### Installation

To install the API, clone the repository and install the dependencies:

```
git clone https://github.com/your-username/amazon-scraper-api.git
cd amazon-scraper-api
npm install
```

### Usage

To start the API, run the following command:

```
npm start
```

The API will be available at http://localhost:5000.

### Endpoints

The API provides the following endpoints:

* `/products/:productId`: Gets the product details for the specified product ID.
* `/products/:productId/offers`: Gets the product offers for the specified product ID.
* `/search/:searchQuery`: Gets the search results for the specified search query.

### Example Usage

To get the product details for the product with the ID `B079876543`, you can make the following request:

```
curl http://localhost:5000/products/B079876543
```

The response will be a JSON object containing the product details.

To get the product offers for the product with the ID `B079876543`, you can make the following request:

```
curl http://localhost:5000/products/B079876543/offers
```

The response will be a JSON object containing the product offers.

To get the search results for the search query `"iPhone 13"`, you can make the following request:

```
curl http://localhost:5000/search/iPhone%2013
```

The response will be a JSON object containing the search results.

### Code Explanation

The code for the API is located in the `index.js` file. The code is well-commented and easy to understand.

The main function of the API is to scrape data from Amazon.in.
