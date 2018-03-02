# Dev Knowledge Prerequisites

**Everything you should understand in order to successfully build new features in this project**

## SCSS

[ ] What is SASS/SCSS?
* How do you nest selectors?
* What is `&` used for when nesting selectors?
* What are and how to use variables?
* What are and how to use mixins?
* What is the `@import` directive used for?
* What is the `@extend` directive used for?

## Typescript

* Variables
  * What is `const`?
  * What is `let`?
  * What is `var`?
  * What is the difference between them?
  * When should you use `const`? `let`? `var`?
  * What is scope?
    * What are global scope, function scope, and block scope?
* Arrays
  * How do you create an array?
  * How do you type an array?
  * How do you make a copy of an array? Name as many ways as you can.
  * How do you combine two arrays together?
  * What operators can you use on an array?
    * What does `forEach()` do? What does it return? When should you use it?
    * What does `map()` do? What does it return? When should you use it?
    * What does `filter()` do? What does it return? When should you use it?
    * What does `reduce()` do? What does it return? When should you use it?
    * What does `find()` do? What does it return? When should you use it?
    * What does `findIndex()` do? What does it return? When should you use it?
    * What does `push()` do? What does it return? When should you use it?
    * What does `pop()` do? What does it return? When should you use it?
    * What does `shift()` do? What does it return? When should you use it?
    * What does `unshift()` do? What does it return? When should you use it?
* Objects
  * What is a generic object?
  * How do you create a generic object?
  * How can you assign properties to objects? Name as many ways as you can.
  * How do you make a copy of an object? Name as many ways as you can.
  * How do you combine two or more objects into one?
* Arrow functions
  * What are they?
  * Why use them?
  * How is `() => { ... }` different from `function() { ... }`?
* this
  * What is `this`?
  * Why is it special?
  * How is the value of `this` assigned?
* Destructuring
  * What is destructuring?
  * How do you destructure an object?
    * What does `...object` do?
  * How do you destructure an array?
    * What does `...array` do?
  * Where can you use destructuring?
* Classes
  * What is a class?
  * What is a property?
  * What is a method?
  * What are access modifiers?
    * What is the difference between public, protected, and private?
    * If you don't specify an access modifier, which one is implied by default?
  * What are getters and setters?
  * What do extends and implements mean?
  * What is the difference between extends and implements?
  * When do you need a constructor?
    * What does adding an access modifier to a parameter in the constructor do?
  * What does `super()` do?
  * What does `static` mean and when should you use it?
  * What does `readonly` mean and when should you use it?
* Interfaces
  * What is an interface?
  * How is it different from a class?
  * When should you use an interface and when should you use a class?
  * How do you make a property optional?
* Modules
  * What is a Typescript module?
  * How do you import a module?
    * When do you use `import { Something } from 'some-module';`?
    * When do you use `import Something from 'some-module';`?
    * When do you use `import * as Something from 'some-module';`?
    * What is the difference between the three?
  * How do you create a module?
  * How do you export things from a module?
  * What's the difference between a default export and a named export?
* Types
  * What is a type?
  * What types are built in to typescript?
  * What's the difference between `Boolean` and `boolean` and which should you use?
  * What are Intersection Types and Union Types?
  * How do you typecast something in TypeScript?
    * What forms of typecasting are only hints to the typescript compiler?
    * What forms of typecasting actually change something's type in the resulting javascript?
  * How do you create your own type?
  * When should you use a type vs an interface or class?
  * What is a typescript declaration file?
  * How do you type a function?
    * If a function doesn't return anything, what return type should you use?
* Enums
  * What is an enum?
  * When should you use an enum?
* Generics
  * What are generics?
  * When should you use generics?
* Decorators
  * What is a decorator?
  * How do you create a decorator?
* Promises
  * What is a promise?
  * How do you create a promise?
    * What does `resolve()` do?
    * What does `reject()` do?
  * How do you use a promise?
    * What does `then()` do?
    * Can you chain promises together?
    * How do you handle errors?

## Angular

