# Core Libraries

## Classes that go over everything

* [getting-started-with-redux](https://egghead.io/courses/getting-started-with-redux)
* [up-and-running-with-redux-observable](https://egghead.io/courses/up-and-running-with-redux-observable)
* [RxJs Tutorial Playlist](https://www.youtube.com/playlist?list=PL55RiY5tL51pHpagYcrN9ubNLVXF8rGVi)

## Redux

* What is Redux?
* Who made Redux?
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
* [Advanced] What is a middleware in redux and how do you program one?
* [Advanced] What things mgiht be good to put in a middleare?

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

## Moment

* What is Moment?
* How do you parse date strings with Moment?
* How do you add or subtract time with Moment?
* How do you convert a date to UTC with Moment?

## GraphQL & Apollo

* What is GraphQL?
* What is a query?
* How do you write a query?
* What is a mutation?
* How do you write a mutation?
* How do you pass parameters into a query/mutation?
* Where do you go to test queries against Spectre's API?
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
