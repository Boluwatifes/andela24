### Andela News 24

[![Code Climate](https://codeclimate.com/github/Boluwatifes/andela24/badges/gpa.svg)](https://codeclimate.com/github/Boluwatifes/andela24)
[![Coverage Status](https://coveralls.io/repos/github/Boluwatifes/andela24/badge.svg?branch=master)](https://coveralls.io/github/Boluwatifes/andela24?branch=master)
[![Issue Count](https://codeclimate.com/github/Boluwatifes/andela24/badges/issue_count.svg)](https://codeclimate.com/github/Boluwatifes/andela24)
[![Build Status](https://travis-ci.org/Boluwatifes/andela24.svg?branch=master)](https://travis-ci.org/Boluwatifes/andela24)

## Introduction
*  **`Andela24`** is a React Powered News Feed App.
*  It has the following features;
  *  Login via Google
  *  Allows users to select news sources
  *  Allows users to sort news article based on the sorting parameter available
  *  Sorting can either be by -
    *  Top
    *  Latest
    *  Popular
  *  Allows users to save favorite news 
  *  Allows users to share interesting news on social media
*  A demo of the app can be access on heroku via [here](https://andela24.herokuapp.com)

## Dependencies

### Development Dependencies
*  The following depencies are required by the app during developmment
  *  **[Babel-register](https://www.npmjs.com/package/babel-register)** - This framework helps to compile from es6 to es5
  *  **[css-loader](https://www.npmjs.com/package/css-loader)** - The  css-loader is used with webpack and it interprets @import and url() like import/require()
  *  **[enzyme](https://www.npmjs.com/package/enzyme)** - Enzyme is used together with mocha, chai and expect.js to test this application
  *  **[eslint](https://www.npmjs.com/package/eslint)** - This is a javascript syntax highlighter used to highligh syntax error during the development of this app
  *  **[eslint-config-airbnb](https://www.npmjs.com/package/eslint-config-airbnb)**, **[eslint-plugin-import](https://www.npmjs.com/package/eslint-plugin-import)**, **[eslint-plugin-jsx-a11y](https://www.npmjs.com/package/eslint-plugin-jsx-a11y)**, **[eslint-plugin-react](https://www.npmjs.com/package/eslint-plugin-react)**  - These are ESlint packages containing all of eslint rules and they are used in this application to define rules and highligh errors
  *  **[extract-text-webpack-plugin](https://www.npmjs.com/package/extract-text-webpack-plugin)** - It's used to move all the css imported into the application into a separate file.
  *  **[file-loader](https://www.npmjs.com/package/file-loader)** - It enables the app to load files directly into scripts
  *  **[jsdom](https://www.npmjs.com/package/jsdom)**, **[jsdom-global](https://www.npmjs.com/package/jsdom-global)**, **[mocha-jsdom](https://www.npmjs.com/package/mocha-jsdom)**, **[mock-local-storage](https://www.npmjs.com/package/mock-local-storage)** - Used to emulate web browser during application testing
  *  **[node-sass](https://www.npmjs.com/package/node-sass)**, **[sass-loader](https://www.npmjs.com/package/sass-loader)** - This enables the app to use sass (.scss) directly in scripts
  *  **[nyc](https://www.npmjs.com/package/nyc)** - Used with mocha for test coverage report
  *  **[sinon](https://www.npmjs.com/package/sinon)** - Used with mocha and enzyme for mocking React components during test
  *  **[url-loader](https://www.npmjs.com/package/url-loader)** - It enables the app to use background images in the scss files
  *  **[webpack-dev-middleware](https://www.npmjs.com/package/webpack-dev-middleware)** - Serves files to server during development
  *  **[webpack-hot-middleware](https://www.npmjs.com/package/webpack-hot-middleware)** - It enables the browser to reload automatically when changes are made to the app

### Dependencies
*  **[axios](https://www.npmjs.com/package/axios)** - Used to make GET requests to external API's
*  **[babel-cli](https://www.npmjs.com/package/babel-cli)** - It enables the app scripts to be tested with babel from the command line
*  **[babel-core](https://www.npmjs.com/package/babel-core)** - It compiles es6 used in the app to es5
*  **[babel-eslint](https://www.npmjs.com/package/babel-eslint)** - Used with ESlint to lint syntax errors
*  **[babel-loader](https://www.npmjs.com/package/babel-loader)** - Used with Webpack to transpile javascript codes
*  **[babel-plugin-react-html-attrs](https://www.npmjs.com/package/babel-plugin-react-html-attrs)** - It help convert JSX `class` attribute into `className` 
*  **[coveralls](https://www.npmjs.com/package/coveralls)** - Display test coverage
*  **[express](https://www.npmjs.com/package/express)** - Used as the web server for this application
*  **[extract-text-webpack-plugin](https://www.npmjs.com/package/extract-text-webpack-plugin)** - Moves the app's css into a separate file
*  **[flux](https://www.npmjs.com/package/flux)** - It enables the app to implement the flux architecture
*  **[history](https://www.npmjs.com/package/history)** - Allows the app to implement history in routes.
*  **[json-loader](https://www.npmjs.com/package/json-loader)** - Enables the app to inport json files.
*  **[lodash](https://www.npmjs.com/package/lodash)** - Used to perform filter on objects
*  **[node-localstorage](https://www.npmjs.com/package/node-localstorage)** - Used to mock localStorage during testing
*  **[react](https://www.npmjs.com/package/react)** - It enables the app to use the React architecture
*  **[react](https://www.npmjs.com/package/react)** - Used with **[react-dom](https://www.npmjs.com/package/react-dom)** enables the app to use the React architecture
*  **[react-google-login](https://www.npmjs.com/package/react-google-login)** - Enables authentication with Google
*  **[react-router-dom](https://www.npmjs.com/package/react-router-dom)** - Used to perform app routing
*  **[webpack](https://www.npmjs.com/package/react-router-dom)** - Used to bundle the app's js and scss files for usage in the browser
*  **[webpack-dev-server](https://www.npmjs.com/package/webpack-dev-server)** - Serves as the server during development

## Front End Dependencies
*  **[Materialize CSS](http://materializecss.com/)** - All part of the app was styled with this css framework.
*  **[Material Icons](https://material.io/icons/)** - Iconic font provided by Google.

## Installation and setup
*  Navigate to a directory of choice on `terminal`.
*  Clone this repository on that directory.
  *  Using SSH;

    >`git clone git@github.com:Boluwatifes/andela24.git`

  *  Using HTTP;

    >`git clone https://github.com/Boluwatifes/andela24.git`

*  Navigate to the repo's folder on your computer
  *  `cd andela24/`
*  Install the app's dependencied
  *  `npm install`
* Run the app
  *  `npm start`

## Tests
*  The tests have been written using Mocha and Enzyme.
*  They are run using the **`coverage`** tool in order to generate test coverage reports.
*  To run the tests, navigate to the project's root folder
*  Run the following commands.
  *  `npm test`