* Components
  * What is a component?
  * How do you create a component?
  * What options go in the component decorator?
  * What are @Input and @Output used for?
  * What are lifecycle methods?
    * How many are there?
    * When does each one get called?
    * What types of code should you put in each one?
  * What is an EventEmitter?
* Templates
  * What is a template?
  * What is interpolation?
  * How do you add inline styles?
  * How do you dynamically add css classes?
  * How do you bind to a property (input)?
  * How do you bind to an event (output)?
  * What is two-way binding? How and when do you use it?
  * What is a template reference variable?
    * When do you use it?
    * How do you reference one element from another element?
  * What is the elvis operator?
    * What does it do?
    * When do you use it?
    * [Advanced] Why should you avoid using it?
* Components & Templates
  * How do you access component properties and methods within a template?
  * How do you access a template element from within a component class?
  * What are ViewChildren?
  * What are ContentChildren?
  * How do you access ViewChildren and ContentChildren within a component class?
  * What is the built-in `<ng-content>` component and when do you use it?
  * What is the built-in `<ng-template>` component and when do you use it?
  * What is the built-in `<ng-container>` component and when do you use it?
* Styling
  * How do you style a component?
  * Why doesn't one component's styles affect other components?
  * What is the `:host` selector and when do you use it?
  * What is the `::ng-deep` selector and when do you use it?
* Directives
  * What is a directive?
    * What is an attribute directive?
    * What is a structural directive?
    * What are the differences between the two?
  * What are some built-in attribute directives?
    * What do they do?
    * How and when do you use them?
  * What are some built-in structural directives?
    * What do they do?
    * How and when do you use them?
  * How would you create your own attribute directive?
  * How would you create your own structural directive?
* Pipes
  * What is a pipe?
  * What are some built-in pipes?
    * What do they do?
    * How do you use them?
  * How do you create your own pipe?
  * What is the async pipe?
    * How do you use the async pipe?
    * [Advanced] Why should you avoid using it?
* Services
  * What is a service?
  * What is the difference between a service and a provider?
  * What are services used for?
  * How do you create a service?
* Modules
  * What is an angular module?
  * What goes in the module's imports array?
  * What goes in the module's declarations array?
  * What goes in the module's exports array?
  * What goes in the module's providers array?
  * What is `forRoot()` and when do you need it?
  * How do you create a new module?
* Forms
  * What is a form?
  * What is the difference between a template-driven form and a reactive form?
  * What do you add to a template when creating a reactive form?
  * How do you create a model for a reactive form?
  * How do you get values from a reactive form?
  * How do you set values in a reactive form?
  * [Advanced] Why do we prefer reactive forms over template-driven forms?
* Testing
  * What is a unit test?
  * What is jasmine?
  * What is karma?
  * How do you write a unit test?
    * what does `describe()` do?
    * What do `beforeAll()`, `beforeEach()`, `afterAll()`, and `afterEach()` do?
    * What does `it()` do?
    * What does `expect()` do? What methods can you chain after `expect()` and what do they do?
  * What is a spy?
    * How do you use a spy?
    * How do you create a spy?
  * How do you run all unit tests in the project?
  * How do you exclude a test from the project?
  * How do you run only one test?
* Dependency Injection
  * What is dependency injection?
  * How does Angular's dependency injection system work?
  * What roles do angular modules play in dependency injection?
  * What steps do you need to take to add a dependency within a component?
* Change detection
  * What is change detection?
  * What is Angular's default change detection strategy?
  * What is the OnPush change detection strategy, and how is it different?
  * What is the ChangeDetectorRef?
    * What methods does it contain?
    * What do they do?
* Environment
  * What are environment files in Angular?
  * How do you access them within the app?
  * How do you add things to environment files?
  * How do you create new environment files?
* Router
  * What is the Angular Router?
  * What is a route?
  * How do you access the current route within your component?
  * How do you add new routes to the application?
* Bootstrapping
  * What is bootstrapping?
  * How do you bootstrap an Angular app?

## GraphQL & Apollo

