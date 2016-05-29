# Functional Reactive Programming (FRP)

**Context: [frontend-dev-bookmarks](../README.md) / Architecture**

FRP is a programming paradigm for asynchronous dataflow programming using the building blocks of functional programming.

[![frontend.directory](https://img.shields.io/badge/frontend-directory-blue.svg?style=flat-square)](http://frontend.directory/)
[![PayPal](https://img.shields.io/badge/donate-PayPal-00457c.svg?style=flat-square&maxAge=2592000)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=4FAGPMANWRVJJ)
[![Beerpay](https://beerpay.io/dypsilon/frontend-dev-bookmarks/badge.svg?style=flat-square)](https://beerpay.io/dypsilon/frontend-dev-bookmarks)
[![Flattr](https://img.shields.io/badge/donate-Flattr-88b058.svg?style=flat-square&maxAge=2592000)](https://flattr.com/submit/auto?fid=3nlo5p&url=https%3A%2F%2Fgithub.com%2Fdypsilon%2Ffrontend-dev-bookmarks)
[![Gitter](https://img.shields.io/gitter/room/dypsilon/frontend-dev-bookmarks.svg?style=flat-square&maxAge=2592000)](https://gitter.im/dypsilon/frontend-dev-bookmarks)
[![Twitter](https://img.shields.io/badge/follow-twitter-55acee.svg?style=flat-square)](https://twitter.com/FrontendDir)

-----------------------------------------

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
    + **[Tricycle](https://github.com/Widdershin/tricycle)**: A scratchpad for trying out Cycle.js.
    + **[What Developers Need to Know about MVI (Model-View-Intent)](http://thenewstack.io/developers-need-know-mvi-model-view-intent/)**: The article explains the general MVI pattern and how it relates to React, Reactive Programming and Cycle.js
+ **[Cycle.js and Functional Reactive User Interfaces](https://www.youtube.com/watch?v=uNZnftSksYg)**: In this talk we will discover how Cycle.js is purely reactive and functional, and why it's an interesting alternative to React.
+ **Stream Libraries**: Libraries which help you compose asynchronous operations on streams of time-varying values and events.
    + **[Bacon.js](http://baconjs.github.io/)**: A small functional reactive programming lib for JavaScript. Turns your event spaghetti into clean and declarative feng shui bacon, by switching from imperative to functional.
    + **[Kefir.js](https://rpominov.github.io/kefir/)**: Kefir — is a Reactive Programming library for JavaScript inspired by Bacon.js and RxJS, with focus on high performance and low memory usage.
    + **[Most](https://github.com/cujojs/most)**: Monadic reactive streams with high performance.
    + **[Reactive Extensions (RxJS)](https://github.com/Reactive-Extensions/RxJS)**: RxJS is a set of libraries for composing asynchronous and event-based programs using observable sequences and fluent query operators.
        + **[Async JavaScript with Reactive Extensions](https://www.youtube.com/watch?v=XRYN2xt11Ek)**: Jafar Husain explains in this video how Netflix uses the Reactive Extensions (Rx) library to build responsive user experiences that strive to be event-driven, scalable and resilient.
        + **[Learn RX](http://reactivex.io/learnrx/)**: A series of interactive exercises for learning Microsoft's Reactive Extensions (Rx) Library for Javascript.
        + **[Rx Training Games](https://github.com/JulienMoumne/rx-training-games)**: Rx Training Games is a coding playground that can be used to learn and practice Reactive Extensions coding grid-based games
        + **[Rx-Book](http://xgrommx.github.io/rx-book/index.html)**: A complete book about RxJS v.4.0.
        + **[RxMarbles](http://rxmarbles.com/)**: A webapp for experimenting with diagrams of Rx Observables, for learning purposes.
        + **[Transducers with Observable Sequences](https://xgrommx.github.io/rx-book/content/getting_started_with_rxjs/creating_and_querying_observable_sequences/transducers.html)**: A chapter from the RxJS Book describing Transducers.
        + **[Why We Built Xstream](http://staltz.com/why-we-built-xstream.html)**: The authors needed a stream library tailored for Cycle.js. It needs to be “hot” only, small in kB size and it should have only a few and intuitive operators.
    + **[Xstream](https://github.com/staltz/xstream)**: An extremely intuitive, small, and fast functional reactive stream library for JavaScript.
        + **[Why We Built Xstream](http://staltz.com/why-we-built-xstream.html)**: The authors needed a stream library tailored for Cycle.js. It needs to be “hot” only, small in kB size and it should have only a few and intuitive operators.
+ **[The Introduction to Reactive Programming](https://gist.github.com/staltz/868e7e9bc2a7b8c1f754)**: André Staltz provides a complete introduction to the Reactive Programming and RxJS.
+ **[What if the User was a Function?](https://www.youtube.com/watch?v=1zj7M1LnJV4)**: In this video André Staltz talks about the input/output cycle between humans and computers and how to take advantage of this model by using FRP and event streams.


------------------

# License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

Please provide a link back to this repository. This is not necessary for GitHub forks.