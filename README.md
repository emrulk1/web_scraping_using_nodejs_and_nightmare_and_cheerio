his project is cloned from https://github.com/ankitjain28may/scraping-nodejs for testing purpose.
you can find the step by step tutorial here : https://morioh.com/p/5932527fe756/how-to-perform-web-scraping-using-node-js 

Setup
Our setup is pretty simple. We create a new folder and run this command inside that folder to create a package.json file. Let’s cook the recipe to make our food delicious.

npm init -y
Before we start cooking, let’s collect the ingredients for our recipe. Add Axios and Cheerio from npm as our dependencies.

npm install axios cheerio
Now, require them in our index.js file

const axios = require('axios');
const cheerio = require('cheerio');