* What is GraphQL?
* What is a query?
* How do you write a query?
* What is a mutation?
* How do you write a mutation?
* How do you pass parameters into a query/mutation?
* Where do you go to test queries against Spectre's API?
* What is Apollo?
* What does the graphql-tag library do?
* What role does apollo-client play?
* What role does apollo-cache play?
  * How many apollo-cache libraries are there? Which ones do we use?
* What role does apollo-link play?
  * How many apollo-link libraries are there? Which ones do we use?
* What role does apollo-angular play?
* How do you access Apollo within an Angular app?
* How do you run a graphql query using Apollo? 
  * How do you access the query results?
  * What happens if the query errors?
  * How should you handle errors?
* How do you run a GraphQL mutation using Apollo?
  * How do you access the mutation results?
  * What happens if the mutation errors?
  * How should you handle errors?
* How do you set up multiple Apollo clients?
  * How do you run a query using a specific client?
  * How many Apollo clients do we use? Why?

## Redux

* What is Redux?
* What is state?
  * Why must state be immutable?
  * What does immutable mean?
* What is the store?
* What is an action?
  * What must an action have?
  * What is an action creator?
  * What does `dispatch()` do?
* What is a reducer?
  * What is a pure function?
  * What is a side effect?
    * What do we use to handle side effects?
  * Why must a reducer be pure?
  * How many reducers does a Redux store have?
  * How do you break apart a reducer into smaller pieces that affect specific sections of the state tree?
    * [Advanced] How do you handle arrays such that a reducer only sees and acts upon individual items in that array?

## RxJS

* What is an observable?
  * What makes an observable different from an array?
  * What makes an observable different from a promise?
  * How do you create an observable...
    * ...from an event?
    * ...from an array?
    * ...from an interval?
    * ...from null?
* What is an operator?
  * How does `pluck()` work?
  * How does `do()` work?
    * When should you use it?
  * How does `filter()` work?
    * When should you use it?
  * How does `map()` work?
    * When should you use it?
  * How does `mergeMap()` work?
    * How is it different from `map()`?
    * When should you use it?
  * How does `switchMap()` work?
    * How is it different from `map()`?
    * How is it different from `mergeMap()`?
    * When should you use it?
  * How does `combineAll()` work?
    * When should you use it?
  * How does `combineLatest()` work?
    * How is it different from `combineAll()`?
    * When should you use it?
  * How does `pairwise()` work?
    * When should you use it?
  * How does `startWith()` work?
    * When should you use it?
* What does `subscribe()` do?
* When should you unsubscribe?
* What's the difference between a cold observable and a hot observable?
* [Advanced] What is a subject?
  * How is a subject different from an observable?
  * How do you turn a subject into an observable?
  * When should you use a subject?
  * What does `next()` do?

## Redux Observable

* What is an Epic?
* What does an epic take in?
* What does an epic return?
* What do we use epics for?
* How do you create an epic?
* How do you add an epic to redux so it will get called?
* Which does an action reach first, an epic or a reducer?
* How do you access the current redux state in an epic?

## Lodash

* What is Lodash?
* What does `_.isEqual` do?
* What does `_.orderBy` do?
* What does `_.pick` do?

## Moment

* What is Moment?
* How do you parse date strings with Moment?
* How do you add or subtract time with Moment?
* How do you convert a date to UTC with Moment?

## D3

* What is D3?
* For what are we using D3?
* [Really Really Advanced] How do you use D3?

## Spectre

* What is a DataDisplay?
  * What is a TimeSeriesDataDisplay? How is it different?
* How are we using DataDisplays?
* How do you get a DataDisplay from the API?
* How do you create a DataDisplay?

## HTTP

* What is HTTP?
* What is a request?
  * What parts can a request contain?
    * What are headers?
    * What is a request body?
    * How can a request body be formatted?
  * What are request methods?
    * When do you use GET?
    * When do you use POST?
    * When do you use PUT?
    * When do you use DELETE?
  * How do you create a request using a web browser?
  * How do you create a request using javascript/typescript?
