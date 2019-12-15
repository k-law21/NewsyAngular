# Newsy

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.3.20.

## New API
Key is ``

```
var url = 'https://newsapi.org/v2/top-headlines?' +
          'country=us&' +
          'apiKey=3bceda4701064e3d92fa5cfbf48bcf1d';
var req = new Request(url);
fetch(req)
    .then(function(response) {
        console.log(response.json());
    })
```
## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
