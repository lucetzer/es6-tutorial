## ES6 Tutorial using webpack and babel

View full tutorial [here](http://ccoenraets.github.io/es6-tutorial).

### Setup notes

* build folder contains the final bundled code
* index should refer to the bundled entry code e.g. main.bundle.js
* webpack configures the different tools together
```npm install babel-loader webpack --save-dev```
```npm run webpack```
```npm install webpack-dev-server -g``` //not implemented here but allows us to pass --watch flag so when we run webpack, watch file changes and serve these changes in the browser immediately
* To run ```npm start``` or ```http-server```

* Babel setup:
```npm init```
```npm install babel-cli babel-core --save-dev```
```npm install babel-present-es2015 --save-dev```
```npm install http-server --save-dev```
```npm install babel-polyfill --save```  //runtime helper and helps set up an ES6 like environment
```npm install babel-runtime --save```
```npm install babel-plugin-transform-runtime --save-dev```
To build and run ```npm run babel```