* What is a response?
  * What parts does a response contain?
  * What are HTTP status codes? What are the most common ones and what do they mean?
    * What response code indicates success?
    * What happens when your browser receives a 301 response code? A 302 response code?
    * What are the 4XX codes used for?
    * What are the 5XX codes used for?
* [Bonus Points] What is a cookie?
  * What is a secure cookie? How is it different?
  * How much data can be stored in a cookie?
  * How long does a cookie persist?

## Debugging

* How do you access your browser's dev tools?
* What purpose does the Elements tab serve?
* How do you create and test CSS changes in your browser?
* What purpose does the Console tab serve?
  * What are the different log levels and what are they used for?
  * What methods does the `console` API contain and what do they do?
    * What's the difference between `console.log()` and `console.dir()`?
* What purpose does the Sources tab serve?
  * What is a breakpoint? Name two ways to create one.
  * [Advanced] What are source maps?
* What purpose does the Network tab serve?
  * What are the request types it shows? What's the difference between them?
* What is redux dev tools and how do you add it to your browser?
  * What is the inspector tab used for?
  * What is the log monitor tab used for?

## LocalStorage

* What is LocalStorage?
* How do you save data to LocalStorage?
* How do you retrieve data from LocalStorage?
* How long does data stored in LocalStorage persist?
* How much can you store in LocalStorage?

## History

* What is the History API?
* How do you add entries to the History API?
* How do you replace entries in the History API?
* How do you move through entries in the History API?

## TSLint

* What is linting?
* What is TSLint?
* Where are the TSLint rules configured?
* How do you add a new rule to TSLint?
* Why do we use TSLint?

## Prettier

* What is Prettier?
* Why do we use Prettier?
* Where is Prettier's configuration in this project?

## Webpack

* What is Webpack?
* How are we currently using webpack?
* Where is the webpack config?

## Typescript Compiler

* What is a compiler?
* What does the Typescript compiler do?
* Where is the typescript compiler configuration located for this project?

## Angular CLI

* What is the Angular CLI?
* How do you create a new Angular app using the CLI?
* How do you run the Angular app in development mode?
* How do you build the Angular app for deployment?
  * What are build flags?
  * How do you set the Angular environment when building?
  * What other build flags are available? What do they do?
  * What is the difference between JIT and AOT compilation?
* How do you generate a new component, directive, service, pipe, etc. using the Angular CLI?
  * What is a scaffold?
* What is angular-cli.json? How is it different from a webpack config?
  * How do you include external scripts and stylesheets in the app?

## NPM

* What is NPM?
* What is package.json?
* What is package-lock.json?
  * How is it different from package.json?
* What is the scripts section of package.json used for?
* How do you add a new package with NPM?
  * How do you save the package in package.json?
  * How do you save a package for development only?
    * What's the difference?
  * How do you add a package globally with NPM?
    * What does it mean to add a package globally?
* When you first set up the project on your machine, how do you install all of the dependencies using NPM?
  * When someone else changes the project's package.json, how do you add missing dependencies to your local project?
* How do you update a package with NPM?
  * How do you update (or downgrade) a package to a specific version with NPM?
  * What do '@latest' and '@next' mean?
* How do you version lock a package in this project?
  * What does version locking mean?
  * Why do we version lock all packages in this project?
* [Advanced] How do you create a new NPM package?

## DefinitelyTyped

* What is DefinitelyTyped?
* What happens if a package doesn't include its own type definitions?
* How do you find a type definition package on DefinitelyTyped?
* What do you do if there isn't a type definition package on DefinitelyTyped for the library you want to use?

## JSDoc Comments

* What is a JSDoc comment?
* How do you write a JSDoc comment?
* What should you include in a JSDoc comment?

## Naming

* What are the naming conventions you should follow in Angular and Typescript?
  * How should you name a component?
  * How should you name a file that contains a component class?
  * How about for directives, modules, pipes, services, and tests?
  * File names for component templates and styles?
* How should you name functions/methods, parameters, properties, and variables?
  * When is it acceptable to use short/abbreviated parameter names?
  * When is it acceptable to use short/abbreviated variable names?
