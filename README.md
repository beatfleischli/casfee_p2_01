# Angular with Firebase

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.6.0.

## Installation

`npm install`, should also install firebase-tools

## Preparations

To run this example you need a firebase login, a project and a firestore database 'items' with a couple of documents with the fields 
```
color = {red, green, blue}
size = {small, medium, large}
text = 'anythingYouLike'
```
To connect to firebase, you then have to set up the '/src/environments/environments.ts' with the parameters you get when you click in the 
firebase console / Project Overview on button '</>' 'Add firebase to my Web-App'.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Firebase

`$ firebase login` login to your firebase account
`$ firebase deploy` only dist folder will be uploaded. So run `ng build` first.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

