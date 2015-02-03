Demo AngularJS Path
===================

## Intro to Angular

### Angular in 20'ish minutes

[https://www.youtube.com/watch?v=tnXO-i7944M](https://www.youtube.com/watch?v=tnXO-i7944M)

### How AngularJS compares to jQuery

[https://www.airpair.com/angularjs/posts/jquery-angularjs-comparison-migration-walkthrough](https://www.airpair.com/angularjs/posts/jquery-angularjs-comparison-migration-walkthrough)

### Intro to directives

At a high level, directives are markers on a DOM element (such as an attribute, element name, comment or CSS class) that tell AngularJS's HTML compiler ($compile) to attach a specified behavior to that DOM element or even transform the DOM element and its children.

Angular comes with a set of these directives built-in, like ngBind, ngModel, and ngClass. Much like you create controllers and services, you can create your own directives for Angular to use. When Angular bootstraps your application, the HTML compiler traverses the DOM matching directives against the DOM elements.

[https://docs.angularjs.org/guide/directive](https://docs.angularjs.org/guide/directive)

### Using built in directives (ng-app)

    <!DOCTYPE html>
    <html lang="en">
    <head>
    <meta charset="utf-8">
    <title>Angular Demo</title>
    <script src="bower_components/angular/angular.js"></script>
    </head>
    <body ng-app>

    </body>
    </html>

### Implment bindings and expressions in HTML (ng-init, ng-model)

    <!DOCTYPE html>
    <html lang="en">
    <head>
    <meta charset="utf-8">
    <title>Angular Demo</title>
    <script src="bower_components/angular/angular.js"></script>
    </head>
    <body ng-app>

    <!-- bind an expression -->
    <h1>Welcome {{ 1 + 1 }}</h1>

    <!-- bind to a property on the scope object -->
    <h1>Welcome {{ person.name }}</h1>

    <!-- populate the person object on the scope object using ng-init directive -->
    <h1 ng-init="person = {name: 'dan'}">Welcome {{ person.name }}</h1>

    <!-- input bound to a property on the scope using ng-model directive -->
    <p><input type="text" ng-model="person.name"></p>

    </body>
    </html>

Exercise

### Implement events (ng-click)

Code

Exercise

********************************************************************

## Angular Components: Modules

### Intro to modules

Text

### Getting and setting modules

Code

Exercise

### Config and run blocks

Code

Exercise

********************************************************************

## Angular Components: Controllers

### Intro to controllers

Text

### Defining controllers and accessing properties

Code

### Controller methods

Code

Exercise

### $scope vs. this

Code

[http://www.johnpapa.net/do-you-like-your-angular-controllers-with-or-without-sugar/](http://www.johnpapa.net/do-you-like-your-angular-controllers-with-or-without-sugar/)

### Controllers as view models

Text

Exercise

### Rethinking AngularJS Controllers

[http://toddmotto.com/rethinking-angular-js-controllers/](http://toddmotto.com/rethinking-angular-js-controllers/)

********************************************************************

## Angular Components: Services

### Intro to services

Text

### Dependency injection


[http://www.ng-newsletter.com/posts/deep-dive-in-angular-dependency-injection.html](http://www.ng-newsletter.com/posts/deep-dive-in-angular-dependency-injection.html)

### Angular built in services

Text

### Using the built in $http service to communicate with an API

Code

Exercise

### Using custom services to share data between controllers

Code

Exercise

********************************************************************

## Angular Components: Routes

Intro to routes

Text

### Different ways to reuse HTML (ng-include, ng-view, custom directives)

Text

### Using ng-include

Code

### Using $routeProvider and ng-view

Code

The new Router for AngularJS by Rob Eisenberg

[https://www.youtube.com/watch?v=h1P_Vh4gSQY](https://www.youtube.com/watch?v=h1P_Vh4gSQY)

********************************************************************

## Angular Components: Filters

### Intro to filters

Text

### Using built in filters

Code

### Creating a custom filter

Code

Exercise

********************************************************************

## Angular Components: Custom Directives

### Intro to custom directives

[http://weblogs.asp.net/dwahlin/creating-custom-angularjs-directives-part-i-the-fundamentals](http://weblogs.asp.net/dwahlin/creating-custom-angularjs-directives-part-i-the-fundamentals)

### Element and attribute directives

Code

### Directive templates

Code

Exercise

### DOM manipulation or event handling in the link() function

Code

### jQuery in Angular

Text

Exercise

### Isolate scope

[https://weblogs.asp.net/dwahlin/creating-custom-angularjs-directives-part-2-isolate-scope](http://weblogs.asp.net/dwahlin/creating-custom-angularjs-directives-part-i-the-fundamentals)

### Outside in property, inside out behavior, and two way property binding

Code

Exercise

### Directive controllers

[http://weblogs.asp.net/dwahlin/creating-custom-angularjs-directives-part-6-using-controllers](http://weblogs.asp.net/dwahlin/creating-custom-angularjs-directives-part-6-using-controllers)

Exercise

### Transclusion

[http://weblogs.asp.net/dwahlin/creating-custom-angularjs-directives-part-4-transclusion-and-restriction](http://weblogs.asp.net/dwahlin/creating-custom-angularjs-directives-part-4-transclusion-and-restriction)

### Transclusion demo

Code

Exercise

### Deep Dive into Custom Directives

[https://www.youtube.com/watch?v=UMkd0nYmLzY](https://www.youtube.com/watch?v=UMkd0nYmLzY)

********************************************************************

## Angular Components: Providers

### Provider hirearchy

Text

********************************************************************

## Project Structure

### Common approaches for directory structure

Text

### Sample project structure

Code

********************************************************************

## Angular Components: Build Tools

### Intro to Gulp.js

Text

### Sample gulpfile.js for Angular

Code

### JavaScript Build Automation With Gulp.js by John Papa

[http://www.pluralsight.com/courses/javascript-build-automation-gulpjs](http://www.pluralsight.com/courses/javascript-build-automation-gulpjs)

********************************************************************

## Testing Angular Applications

### Intro to testing strategies

Text

Writing good unit tests

Text

### Unit tests for a filter and a service

Code

### Writing good integration tests

Text

### Integration tests using Protractor

[http://angular.github.io/protractor](http://angular.github.io/protractor)

Code

********************************************************************

## Sample Application

### Task manager

Code

********************************************************************

## Best Practices

### AngularJS Patterns: Clean Code by John Papa

[http://www.pluralsight.com/courses/angularjs-patterns-clean-code](http://www.pluralsight.com/courses/angularjs-patterns-clean-code)
