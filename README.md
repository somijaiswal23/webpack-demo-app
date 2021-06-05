# webpack-demo-app

## What is webpack?

* It bundles our code and assets together
* It manages dependencies

## Setup

* Create package.json `npm init -y`
* Install webpack `npm install --save-dev webpack webpack-cli`
* In Package.json add script `"start":"webpack"
  * This will create a dist folder with main.js whenever we run `npm start`
  * main.js will always lookup for index.js as its starting compoenet.

## Webpack Bundle

* Define import and export for dependencies of each component.
* Weback will take care of the rest.
