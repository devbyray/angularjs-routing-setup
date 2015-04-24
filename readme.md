# Angular routing Setup

## Project structure:
- app
    - src
        - js
            - libs
                - angular.min.js
            - app.js
        -sass
            - sass-structure
    - index.html
- gulpfile.js
- package.json
- readme.md

## How to install

1. run `(sudo) npm install`
2. run `gulp`
3. Then go to the browser and paste: "http://localhost:3000/".

## How to start an AngularJS routing app

In this example I already did the setup. But the most important things to do is:

Before you start, checkout this repo first: [How to start an AngularJS app](https://github.com/raymonschouwenaar/angularjs-first-setup)

1. Now include the ngRoute script in your html: [ngRoute source](https://code.angularjs.org/1.3.9/angular-route.js)
2. Give your application a name, in the app.js (`var ngRouteApp = angular.module("ngRouteApp", ['ngRoute']);`) & html (`<html ng-app="ngRouteApp">`). Be carfull that the name inside the angular.module("appName") is the same as the name inside the html ng-app.
