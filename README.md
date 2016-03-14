# AngularJS refactoring playground

With the present example, code refactoring scenarios can be discussed and practiced.

##Scenario
+ The application consists of two views.
  + The login dialog - consisting of an input user name 'foo' and password 'password'.
  + The picture view - consisting of two images with stored metadata, which can be read by mouse hover.
+ The user first enters the login view and enters the user data.
  + When valid user data the user enters in the picture view.
  + For invalid user data a notification appears.

## Subjects
The focus is on the following topics:

+ Software Architectural aspects such as SOLID (https://en.wikipedia.org/wiki/SOLID_(object-oriented_design))
+ Refactoring Basics
  +provide a basis for refactoring +
  + Recognize, resolve and test bad smells
+ Javascript Basics
+ AngularJS Basics
  + Building a AngularJS application
    + Declaration Pattern MV * (MVC / MVVM)
  + Detecting and explaining the concepts in AngularJS such as
    + Scopes
    + Data Binding (Two-Way Binding vs. One-Way Binding)
    + Dependency Injection & Injector
    + Templates
    + Expressions
    + Filter
    + Directives
    + Modules
    + Routing
+ AngularJS and integration with other JS frameworks such as JQuery, ZeptoJS vs. JQlite
+ Dependency Management
  + Optimization -> Application example Bower
+ Unit testing
+ Debugging
+ Automation & optimization
    + recognize the necessity and potential of automation, such as
      + Serve or Watchers
      + Browser Sync
      + Wireing dependencies
      + Automation (unit-) test
    + recognize the need for optimization such as
      + minification
      + concatenation
      + Vendor prefixes
      + ngAnnotate
      + File Suffixes

## Setting up the environment

`` `Bash
npm install
`` `

## Gulp tasks

Following Gulp tasks are available:

Start the entire environment:
```bash
gulp
```


Start reviewing the coding guidelines:
```bash
gulp jshint
```

Start the "imaginary" unit tests:
```bash
gulp test
```

Starting the Web Server:
```bash
gulp connect
```
