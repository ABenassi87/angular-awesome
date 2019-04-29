<img src="/assets/images/angular-logo.png" title="Angular Logo">

# Index:
- [Official Resources](#official-resources)
- [Community](#community)
- [Cheatsheet](#cheatsheet)
- [Features](#features)
    - [Annotations](#annotations)
    - [View](#view)
    - [Templates](#templates)
    - [Change detection](#change-detection)
    - [Dependency Injection](#dependency-injection)
    - [Pipes](#pipes)
    - [Web Workers](#web-workers)
    - [HTTP](#http)
    - [Router](#router)
    - [Test](#test)
    - [Ahead-of-Time Compilation](#ahead-of-time-compilation)
- [Courses-Tutorials](#courses-tutorials)
- [Angular Connect](#angular-connect)
- [Books](#books)
- [Components](#components)
- [Integrations](#integrations)
- [TodoMVC](#todomvc)
- [Others](#others)


## Official Resources:
- [Site](https://angular.io/)
- [Blog](http://angularjs.blogspot.com/)
- [Documentation](https://angular.io/docs/js/latest/)
- [Cheatsheet](https://angular.io/cheatsheet)
- [Quick Start Guide](https://angular.io/docs/js/latest/quickstart.html)
- [GitHub Repo](https://github.com/angular/angular)

## Community:
- [`#angular2`](https://twitter.com/hashtag/angular2) hashtag on Twitter
- [Gitter Channel](https://gitter.im/angular/angular)
- [Angular StackOverflow](http://stackoverflow.com/questions/tagged/angular2)
- [@AngularJS on Twitter](https://twitter.com/angularjs)
- [/r/Angular2 Subreddit](https://www.reddit.com/r/Angular2/)
- [Angular Group on Facebook](https://www.facebook.com/groups/angular2/)
- [AngularJS on Google+](https://plus.google.com/+AngularJS)
- [AngularAir](http://angular-air.com/) podcast and live broadcast
- [Adventures in Angular](https://devchat.tv/adv-in-angular) podcast
- [ng-newsletter](http://www.ng-newsletter.com) email newsletter
- [Angular Expo](http://angularexpo.com/) showcase
- [`#ng-2 Slack Channel`](https://angularbuddies.slack.com/messages/ng-2/) on AngularBuddies
- [`#angular2 Slack Channel`](https://dartlang.slack.com/messages/angular2) on dartlang.slack.com ([Sign up](https://dartlang-slack.herokuapp.com/))

## Cheatsheet
- [Official Angular Cheatsheet](https://angular.io/cheatsheet)
- [Dart API Cheatsheet](https://docs.google.com/document/d/1FYyA-b9rc2UtlYyQXjW7lx4Y08MSpuWcbbuqVCxHga0/edit#heading=h.34sus6g4zss3)
- [Angular2 Dart cheatsheet](https://github.com/andresaraujo/angular2_cheatsheet_dart)
- [Angular Performance Checklist](https://github.com/mgechev/angular-performance-checklist)

## Features

##### Annotations
###### Directives
Directives allow you to attach behavior to elements in the DOM.
<br>[Read more »](features/Annotations.md#directives)

###### Components
A component is a directive which uses shadow DOM to create encapsulate visual behavior. Components are typically used to create UI widgets or to break up the application into smaller components.
<br>[Read more »](features/Annotations.md#components)

##### View
A View is a core primitive used by angular to render the DOM tree.
<br>[Read more »](features/View.md)

##### Templates
Templates are markup which is added to HTML to declaratively describe how the application model should be
projected to DOM as well as which DOM events should invoke which methods on the controller.
<br>[Read more »](features/Templates.md)

##### Change detection
Every component gets a change detector responsible for checking the bindings defined in its template.
<br>[Read more »](features/ChangeDetection.md)

##### Dependency Injection
Angular 1.x has two APIs for injecting dependencies into a directive. Angular 2 unifies the two APIs, making the code easier to understand and test.
<br>[Read more »](features/DI.md)

##### Pipes
Pipes can be appended on the end of the expressions to translate the value to a different format.
<br>[Read more »](features/Pipes.md)

##### Web Workers
WebWorker support in Angular2 is designed to make it easy to leverage parallelization in your web application.
When you choose to run your application in a WebWorker angular runs both your application's logic and the
majority of the core angular framework in a WebWorker.
<br>[Read more »](features/WebWorkers.md)

##### HTTP
Http is available as an injectable class, with methods to perform http requests. Calling request returns an EventEmitter which will emit a single Response when a response is received.
* [Introduction to HTTP in Angular 2](http://www.syntaxsuccess.com/viewarticle/angular-2.0-and-http)
<br>[Read more »](features/HTTP.md)

##### Router
* [Official Router](https://angular.io/docs/ts/latest/guide/router.html#!#sts=Router%20imports)
* [ui-router](https://github.com/angular-ui/ui-router)

##### Test
* [Testing Http services in Angular 2 with Jasmine](http://chariotsolutions.com/blog/post/testing-http-services-angular-2-jasmine/)
* [Testing UI Components with the TestComponentBuilder](http://chariotsolutions.com/blog/post/testing-angular-2-components-unit-tests-testcomponentbuilder/)

##### Ahead-of-Time Compilation
* [Official Documentation](https://angular.io/docs/ts/latest/cookbook/aot-compiler.html)
* [Ahead-of-Time Compilation in Angular 2](http://blog.mgechev.com/2016/08/14/ahead-of-time-compilation-angular-offline-precompilation/)
* [Building an Angular 2 Application for Production](http://blog.mgechev.com/2016/06/26/tree-shaking-angular2-production-build-rollup-javascript/)
* [Demystifying Ahead-Of-Time Compilation In Angular 2](http://slides.com/wassimchegham/demystifying-ahead-of-time-compilation-in-angular-2-aot-jit)
* [Code Example with Webpack](https://github.com/blacksonic/angular2-aot-webpack)
* [Code Example with Rollup](https://github.com/mgechev/angular2-ngc-rollup-build)

## Courses-Tutorials
- [Egghead.io - Angular](https://egghead.io/technologies/angular2)
- [Egghead.io - Build Redux Style Applications with Angular2, RxJS, and ngrx/store](https://egghead.io/courses/building-a-time-machine-with-angular-2-and-rxjs)
- [HiRez.io - Angular Basics](https://www.hirez.io/c/angular-basics-1/e/episode-1-course-overview)
- [HiRez.io - Angular In Depth - Components](https://www.hirez.io/c/components-1/e/episode-1-course-overview)
- [udemy - Introduction to Angular](https://www.udemy.com/introduction-to-angular2/)
- [udemy - Angular with TypeScript for Beginners: The Pragmatic Guide](https://www.udemy.com/angular-2-tutorial-for-beginners/)
- [udemy - The Complete Guide to Angular](https://www.udemy.com/the-complete-guide-to-angular-2/)
- [Pluralsight - Angular: First Look](https://www.pluralsight.com/courses/angular-2-first-look)
- [Pluralsight - Angular: Getting Started](https://www.pluralsight.com/courses/angular-2-getting-started-update)
- [Channel9 - The Future of TypeScript: ECMAScript 6, Async/Await and Richer Libraries](https://channel9.msdn.com/Events/Build/2015/3-644)
- [Channel9 - Creating Cross-Platform Apps with Angular](https://channel9.msdn.com/Events/Build/2016/T627)
- [Code School - Accelerating Through Angular](https://www.codeschool.com/courses/accelerating-through-angular)
- [Angular typed Store](https://www.youtube.com/watch?v=bEkPEnudm7s&feature=youtu.be)
- [Angular advanced tips and tricks](https://www.youtube.com/watch?v=vyiyJCLlGwo&feature=youtu.be)
- [Angular Fullstack JavaScript Channel](https://www.youtube.com/channel/UCRefxaAA-7PfezH3CY87fzw)
- [Angular 4 Master Class: Beginner to Advanced](https://www.udemy.com/angular-crash-course-for-beginners) 

## Angular Connect
- [Keynote – Brad Green, Igor Minar and Jules Kremer](https://www.youtube.com/watch?v=UxjgUjVpe24)
- [Testing strategies with Angular – Julie Ralph](https://www.youtube.com/watch?v=C0F2E-PRm44)
- [Building native mobile apps with Angular 0 and NativeScript​ - Sebastian Witalec](https://www.youtube.com/watch?v=4SbiiyRSIwo)
- [Angular Data Flow – Jeff Cross, Rob Wormald and Alex Rickabaugh](https://www.youtube.com/watch?v=bVI5gGTEQ_U)
- [Iterative version upgrade strategies for large Angular applications – Jen Bourey](https://www.youtube.com/watch?v=8tGcdaItj0I)
- [Debugging Angular Apps with Batarangle – Yuri Takhteyev and Igor Krivanov](https://www.youtube.com/watch?v=cAC4d3KIQcM)
- [Building apps with Firebase and Angular - Sara Robinson](https://www.youtube.com/watch?v=RD0xYicNcaY)
- [Better concepts, less code in Angular - Victor Savkin and Tobias Bosch](https://www.youtube.com/watch?v=4YmnbGoh49U)
- [Modularity and Packaging for Angular2 Applications – Pawel Kozlowski](https://www.youtube.com/watch?v=9odY9Rh5kTQ)
- [Creating realtime apps with Angular and Meteor - Uri Goldshtein](https://www.youtube.com/watch?v=3FT0BqYASCo)

## Books
- [ng-book 2](https://www.ng-book.com/2/) `fullstack.io`
- [Become a ninja with Angular](https://books.ninja-squad.com/angular2) `Ninja Squad`
- [Angular Development with TypeScript](https://www.manning.com/books/angular-2-development-with-typescript) `Manning Publications`
- [Angular in Action](https://www.manning.com/books/angular-2-in-action) `Manning Publications`
- [Practical Angular](https://leanpub.com/practical-angular-2) `Leanpub`
- [Switching to Angular](https://www.packtpub.com/web-development/switching-angular-2) `Packt Publishing`
- [Testing Angular Applications](https://www.manning.com/books/testing-angular-2-applications) `Manning Publications`
- [Rangle's Angular training](https://www.gitbook.com/book/rangle-io/ngcourse2/details) `Rangle.io`

## Components:
[Ir a Página](components/Components.md)
 
## Integrations
- [FalcorJS + Angular2 (Video)](https://www.youtube.com/watch?v=z8UgDZ4rXBU&feature=youtu.be)
- [Angular2-Meteor](https://www.angular-meteor.com/angular2)
- [nativescript-angular](https://github.com/NativeScript/nativescript-angular)
- [react-native-renderer](https://github.com/angular/react-native-renderer)

## TodoMVC
- [Official Angular](http://todomvc.com/examples/angular2/)

## Others:
- [Angular: NGRX a clean and clear Introduction](https://medium.com/frontend-fun/angular-ngrx-a-clean-and-clear-introduction-4ed61c89c1fc)
- [Making an Angular project mono repo with NgRx state management and lazy-loading](https://blog.angularindepth.com/making-angular-project-mono-repo-with-ngrx-state-management-and-lazy-loading-3f09178319d4)
- [Comprehensive Introduction to @ngrx/store](https://gist.github.com/btroncone/a6e4347326749f938510)
- [Adding Redux With NgRx/store and Angular2 - Part 1](http://orizens.com/wp/topics/adding-redux-with-ngrxstore-to-angular-2-part-1/)
- [Adding Redux with NgRx/store to Angular2 – Part 2 (Testing Reducers)](http://orizens.com/wp/topics/adding-redux-with-ngrxstore-to-angular2-part-2-testing-reducers/)
- [Angular & NgRx/store: The NgModel In Between Use Case (from AngularJS)](http://orizens.com/wp/topics/angular-2-ngrxstore-the-ngmodel-in-between-use-case-from-angular-1/)
- [Angular, Ngrx/Store & Ngrx/Effects – Intro To Functional Approach For A Chain Of Actions](http://orizens.com/wp/topics/angular-2-ngrxstore-ngrxeffects-intro-to-functional-approach-for-a-chain-of-actions/)
- [Making chained API Calls using @ngrx/Effects](https://gist.github.com/peterbsmith2/ce94c0a5ddceb99bab24a761731d1f07)
- [Authentication in Angular with NGRX](http://mherman.org/blog/2018/04/17/authentication-in-angular-with-ngrx)
- [Angular with OpenID Connect Implicit Flow from Damien Bowden](https://damienbod.com/2016/03/02/angular2-openid-connect-implicit-flow-with-identityserver4/)
- [Angular bootstrap4 OAuth2 Webpack from Michael Oryl](https://github.com/michaeloryl/angular2-bootstrap4-oauth2-webpack)
- [Angular OAuth2 OIDC from Manfred Steyer](https://www.softwarearchitekt.at/post/2016/07/03/authentication-in-angular-2-with-oauth2-oidc-and-guards-for-the-newest-new-router-english-version.aspx)
- [Angular authentication sample from auth0-blog](https://github.com/auth0-blog/angular2-authentication-sample)
