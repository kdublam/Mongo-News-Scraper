# Mongo-News-Scraper


### Overview
This app scrapes the Manchester United team page from BBC Sport for the latest news/articles. The app will store these new articles on a MongoDB database and allow users to save and leave a comment/note on individual articles.

You can check out the here
[Live Demo](https://reddevils-news-scraper.herokuapp.com/articles)!

### Screenshots
<img src="https://github.com/kdublam/Mongo-News-Scraper/blob/master/public/assets/img/home.png" width="400"/><img src="https://github.com/kdublam/Mongo-News-Scraper/blob/master/public/assets/img/saved.png" width="400"/>

#### Mobile page
<img src="https://github.com/kdublam/Mongo-News-Scraper/blob/master/public/assets/img/mobile.png" width="400"/>


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development. I will assume that you already have [Node.js](https://nodejs.org/en/) and [MongoDB](https://www.mongodb.com/) installed locally. See deployment for notes on how to deploy the project on a live system.

1. Install dependencies
2. In your CLI, enter **mongod**
3. In a new CLI window, go to root of directory and enter **node server.js**
4. In browser, navigate to **http://localhost:3000**

### Dependencies

You will need to npm install the following node modules:

1. express
2. express-handlebars
3. mongoose
4. cheerio
5. axios
6. morgan 

Since I have included a package.json file, you do not need to install dependencies by name. Simply run the following in the root of your directory:

```
npm install
```

## Deployment

Follow these instructions to deploy your app live on Heroku

Create a heroku app in your project directory
```
heroku create <projectName>
```

Provision mLab MongoDB add-on for your project
```
heroku addons:create mongolab
```

