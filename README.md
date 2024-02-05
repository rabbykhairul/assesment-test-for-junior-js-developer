  
# Junior JavaScript Developer assesment test
Hi, there! In this test you need to create a simple web app that integrates with a third-party API specifically `NewYork Times API`. You'll show list of popular books and posts fetched from the API. 

### Setup guide

> To get started you need to create a developer account and setup an app in your `nytimes developer account`.  Please visit [this link](https://developer.nytimes.com/get-started) to `create a developer account` .

 1. After signing up, create a [*new app*](https://developer.nytimes.com/my-apps)
 2. Give your app a name & description
 3. From the **APIs** section kindly **`enable`** the following APIs
	  - *Books API*
	  - *Most Popular API*
4. Now save the app
5. Find the `api key & secret` for the app you just created and keep note of it. You'll need this to authenitcate to *nytimes api server*. 

### API documentation
Go through the following API docs to get an idea of the API's call structure and response. Play around with the integrated sandbox if you like.

 - [Most popular articles sent in email](https://developer.nytimes.com/docs/most-popular-product/1/routes/emailed/%7Bperiod%7D.json/get)
 - [Most shared articles in social media](https://developer.nytimes.com/docs/most-popular-product/1/routes/shared/%7Bperiod%7D.json/get)
 - [Best sellers book list](https://developer.nytimes.com/docs/books-product/1/routes/lists/%7Bdate%7D/%7Blist%7D.json/get)

### Deliverable

> You need to submit a web app that meets the following criterias

 - An web-app based on `React.js`
 - A navigation menu with *2 items* `(Articles, Books)`
 - In the `articles` page there should be 2 tabs for (most popular articles, most shared articles)
 - Based on the *selected tab*, query the API and show the list of articles in a table with some basic info
 - In the `books` page, show the the list of bestsellers book for `today` in a table. You need to show the image, title, author, amazon product url, price of each book.
 - A public Github repository with all the codes and a readme file with instructions on how to run the app locally.
 - Bonus points
	- Add a `date filter` in the `books page` and let user select a specific date for the bestseller books list and update data accordingly.
	- Add a `search` by title option in the `articles` page. No need to query the API for this, just implement search in the list data available to you from the API response.
	- `Deploy` the app to a free hosting like (Netlify, Vercel) for `live demo`
