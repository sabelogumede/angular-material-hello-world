# AngularMaterialHelloWorld
Initializing a clean Angular Material Project
These are the commands and steps needed to scaffold a new Angular Material project from scratch, from an empty folder.
Please make sure to have the latest CLI, and at least NPM 5.
When is doubt, its recommended to update to the latest version of node using a node versioning tool such as for example nave or nvm-windows.
Step 1 - Scaffold a clean project using the Angular CLI
With a CLI version 1.5 or above, let's scaffold a new project with routing:
ng new angular-material-hello-world --routing
Step 2 - Installing Angular Material dependencies
Next, let's install these dependencies:
npm install @angular/material @angular/cdk  @angular/animations hammerjs

-	in main.ts import “hammerjs”

-	choose and import a theme on your global style.css
-	@Import ~@angular/material/prebuilt-themes/indigo-pink.css;
-	
Step 3 - Adding Google Material Icons Font https://material.io/icons/
Let's add this to our index.html:
<link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">

Step 4 - choosing a Theme
Before starting to import components, let's choose a widget theme, have a look at the themes available
inside node_modules/@angular/material/prebuild-themes.
We can for example use the Indigo Pink theme by adding this line to our styles.css file:
@import "~@angular/material/prebuilt-themes/indigo-pink.css";

Step 5 – Import material Module type you need into your app.module.ts to use it in your template.


<!-- my notes above -->


This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.3.4.

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
