# Designs

**Context: [frontend-dev-bookmarks](../README.md) / Architecture**

Ready to use and well documented structures and frameworks for frontend development.

[![frontend.directory](https://img.shields.io/badge/frontend-directory-blue.svg?style=flat-square)](http://frontend.directory/)
[![Gitter](https://img.shields.io/gitter/room/dypsilon/frontend-dev-bookmarks.svg?style=flat-square&maxAge=2592000)](https://gitter.im/dypsilon/frontend-dev-bookmarks)
[![Twitter](https://img.shields.io/badge/follow-twitter-55acee.svg?style=flat-square)](https://twitter.com/FrontendDir)

-----------------------------------------
+ **[Atomic Design](http://atomicdesign.bradfrost.com/table-of-contents/)**: Atomic Design discusses the importance of crafting robust design systems, and introduces a methodology for which to create smart, deliberate interface systems.
    + **[A More Seamless Workflow — Style Guides for Better Design and Development](https://medium.com/@AshConnolly/a-more-seamless-workflow-style-guides-for-better-design-and-development-639fc55be28c)**: Ash Connolly explains what styles guides are and which benefits they bring to designers and developers.
    + **[Atomic Docs](http://atomicdocs.io/)**: Atomic Docs is a styleguide generator and component manager. Atomic Docs is built in PHP. Inspired by Brad Frost's Atomic Design principles.
    + **[Atomic Lab](http://steelydylan.github.io/atomic-lab/)**: Template sharing and coding environment based on atomic design.
+ **Authoring jQuery Plugins**: jQuery is an utility library and a plugin framework. This section collects resources about creating such plugins.
    + **[Advanced Plugin Concepts](http://learn.jquery.com/plugins/advanced-plugin-concepts/)**: A collection of best practices for jQuery plugin authoring.
    + **[How to Create a Basic Plugin](http://learn.jquery.com/plugins/basic-plugin-creation/)**: The article describes basic plugin creation and provides a simple boilerplate.
    + **[Signs of a poorly written jQuery plugin](https://remysharp.com/2010/06/03/signs-of-a-poorly-written-jquery-plugin)**: Collection of jQuery plugin antipatterns.
    + **[The Ultimate Guide to Writing jQuery Plugins](https://websanova.com/blog/jquery/the-ultimate-guide-to-writing-jquery-plugins)**: A comprehensive guide on how to develop jQuery plugins including a simple boilerplate.
    + **[Writing Stateful Plugins with the jQuery UI Widget Factory](http://learn.jquery.com/plugins/stateful-plugins-with-widget-factory/)**: The article demonstrates the capabilities of the Widget Factory by building a simple progress bar plugin.
    + **[jQuery Boilerplate](https://github.com/jquery-boilerplate/jquery-boilerplate)**: This project won't seek to provide a perfect solution to every possible pattern, but will attempt to cover a simple template for beginners and above.
    + **[jQuery Plugin Patterns](https://github.com/jquery-boilerplate/jquery-patterns)**: This project won't seek to provide implementations for every possible pattern, but will attempt to cover popular patterns developers often use in the wild.
+ **[Block Element Modifier (BEM)](https://en.bem.info/method/)**: Methodology aimed at achieving fast to develop long-lived projects, team scalability, and code reuse.
    + **[A New Front-End Methodology: BEM](http://www.smashingmagazine.com/2012/04/a-new-front-end-methodology-bem/)**: An introduction by Varvara Stepanova at SmashingMagazine.
    + **[An Introduction to the BEM Methodology](http://webdesign.tutsplus.com/articles/an-introduction-to-the-bem-methodology--cms-19403)**: General introduction article on tutsplus.
    + **[BEM 101](https://css-tricks.com/bem-101/)**: A collaborative post by Joe Richardson, Robin Rendle, and CSS-Tricks staff giving an introduction to BEM with some good examples.
    + **[BEM I (finally) understand](https://m.alphasights.com/bem-i-finally-understand-b0c74815d5b0)**: In this article Andrei Popa will focus on the basics of BEM and how to approach simple to complex anatomies.
    + **[Battling BEM (Extended Edition): 10 Common Problems And How To Avoid Them](https://www.smashingmagazine.com/2016/06/battling-bem-extended-edition-common-problems-and-how-to-avoid-them/)**: This article aims to be useful for people who are already BEM enthusiasts and wish to use it more effectively or people who are curious to learn more about it.
    + **[Block, Element, Modifying Your JavaScript Components](https://medium.com/seek-ui-engineering/block-element-modifying-your-javascript-components-d7f99fcab52b)**: Mark Dalgleish is discussing how to organize React code with BEM and build everything with Webpack.
    + **[Emmet filter for BEM](http://docs.emmet.io/filters/bem/)**: If you’re writing your HTML and CSS code in OOCSS-style, Yandex’s BEM style specifically, you will like this filter. It provides some aliases and automatic insertions of common block and element names in classes.
    + **[Fifty Shades of BEM](http://blog.kaelig.fr/post/48196348743/fifty-shades-of-bem)**: Article describes different flavors of BEM.
    + **[How We Use BEM to Modularise Our CSS](https://m.alphasights.com/how-we-use-bem-to-modularise-our-css-82a0c39463b0)**: Andrei Popa describes the challenges, AlphaSights team had, implementing BEM in their projects.
    + **[Introduction To BEM Methodology (Toptal)](https://www.toptal.com/css/introduction-to-bem-methodology)**: General introduction to BEM methodology and platform.
    + **[MindBEMding – getting your head ’round BEM syntax](http://csswizardry.com/2013/01/mindbemding-getting-your-head-round-bem-syntax/)**: Article on csswizardry explaining the BEM syntax for CSS classes.
    + **[Pobem](https://github.com/bem-contrib/pobem)**: PostCSS plugin for BEM syntax.
    + **[Support for BEM modules in Sass 3.3](http://mikefowler.me/2013/10/17/support-for-bem-modules-sass-3.3/)**: The next major release of Sass is poised for release and with it comes real support for BEM-style modules...
    + **[To BEM or not to BEM](http://www.didoo.net/to-bem-or-not-to-bem/)**: A series of interviews on BEM methodology.
+ **[Cycle.js](http://cycle.js.org/)**: A functional and reactive JavaScript framework that solves the cyclic dependency of Observables which emerge during dialogues (mutual observations) between the Human and the Computer.
    + **[Async Driver](https://github.com/whitecolor/cycle-async-driver)**: Higher order factory for creating cycle.js async request based drivers. Allows you almost completely eliminate boilerplate code for this kind of drivers.
    + **[Cycle.js Was Built to Solve Problems](https://www.youtube.com/watch?v=Rj8ZTRVka4E)**: In this video André Staltz shows how Cycle.js has a practical purpose, meant to solve problems your customers/business may relate to.
    + **[Cycle.js and Functional Reactive User Interfaces](https://www.youtube.com/watch?v=uNZnftSksYg)**: In this talk we will discover how Cycle.js is purely reactive and functional, and why it's an interesting alternative to React.
    + **[Draw Cycle](https://glebbahmutov.com/draw-cycle/)**: Simple Cycle.js program visualized
    + **[Drivers](http://cycle.js.org/drivers.html)**: Drivers are functions that listen to Observable sinks (their input), perform imperative side effects, and may return Observable sources (their output).
        + **[Animation](https://github.com/Widdershin/cycle-animation-driver)**: A Cycle driver for requestAnimationFrame.
        + **[Audio Graph Driver](https://github.com/benji6/cycle-audio-graph)**: Audio graph driver for Cycle.js based on virtual-audio-graph.
        + **[Cookie](https://github.com/10clouds/cyclejs-cookie)**: Cycle.js Cookie Driver, based on cookie_js library.
        + **[DOM](https://github.com/cyclejs/dom)**: The standard DOM Driver for Cycle.js based on virtual-dom, and other helpers.
        + **[Fetch](https://github.com/secobarbital/cycle-fetch-driver)**: A Cycle.js Driver for making HTTP requests, using the Fetch API.
        + **[Fetcher](https://github.com/r7kamura/cycle-fetcher-driver)**: A Cycle.js Driver for making HTTP requests using stackable-fetcher.
        + **[Firebase](https://github.com/dralletje/cycle-firebase)**: Thin layer around the firebase javascript API that allows you to query and declaratively update your favorite real-time database.
        + **[HTTP](https://github.com/cyclejs/http)**: A Cycle.js Driver for making HTTP requests, based on superagent.
        + **[Hammer.js](https://github.com/CyclicMaterials/cycle-hammer-driver)**: The driver incorporates the Hammer.js gesture library.
        + **[History](https://github.com/cyclejs/history)**: Cycle.js URL Driver based on the rackt/history library.
        + **[Keys](https://github.com/raquelxmoss/cycle-keys)**: A Cycle.js driver for keyboard events.
        + **[Mongoose.js](https://github.com/whitecolor/cycle-mongoose/)**: A driver for using Mongoose with Cycle JS. Accepts both, write and read operations.
        + **[Notification](https://github.com/cyclejs/cycle-notification-driver)**: A Cycle.js Driver for showing and responding to HTML5 Notifications.
        + **[Router](https://github.com/TylorS/cycle-router)**: A router built from the ground up with Cycle.js in mind. Stands on the shoulders of battle-tested libraries switch-path for route matching and rackt/history for dealing with the History API.
        + **[Router5](https://github.com/axefrog/cycle-router5)**: A source/sink router driver for Cycle.js, based on router5.
        + **[Server-Sent Events](https://github.com/jessaustin/cycle-sse-driver)**: Cycle.js driver for Server-Sent Events (SSE), a browser feature also known as EventSource. Server-Sent Events allow the server to continuously update the page with new events, without resorting to hacks like long-polling.
        + **[Snabbdom](https://github.com/TylorS/cycle-snabbdom)**: Alternative DOM driver utilizing the snabbdom library.
        + **[Socket.IO](https://github.com/cgeorg/cycle-socket.io)**: A Cycle driver for applications using Socket.IO
        + **[Storage](https://github.com/cyclejs/storage)**: A Cycle.js Driver for using localStorage and sessionStorage in the browser.
    + **Example Projects**: Example applications built with Cycle.js
        + **[Cycle.js Examples](https://github.com/cyclejs/examples)**: Browse and learn from examples of small Cycle.js apps using Core, DOM Driver, HTML Driver, HTTP Driver, JSONP Driver, and others.
        + **[RX Marbles](https://github.com/staltz/rxmarbles)**: Interactive diagrams of Rx Observables.
        + **[TODO: Minimum Viable Pizza](https://github.com/cgeorg/todomvp)**: Minimum Viable Pizza implemented with Cycle.js
        + **[Tricycle](https://github.com/Widdershin/tricycle)**: A scratchpad for trying out Cycle.js.
    + **[Intro to Functional Reactive Programming with Cycle.js](https://www.youtube.com/watch?v=6_ETUyh0tns)**: Nick Johnstone gives an introduction to developing with Cycle.js in this video presentation.
    + **[Learning How to Ride: an Introduction to Cycle.js](https://www.youtube.com/watch?v=31URmaeNHSs)**: In this talk, Fernando Macias Pereznieto introduces us to the good, the bad, and the beautiful of using Cycle.js, whether you are a complete beginner or an experienced JS ninja.
    + **[Motorcycle.js](https://github.com/motorcyclejs/core)**: This is a sister project that will continue to evolve and grow alongside Cycle.js for the foreseeable future. The primary focus of this project is to tune it for performance as much as possible.
        + **[Most](https://github.com/cujojs/most)**: Monadic reactive streams with high performance.
    + **[Plug and Play All Your Observable Streams With Cycle.js](https://medium.com/@fkrautwald/plug-and-play-all-your-observable-streams-with-cycle-js-e543fc287872)**: Frederik Krautwald explains the principles behind Cycle.js, it's inner workings and how to use it to create a simple program with drivers.
    + **[Tricycle](https://github.com/Widdershin/tricycle)**: A scratchpad for trying out Cycle.js.
    + **[What Developers Need to Know about MVI (Model-View-Intent)](http://thenewstack.io/developers-need-know-mvi-model-view-intent/)**: The article explains the general MVI pattern and how it relates to React, Reactive Programming and Cycle.js
+ **[Polymer Project](https://www.polymer-project.org/1.0/docs/devguide/feature-overview.html)**: The Polymer library is designed to make it easier and faster for developers to create great, reusable components for the modern web.
    + **[Building web components using ES6 classes](https://www.polymer-project.org/1.0/articles/es6.html)**: Web components evolve markup into something that’s meaningful, maintainable, and highly modular. Thanks to these new API primitives, not only do we have improved ergonomics when building apps, but we gain better overall structure, design, and reusability.
    + **[Developing Front-End Microservices](https://technologyconversations.com/2015/08/09/developing-front-end-microservices-with-polymer-web-components-and-test-driven-development-part-15-the-first-component/)**: In this article series we’ll go through Web Components development in context of microservices.
    + **[Lazy Loading of Pages](https://github.com/TimvdLippe/iron-lazy-pages)**: iron-lazy-pages is a Polymer component which allows to load pages on demand.
    + **[ShadowDOM Visualizer](http://html5-demos.appspot.com/shadowdom-visualizer)**: This tools allows you to visualize how Shadow DOM renders in the browser.
    + **[Thinking in Polymer (The Polymer Summit 2015)](https://www.youtube.com/watch?v=ZDjiUmx51y8)**: Kevin Schaaf explains how to employ data binding and composition to build complex application using only Polymer.
    + **[Unidirectional Dataflow Architecture with Polymer + RxJS + Immutable Data](https://medium.com/@richardanaya/unidirectional-data-architecture-with-polymer-rxjs-immutable-data-c689386ee998)**: Richard Anaya describes how to combine Polymer, RxJS and Freezer to implement a unidirectional data flow architecture.
    + **[Using Elements](https://elements.polymer-project.org/guides/using-elements)**: This guide describes how to install and use standalone Polymer components in an existing project.
    + **[Using Polymer with Flux and a Global App State](http://paulusschoutsen.nl/blog/2015/07/using-polymer-with-flux-and-a-global-app-state/)**: Paulus Schoutsen describes his experience integrating Polymer and NuclearJS.
    + **[What is shady DOM?](https://www.polymer-project.org/1.0/articles/shadydom.html)**: On browsers that support shadow DOM, it’s possible to have an element that is rendered with complex DOM, but have that complexity hidden away as implementation detail.
+ **[SMACSS](https://smacss.com/book/)**: SMACSS (pronounced “smacks”) is a way to examine your design process and as a way to fit those rigid frameworks into a flexible thought process. It is an attempt to document a consistent approach to site development when using CSS.
+ **[T3](http://t3js.org/)**: T3 is a minimalist JavaScript framework sponsored by Box Inc. that provides core structure to code.
+ **[The Elm Architecture](http://guide.elm-lang.org/architecture/index.html)**: The Elm Architecture is a simple pattern for infinitely nestable components. It is great for modularity, code reuse, and testing.
+ **[TodoMVC](http://todomvc.com/)**: A project which offers the same Todo application implemented using MV* concepts in most of the popular JavaScript MV* frameworks of today.


------------------

# License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

Please provide a link back to this repository. This is not necessary for GitHub forks.