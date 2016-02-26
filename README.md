# rest-api
REST API using Expressjs, mongoSkin, mocha and Travis CI :)


Steps 

Assuming we already have Node.js, NPM and MongoDB installed, let’s create a new folder

$ mkdir rest-api
$ cd rest-api


We’ll use Mocha, Expect.js and Super Agent libraries. To install them run these command from the project folder:

$ npm install mocha --save-dev
$ npm install expect.js --save-dev 
$ npm install superagent --save-dev

Now let’s create express.test.js file in the same folder which will have six suites:

  1.  Creating a new object
  2.  Retrieving an object by its ID
  3.  Retrieving the whole collection
  4.  Updating an object by its ID
  5.  Checking an updated object by its ID
  6.  Removing an object by its ID



$ npm install express --save
$ npm install mongoskin --save
npm install body-parser --save


run this in your terminal:
$ node express.js

And in a different window (without closing the first one):
$ mocha express.test.js





