# Design Patterns

**Context: [frontend-dev-bookmarks](../README.md) / Architecture**

Best practices that the programmer can use to solve common problems when designing an application or system.

[![frontend.directory](https://img.shields.io/badge/frontend-directory-blue.svg?style=flat-square)](http://frontend.directory/)
[![PayPal](https://img.shields.io/badge/donate-PayPal-00457c.svg?style=flat-square&maxAge=2592000)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=4FAGPMANWRVJJ)
[![Beerpay](https://beerpay.io/dypsilon/frontend-dev-bookmarks/badge.svg?style=flat-square)](https://beerpay.io/dypsilon/frontend-dev-bookmarks)
[![Flattr](https://img.shields.io/badge/donate-Flattr-88b058.svg?style=flat-square&maxAge=2592000)](https://flattr.com/submit/auto?fid=3nlo5p&url=https%3A%2F%2Fgithub.com%2Fdypsilon%2Ffrontend-dev-bookmarks)
[![Gitter](https://img.shields.io/gitter/room/dypsilon/frontend-dev-bookmarks.svg?style=flat-square&maxAge=2592000)](https://gitter.im/dypsilon/frontend-dev-bookmarks)
[![Twitter](https://img.shields.io/badge/follow-twitter-55acee.svg?style=flat-square)](https://twitter.com/FrontendDir)

-----------------------------------------

+ **[About HTML Semantics and Frontend Architecture](http://nicolasgallagher.com/about-html-semantics-front-end-architecture/)**: A collection of thoughts, experiences, ideas on HTML semantics, components and approaches to front-end architecture, class naming patterns, and HTTP compression.
+ **[Box Tech Talk: Scalable JavaScript Application Architecture](https://www.youtube.com/watch?v=mKouqShWI4o)**: A video by Nicholas Zakas (2012) about JavaScript Architecture.
+ **[CSS Modules](https://github.com/css-modules)**: A CSS Module is a CSS file in which all class names and animation names are scoped locally by default.
    + **[CSS Modules Documentation](https://github.com/css-modules/css-modules)**: General overview and some implementations.
    + **[ES CSS Modules](https://github.com/jacobp100/es-css-modules)**: PostCSS plugin that combines CSS Modules and ES Imports.
    + **[Tree Shaking Bootstrap](https://medium.com/@jacobp/tree-shaking-bootstrap-95d6301f61a9)**: Jacob Parker describes how to include only those parts of Bootstrap you are really using on your website by leveraging CSS modules and ES6 modules.
+ **JavaScript Modules**: Modules divide programs into clusters of code that, by some criterion, belong together.
    + **[Chapter 10 of Eloquent JavaScript: Modules](http://eloquentjavascript.net/10_modules.html)**: This chapter explores some of the benefits that division of code provides and shows techniques for building modules in JavaScript.
    + **[ES6 In Depth: Modules](https://hacks.mozilla.org/2015/08/es6-in-depth-modules/)**: This article highlights export and import keywords from ES6.
    + **[JavaScript Modules: A Beginner’s Guide](https://medium.freecodecamp.com/javascript-modules-a-beginner-s-guide-783f7d7a5fcc#.i78m6tfs9)**: In this post, Preethi Kasireddy will unpack the buzzwords like module bundlers, AMD and CommonJS for you in plain English, including a few code samples.
    + **[Modern Modular JavaScript Design Patterns](https://addyosmani.com/resources/essentialjsdesignpatterns/book/#modularjavascript)**: A chapter from Essential JavaScript Design Patterns on Modules.
    + **Module Bundlers and Loaders**: Libraries for bundling JavaScript Modules into one or several files.
        + **[Browserify](http://browserify.org/)**: Browserify lets you require('modules') in the browser by bundling up all of your dependencies.
            + **[Watchify](https://www.npmjs.org/package/watchify)**: Watch mode for browserify builds.
        + **[Require1k](http://stuk.github.io/require1k/)**: CommonJS require for the browser in 1KB, with no build needed.
        + **[SystemJS](https://github.com/systemjs/systemjs)**: Universal dynamic module loader - loads ES6 modules, AMD, CommonJS and global scripts in the browser and NodeJS. Works with both Traceur and Babel.
            + **[Modular JavaScript: A Beginners Guide to SystemJS & JSPM](http://www.sitepoint.com/modular-javascript-systemjs-jspm/)**: The combination of jspm and SystemJS provides a unified way of installing and loading dependencies.
        + **[Webpack](http://webpack.github.io/)**: Webpack is a module bundler. It takes modules with dependencies and generates static assets representing those modules.
            + **[Block, Element, Modifying Your JavaScript Components](https://medium.com/seek-ui-engineering/block-element-modifying-your-javascript-components-d7f99fcab52b)**: Mark Dalgleish is discussing how to organize React code with BEM and build everything with Webpack.
            + **[WebpackBin](http://www.webpackbin.com/)**: A webpack code sandbox.
        + **[crapLoader](https://github.com/gregersrygg/crapLoader)**: The goal of crapLoader is to load ads, widgets or any JavaScript code with document.write in it. This library hijacks document.write and delegates the content loaded from each script into the correct position.
        + **[require.js](http://requirejs.org/)**: RequireJS is a JavaScript file and AMD module loader. It is optimized for in-browser use, but it can be used in other JavaScript environments.
        + **[uRequire](https://github.com/anodynos/urequire)**: The Ultimate JavaScript Module Builder & Automagical Task Runner.
    + **[UMD (Universal Module Definition)](https://github.com/umdjs/umd)**: This repository formalizes the design and implementation of the Universal Module Definition (UMD) API for JavaScript modules. These are modules which are capable of working everywhere, be it in the client, on the server or elsewhere.
    + **[Writing Modular JavaScript With AMD, CommonJS & ES Harmony](https://addyosmani.com/writing-modular-js/)**: In this article Addy Osmani reviewes several of the options available for writing modular JavaScript using modern module formats AMD, CommonJS and ES6 Modules.
+ **[Learning JavaScript Design Patterns](https://addyosmani.com/resources/essentialjsdesignpatterns/book/)**: In this free book Addy Osmani explores applying both classical and modern design patterns to the JavaScript programming language.
+ **[Patterns For Large-Scale JavaScript Application Architecture](https://addyosmani.com/largescalejavascript/)**: An extensive overview by Addy Osmani of existing architectural solutions in the frontend development field.
+ **Routing**: A routing system parses a string input (usually a URL) and decides which action should be executed by matching the string against multiple patterns.
    + **[Crossroads.js](http://millermedeiros.github.io/crossroads.js/)**: Crossroads.js is a powerful and flexible routing system. If used properly it can reduce code complexity by decoupling objects and also by abstracting navigation paths and server requests.
    + **[Director](https://github.com/flatiron/director)**: A tiny and isomorphic URL router for JavaScript.
    + **[Roadcrew.js](http://grobmeier.github.io/Roadcrew.js/)**: Roadcrew.js is a small JavaScript component which lets you switch pages of a single file website.
    + **[hash.js](https://github.com/javve/hash.js)**: Hash.js is a 0.5 KB script that lets you manipulate everything behind # in urls.
    + **[jQuery Address](http://www.asual.com/jquery/address/)**: The jQuery Address plugin provides powerful deep linking capabilities and allows the creation of unique virtual addresses that can point to a website section or an application state.
    + **[page.js](https://github.com/visionmedia/page.js)**: Micro client-side router inspired by the Express router.
    + **[route-recognizer](https://github.com/tildeio/route-recognizer)**: A lightweight JavaScript library that matches paths against registered routes. It includes support for dynamic and star segments and nested handlers.
    + **[router.js](https://github.com/tildeio/router.js)**: router.js is the routing microlib used by Ember.js.
+ **[Scalable JavaScript Application Architecture](https://www.youtube.com/watch?v=vXjVFPosQHw)**: In this video (2011) Nicholas Zakas discusses frontend architecture for complex, modular web applications with significant JavaScript elements.
+ **[Single Page Apps in Depth](http://singlepageappbook.com/)**: This free book is what I wanted when I started working with single page apps. It's not an API reference on a particular framework, rather, the focus is on discussing patterns, implementation choices and decent practices.
+ **[The Media Object Saves Hundreds of Lines of Code](http://www.stubbornella.org/content/2010/06/25/the-media-object-saves-hundreds-of-lines-of-code)**: Extensive description with examples of popular design pattern "media object".
+ **UI Data Binding**: Binding of UI elements to an application domain model. Most frameworks employ the Observer pattern as the underlying binding mechanism.
    + **[Change And Its Detection In JavaScript Frameworks](http://teropa.info/blog/2015/03/02/change-and-its-detection-in-javascript-frameworks.html)**: This article explores several approaches to manage state: Ember's data binding, Angular's dirty checking, React's virtual DOM, and its relationship to immutable data structures.
    + **[Easy Two-Way Data Binding in JavaScript](http://www.lucaongaro.eu/blog/2012/12/02/easy-two-way-data-binding-in-javascript/)**: Two-way data binding refers to the ability to bind changes to an object’s properties to changes in the UI, and viceversa. This article describes how to implement data binding with vanilla JavaScript.
    + **[Functional Reactive Bindings](https://github.com/kriskowal/frb)**: A CommonJS package that includes functional and generic building blocks to help incrementally ensure consistent state.
    + **[Knockout.js](http://knockoutjs.com/)**: Knockout is a standalone JavaScript implementation of the Model-View-ViewModel pattern with templates.
    + **[Rivets.js](http://rivetsjs.com/)**: Lightweight and powerful data binding + templating solution for building modern web applications.
    + **[Synapse](https://github.com/bruth/synapse/)**: Hooks to support data binding between virtually any object.
+ **Virtual DOM**: Virtual DOM is a technique and set of libraries/algorithms that allow us to improve front end performance by avoiding direct work with DOM and work only with lightweight JavaScript object that mimic the DOM tree.
    + **[Change And Its Detection In JavaScript Frameworks](http://teropa.info/blog/2015/03/02/change-and-its-detection-in-javascript-frameworks.html)**: This article explores several approaches to manage state: Ember's data binding, Angular's dirty checking, React's virtual DOM, and its relationship to immutable data structures.
    + **[Incremental DOM](https://github.com/google/incremental-dom)**: Incremental DOM is a library for building up DOM trees and updating them in-place when data changes. It differs from the established virtual DOM approach in that no intermediate tree is created (the existing tree is mutated in-place).
        + **[Introducing Incremental DOM](https://medium.com/google-developers/introducing-incremental-dom-e98f79ce2c5f)**: Incremental DOM is a library inspired by Virtual DOM developed at Google.
    + **[React Demystified](http://blog.reverberate.org/2014/02/react-demystified.html)**: This article is an attempt to explain the core ideas behind React.js and Virtual DOM.
    + **[React vs Incremental DOM vs Glimmer](https://auth0.com/blog/2015/11/20/face-off-virtual-dom-vs-incremental-dom-vs-glimmer/)**: In this post we will explore three technologies to build dynamic DOMs. We will also run benchmarks and find out which one is faster.
    + **[React-less Virtual DOM with Snabbdom: functions everywhere!](https://medium.com/@yelouafi/react-less-virtual-dom-with-snabbdom-functions-everywhere-53b672cb2fe3)**: Yassine Elouafi shows in this post how to write a virtual DOM based applications using a small and standalone library.
    + **[cito.js](https://github.com/joelrich/citojs)**: The core of cito.js consists of a virtual DOM library inspired by React/Mithril. On top of that, it will provide a component framework which will make it easy to build well-encapsulated components.
    + **[snabbdom](https://github.com/paldepind/snabbdom)**: A virtual DOM library with focus on simplicity, modularity, powerful features and performance.
    + **[virtual-dom](https://github.com/Matt-Esch/virtual-dom)**: virtual-dom is a collection of modules designed to provide a declarative way of representing the DOM for your app. So instead of updating the DOM, you simply create a virtual tree or VTree, which looks like the DOM state that you want.
        + **[html-to-vdom](https://github.com/TimBeyer/html-to-vdom)**: This is yet another library to convert HTML into a vtree. It's used in conjunction with virtual-dom to convert template based views into virtual-dom views.
        + **[html2hyperscript](https://github.com/unframework/html2hyperscript)**: Automatically translate old HTML markup into the new Hyperscript markup embeddable directly inside your component Javascript code.
        + **[vdom-to-html](https://github.com/nthtran/vdom-to-html/)**: Turn Virtual DOM nodes into HTML.
        + **[vdom-virtualize](https://github.com/marcelklehr/vdom-virtualize/)**: Turn a DOMNode into a virtual-dom node.
        + **[virtual-html](https://github.com/yoshuawuyts/virtual-html)**: Convert given HTML into Virtual DOM object.
        + **[vtree-select](https://github.com/parshap/vtree-select)**: Select vtree nodes (used by virtual-dom) using css selectors. Selector matching is done using cssauron. See the documentation for details on supported selectors.


------------------

[![frontend.directory](https://img.shields.io/badge/frontend-directory-blue.svg?style=flat-square)](http://frontend.directory/)
[![PayPal](https://img.shields.io/badge/donate-PayPal-00457c.svg?style=flat-square&maxAge=2592000)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=4FAGPMANWRVJJ)
[![Beerpay](https://beerpay.io/dypsilon/frontend-dev-bookmarks/badge.svg?style=flat-square)](https://beerpay.io/dypsilon/frontend-dev-bookmarks)
[![Flattr](https://img.shields.io/badge/donate-Flattr-88b058.svg?style=flat-square&maxAge=2592000)](https://flattr.com/submit/auto?fid=3nlo5p&url=https%3A%2F%2Fgithub.com%2Fdypsilon%2Ffrontend-dev-bookmarks)
[![Gitter](https://img.shields.io/gitter/room/dypsilon/frontend-dev-bookmarks.svg?style=flat-square&maxAge=2592000)](https://gitter.im/dypsilon/frontend-dev-bookmarks)
[![Twitter](https://img.shields.io/badge/follow-twitter-55acee.svg?style=flat-square)](https://twitter.com/FrontendDir)

# License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

Please provide a link back to this repository. This is not necessary for GitHub forks.