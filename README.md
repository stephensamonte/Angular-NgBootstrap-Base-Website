# Angular-NgBootstrap-Base-Website
Website template that uses ng Bootstrap. 

Note: This project is no longer being worked on. I also no longer use ng-bootstrap for my projects. I recommend using [Angular Material](https://material.angular.io/)

In the future will have it's own fake data and mock server which can later be swapped out for real http requests. 

Deployed Project Website: https://stephensamonte.github.io/Angular-NgBootstrap-Base-Website/

# Environment 
- This project is being edited using [Visual Stuid Code](https://code.visualstudio.com/), [GitBash Terminal](https://git-scm.com/downloads), [Angular CLI](https://cli.angular.io/) (Command Line Interface), and [ng Bootstrap](https://ng-bootstrap.github.io/#/home).
- To run the project you have to install ng Bootstrap.

# Notes: 
- This is an [Angular Website](https://angular.io/)
- This project uses [Bootstrap](https://getbootstrap.com/) via [ng Bootstrap](https://ng-bootstrap.github.io/#/home). I decided to implement bootstrap using ng bootstrap because it's a more streamline process than adding bootstrap without ng bootstrap. "Ng-Bootstrap contains a set of native Angular directives based on Bootstrap's markup and CSS. As a result no dependency on jQuery or Bootstrap's JavaScript is required."
- 

# Journal: 
- 2019.01.20 Created Angular Project using `ng new`, added `ng bootstrap` module, and bootstrap dependency [Showcase](https://www.youtube.com/watch?v=HH8cYv4SVMc&feature=youtu.be)
- 2019.01.24 Built production website for deployment & setup GitHub Pages to host production website in docs/ folder

# References: 
- This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.2.1.
- [Using Bootstrap with Angular Medium Blog](https://medium.com/codingthesmartway-com-blog/using-bootstrap-with-angular-c83c3cee3f4a) Scroll down to the section about using "Using Ng-Bootstrap"
- [ng Bootstrap Getting Started](https://ng-bootstrap.github.io/#/getting-started)
- [ng Bootstrap Components](https://ng-bootstrap.github.io/#/components/accordion/examples)
- [Angular Website Deployment](https://angular.io/guide/deployment)
- [Publishing your GitHub Pages site from a /docs folder on your master branch](https://help.github.com/articles/configuring-a-publishing-source-for-github-pages/#publishing-your-github-pages-site-from-a-docs-folder-on-your-master-branch)

## Dependencies
Run `npm install -g @angular/cli`
Run `npm install --save @ng-bootstrap/ng-bootstrap` to be able to use bootstrap components

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build & Deploy Website with GitHub Pages

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

To build the website for hosting use: `ng build --prod --output-path docs --base-href https://stephensamonte.github.io/Angular-NgBootstrap-Base-Website/`

- When publishing don't forget to add a 404.html page which is just a renamed index.html file

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
