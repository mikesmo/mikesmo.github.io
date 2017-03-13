---
layout: post
title:  "Redux with Angular 2"
date:   2016-10-01 18:00:00
categories: blog
---

This post is part 1 of a three part series I'm writing on using Redux with Angular 2.

The benefits of Redux with Angular 2 (or any javascript framework) are:

1. Faster development when used in conjunction with [Hot Module Replacement](https://webpack.github.io/docs/hot-module-replacement.html).
2. Improved debugging.
3. Easier unit testing.

In part 1 of this blog series, I demonstrate how development time can be improved by using 
the combination of Redux + Webpack Hot Module Replacement with Angular 2. 

While developing you can have the application running and watch your
 code changes being reflected live in the application. Yes, live-reloading is provided by tools such as browserify or webpack 
 developer server but the state of the application is reset on every change.
 
 With Redux, you can retain the state so there is no need to perform any
 actions to get the application back to where you were working.

(With the client's permission, this application video is published with brand names blanked out).
<iframe width="560" height="315" src="https://www.youtube.com/embed/OIP04_ZywD4" frameborder="0" allowfullscreen></iframe>

<br/>

As you see, the application state is retained on live-reload. This means that whenever I make a code change I don't have to wait for the application to reload,
log back in, and then click through the various actions to get back to the particular component that I was working on.

This is a hug help if you are working on any complicated single-page application.

# So what is Redux?

- A library that is useful for managing the state of web applications.
- Is based upon the [Flux](https://facebook.github.io/flux/) pattern, as opposed to the 
traditional MVC pattern for designing the architecture of web applications.           
- Can be used with any other javascript application framework (Angular 1.x, Angular 2, React etc).


## Inter-component communication

In Angular 2 the standard communication model between components is by unidirectional data flow from parent
 to child components in one direction and component events in the other direction.

![Greeter](/assets/img/blog/2016-09-01-Redux-with-angular-2/angular-unidirectional-flow.png)

With redux the communication model is a bit different... 

(to be continued... sorry got busy working on another project, will write more soon)




