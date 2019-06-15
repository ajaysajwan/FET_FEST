
# Samrt Parking Assist System
---

![node](https://img.shields.io/badge/node-10.16.0-0093E0.svg) ![npm](https://img.shields.io/badge/npm-6.9.0-0093E0.svg)
 ![Documentation Coverage](https://img.shields.io/badge/Documentation%20Coverage-96%25-4CB944.svg) ![Last Updated](https://img.shields.io/badge/Last%20Updated-2019%2F06%2F15-0093E0.svg)

### Developed in [Angular 7](https://angular.io/ "Link to Angular JS site") and styled with [Bootstrap 4.0.0](https://github.com/twbs/bootstrap/tree/v4.0.0 "Link to Bootstrap site")

>A repository primarily responsible to maintain the **[Angular 7](https://angular.io/ "Link to Angular JS site")** Smart parking assist system which navigates the user to near by parking location without waisting time.
>

### Browser Compatibility Matrix
>![Browser Compatibility](./assets/compatibility.JPG "Browser Compatibility Matrix")

### Pre-Requisites
[![node](https://img.shields.io/badge/node-%3E%3D%2010.9.0-4CB944.svg)](https://nodejs.org/en/download/releases/)

>Both the **Angular CLI** (*7.3.5*) and generated project have dependencies that require **Node 10.9.0** or higher, together with **npm 6.5.0** or higher.
>
>We recommend to have at least **npm** version **6.5.0**
>
>Please verify package version for **`@angular/cli`**, **`@angular/compiler-cli`**, **`@angular/language-service`** and **`typescript`** as mentioned in **`package.json`**

### Installation
This is a [**Node.js**](https://nodejs.org/) module available through the 
or 
[`yarn`](https://yarnpkg.com/en/)
command line tools.
# To install dependencies, you can run
        npm install
### Updating Angular CLI
To update Angular CLI to a new version, you must update both the global package and your project's local package.

**Global package:**
```bash
    npm uninstall -g @angular/cli
    npm cache verify
    npm install -g @angular/cli@7.2.0
```
**Local project package:**
```bash
    rm -rf node_modules dist
    npm install --save-dev @angular/cli@7.2.0
    npm install
```

## Dependencies

- [@angular/animations](https://ghub.io/@angular/animations): Angular - animations integration with web-animations
- [@angular/common](https://ghub.io/@angular/common): Angular - commonly needed directives and services
- [@angular/compiler](https://ghub.io/@angular/compiler): Angular - the compiler library
- [@angular/core](https://ghub.io/@angular/core): Angular - the core framework
- [@angular/forms](https://ghub.io/@angular/forms): Angular - directives and services for creating forms
- [@angular/http](https://ghub.io/@angular/http): Angular - the http service
- [@angular/platform-browser](https://ghub.io/@angular/platform-browser): Angular - library for using Angular in a web browser
- [@angular/platform-browser-dynamic](https://ghub.io/@angular/platform-browser-dynamic): Angular - library for using Angular in a web browser with JIT compilation
- [@angular/router](https://ghub.io/@angular/router): Angular - the routing library
- [core-js](https://ghub.io/core-js): Standard library
- [rxjs](https://ghub.io/rxjs): Reactive Extensions for modern JavaScript
- [zone.js](https://ghub.io/zone.js): Zones for JavaScript
- [@ng-bootstrap/ng-bootstrap](https://ghub.io/@ng-bootstrap/ng-bootstrap): Angular powered Bootstrap

### Temporary
Dependencies required for firebase mentioned in package json

## Dev Dependencies
- [@angular-devkit/build-angular](https://github.com/angular/angular-cli): DevKit's goal is to provide a large set of libraries that can be used to manage, develop, deploy and analyze your code.
- [@angular/cli](https://ghub.io/@angular/cli): CLI tool for Angular
- [@angular/compiler-cli](https://ghub.io/@angular/compiler-cli): Angular - the compiler CLI for Node.js
- [@angular/language-service](https://ghub.io/@angular/language-service): Angular - language services
- [@compodoc/compodoc](https://ghub.io/@compodoc/compodoc): The missing documentation tool for your Angular application
- [@types/jasmine](https://ghub.io/@types/jasmine): TypeScript definitions for Jasmine
- [@types/jasminewd2](https://ghub.io/@types/jasminewd2): TypeScript definitions for jasminewd2
- [@types/node](https://ghub.io/@types/node): TypeScript definitions for Node.js
- [codelyzer](https://ghub.io/codelyzer): Linting for Angular applications, following angular.io/styleguide.
- [jasmine-core](https://ghub.io/jasmine-core): Official packaging of Jasmine&#39;s core files for use by Node.js projects.
- [jasmine-spec-reporter](https://ghub.io/jasmine-spec-reporter): Spec reporter for jasmine behavior-driven development framework
- [karma](https://ghub.io/karma): Spectacular Test Runner for JavaScript.
- [karma-chrome-launcher](https://ghub.io/karma-chrome-launcher): A Karma plugin. Launcher for Chrome and Chrome Canary.
- [karma-cli](https://ghub.io/karma-cli): The Karma command line interface.
- [karma-coverage-istanbul-reporter](https://ghub.io/karma-coverage-istanbul-reporter): A karma reporter that uses the latest istanbul 1.x APIs (with full sourcemap support) to report coverage.
- [karma-html-reporter](https://ghub.io/karma-html-reporter): A Karma plugin. Report results in pretty html format.
- [karma-jasmine](https://ghub.io/karma-jasmine): A Karma plugin - adapter for Jasmine testing framework.
- [karma-jasmine-html-reporter](https://ghub.io/karma-jasmine-html-reporter): A Karma plugin. Dynamically displays tests results at debug.html page
- [ts-node](https://ghub.io/ts-node): TypeScript execution environment and REPL for node
- [tslint](https://ghub.io/tslint): An extensible static analysis linter for the TypeScript language
- [typescript](https://ghub.io/typescript): TypeScript is a language for application scale JavaScript development
### Documentation
```
npm run compodoc
```
After execution of the aove command documentation will be generated in root directory

### Build
1. Run below commands
    ```javascript
        1. npm install
        2. npm run build
    ```
2. It will generate component library package at **`./dist`** folder.
3. Publish **`./dist`** .
[CHANGELOG](CHANGELOG.md).