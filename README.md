# Alex's Angular Vault

## Description

This project is a collection of common Angular use-cases paired with their solutions. Each use-case is abstracted in its own branch and attempts to use as less code as possible in order to encapsulate all the steps necessary to handle the specific use-case. The `main` branch serves as a wiki for all the available use-cases.

The best way to use this repo is to stay on the `main` branch until you find your use-case. Then, the use-case will guide you to the branch you need to checkout in order to view a working example with the specific use-case.

## DISCLAIMER

The fact that your use-case may be featured in this repo, doesn't mean that it's the best solution for you or in general. I'm not the sharpest tool in the shed and my solutions may suck big time. Also, I do not plan to constantly maintain every single use-case.

## Project information

This project was initially generated with [Angular CLI](https://github.com/angular/angular-cli) version 12.2.1.

## Install project

After cloning, install all the `main` branch dependencies with:

`npm install`

## Development server

To run the main branch or any use-case branches, use the following:

Run `ng serve` or `npm start` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

When checking out to a specific use-case, it's highly recommended that you stop the development server and perform an `npm install`. Since those use-cases are as encapsulated as possible, it's highly likely that dependencies will differ between branches.

## Contributions

If you figure out a better solution to an existing use-case, if there is any outdated or missing use-case, consider contributing. Please always fork the project first.

- Updating an existing use-case: Open a PR on the use-case specific branch.
- Adding a new use-case: Create a new feature branch and submit it for review.

### Code scaffolding

All components are scaffolded by using angular schematics. Please do that for consistency.

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

### Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

### Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

### Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
