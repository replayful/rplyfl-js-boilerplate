# rplyfl-js-boilerplate

## A simple and bare-bones boilerplate to kick start HTML/JS/CSS projects/experiments/whatever with some decent defaults and no webpack insane configs to mess with ;)

- using parcel to serve and bundle prod build
- JS linting via eslint
- CSS linting via stylelint
- postcss for css (few plugins added)
- normalize.css to reset and some basic css included
- .browserslistrc (used by postcss, run $ npx browserslist)
- parcel supports .env files for loading enviroment variables 
- build command runs by default some minifiers built-in parcel for html, js and css
- uses yarn to manage dependencies
- add the JS framework of your choice on top, or not.

## TODO
- Styles need work, just basic structure in place

## to run local server
$ npm start

## to build to dist folder a production version
$ npm build