# NgStepbyStep - Currently in Development - Will be available soon
Understand Angular Step by Step

## Getting Started
I will be using angular cli as command line interface to generate angular items like app, component, service... etc.

### What is Angular CLI ?
It is simply having a commands to generate angular items like App, Components, Services, Directives... etc. One can simply install a node module angular-cli globally with command: **npm install -g @angular/cli**; and use its command. This will help to develope fast and develope as per standard.

More Details: https://github.com/angular/angular-cli

Next step is to generate an angular app. Follow the below lines one by one.

  1. Go to the desired directory where you wish to learn angular
  2. Create folder command: **mkdir NgStepByStep**
  3. Go inside folder command: **cd NgStepByStep**
  4. Generate App command: **ng new example-app**
  5. Go inside folder command: **cd example-app**
  6. Install dependencies command: **npm install @angular-devkit/core --save-dev**
  7. Install dependencies command: **npm install**
  8. Open server, watch for changes and launch app on browser command: **ng serve -o**

Have you gone through the folder generated using the generate app command?

No: You should go then only you can proceed

Yes: Very good! This is how you will learn.

Ohh! Its contains a lot more stuff than I think off.

Don't worry! Let's have a cup of coffee and concentrate in app folder in the path '**example-app\src\app**' and forget about the rest. It contains the app root component or parant component of all the components and app module. Following are the file wise description:-

  1. **app.component.css**: This is component specific css file
  2. **app.component.html**: This is component specific html file
  3. **app.component.spec.ts**: This is component specific testing file which will contains the logic for component testing
  4. **app.component.ts**: This is the component file itself which contains the component specific metadata.
  5. **app.module.ts**: This is the module file itself which contains the module specific metadata. Promise watch this file after generation of each angular item and observe the changes.

More Details: https://angular.io/guide/quickstart





