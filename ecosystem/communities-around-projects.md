# Communities Around Projects

**Context: [frontend-dev-bookmarks](../README.md) / Ecosystem**

Successful open source projects attract many developers who produce plugins, libraries, tutorials and other resources. This section collects such resources.

[![frontend.directory](https://img.shields.io/badge/frontend-directory-blue.svg?style=flat-square)](http://frontend.directory/)
[![PayPal](https://img.shields.io/badge/donate-PayPal-00457c.svg?style=flat-square&maxAge=2592000)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=4FAGPMANWRVJJ)
[![Beerpay](https://beerpay.io/dypsilon/frontend-dev-bookmarks/badge.svg?style=flat-square)](https://beerpay.io/dypsilon/frontend-dev-bookmarks)
[![Flattr](https://img.shields.io/badge/donate-Flattr-88b058.svg?style=flat-square&maxAge=2592000)](https://flattr.com/submit/auto?fid=3nlo5p&url=https%3A%2F%2Fgithub.com%2Fdypsilon%2Ffrontend-dev-bookmarks)
[![Gitter](https://img.shields.io/gitter/room/dypsilon/frontend-dev-bookmarks.svg?style=flat-square&maxAge=2592000)](https://gitter.im/dypsilon/frontend-dev-bookmarks)
[![Twitter](https://img.shields.io/badge/follow-twitter-55acee.svg?style=flat-square)](https://twitter.com/FrontendDir)

-----------------------------------------

+ **[Angular](https://angularjs.org/)**: AngularJS is a web application framework trying to address many of the challenges encountered in developing single-page applications.
    + **[Angular 2 ESNext Starter](https://github.com/blacksonic/angular2-esnext-starter)**: This repo stands as a starting point for those who try Angular 2 in Javascript. It shows techniques how easy development can be also without Typescript.
    + **[How to Prevent Name Collisions in Angular 2 Providers](http://blog.thoughtram.io/angular/2016/05/23/opaque-tokens-in-angular-2.html)**: Opaque tokens are distinguishable and prevent us from running into naming collisions. Whenever we create a token that is not a type, OpaqueToken should be used.
    + **[Ng-Newsletter](http://www.ng-newsletter.com/)**: The free, weekly newsletter of the best AngularJS content on the web.
    + **[PrimeNG](http://www.primefaces.org/primeng/)**: PrimeNG is a collection of rich UI components for AngularJS2. PrimeNG is a sibling of the popular JavaServer Faces Component Suite, PrimeFaces.
+ **[Backbone.js](http://backbonejs.org/)**: Backbone supplies structure to JavaScript-heavy applications by providing models, collections, views with declarative event handling, and connects it all to your existing application over a RESTful JSON interface.
+ **[Bootstrap](http://getbootstrap.com/)**: Bootstrap is a HTML, CSS, and JS framework for developing responsive, mobile first projects on the web.
    + **[Tree Shaking Bootstrap](https://medium.com/@jacobp/tree-shaking-bootstrap-95d6301f61a9)**: Jacob Parker describes how to include only those parts of Bootstrap you are really using on your website by leveraging CSS modules and ES6 modules.
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
+ **[Dojo Toolkit](http://dojotoolkit.org/)**: A JavaScript toolkit that saves you time and scales with your development process. Provides everything you need to build a Web app. Language utilities, UI components, and more, all in one place, designed to work together perfectly.
+ **[Ember](http://emberjs.com/)**: Ember.js is an open-source JavaScript web framework, based on the MVC pattern. It allows developers to create scalable single-page web applications.
    + **[Router.js (Ember)](https://github.com/tildeio/router.js)**: Router.js is the routing microlib used by Ember.js.
+ **[Foundation](http://foundation.zurb.com/)**: Foundation provides a responsive grid and HTML and CSS UI components, templates, and code snippets, including typography, forms, buttons, navigation and other interface components, as well as optional JavaScript extensions.
+ **[Gulp](http://gulpjs.com/)**: Gulp is a toolkit that helps you automate painful or time-consuming tasks in your development workflow. It's very fast, platform-agnostic and simple.
    + **Articles & Tutorials**: Publications about gulp or step by step guides for setting up and using gulp in a project.
        + **Building with Gulp 3 and 4 (Series)**: Great series of articles about single components and gulp as a whole.
            + **[Part 1: Examples](http://blog.reactandbethankful.com/posts/2015/04/23/building-with-gulp-3-and-4-part-1-examples/)**: Introduction to gulp and gulpfile.js.
            + **[Part 2: Gulp's anatomy](http://blog.reactandbethankful.com/posts/2015/04/23/building-with-gulp-3-and-4-part-2-gulp-anatomy/)**: Orchestrator, Undertaker, Vinyl and Vinyl FS, Gulp Plugins.
            + **[Part 3: Writing transformers](http://blog.reactandbethankful.com/posts/2015/04/28/building-with-gulp-3-and-4-part-3-writing-transformers/)**: Using map-stream, though2 and event-stream.
            + **[Part 4: Incremental builds](http://blog.reactandbethankful.com/posts/2015/05/01/building-with-gulp-4-part-4-incremental-builds/)**: Building files which changed since last run and caching.
            + **[Part 5: Caveats](http://blog.reactandbethankful.com/posts/2015/05/05/building-with-gulp-part-5-caveats/)**: Error management in Gulp 3 and "MANY:1 disguised as a 1:1" problem.
        + **[The vision, history, and future of the project (Apr. 2014)](https://medium.com/@contrahacks/gulp-3828e8126466)**: The article talks about Streams, Vinyl, Vinyl Adapters, Orchestrator and Error Management in Gulp 4.
        + **[Why Gulp might not be the Answer](http://scm.io/blog/hack/2014/07/why-gulp-might-not-be-the-answer/)**: ... there is still a conceptual problem that Gulp has yet to address. Many build steps are not 1:1 (one file in, one file out) but rather n:1 or 1:n.
    + **CSS**: Gulp plugins for working with CSS files.
        + **[gulp-clean-css](https://github.com/scniro/gulp-clean-css)**: gulp plugin to minify CSS, using clean-css.
        + **[gulp-cssnano](https://www.npmjs.com/package/gulp-cssnano)**: Minify CSS with cssnano.
    + **Concatenation**: Plugins for file concatenation. For example bundling CSS or JavaScript files.
        + **[gulp-concat](https://www.npmjs.com/package/gulp-concat)**: This plugin will concat files by your operating systems newLine. It will take the base directory from the first file that passes through it.
        + **[gulp-group-concat](https://www.npmjs.com/package/gulp-group-concat)**: Concats groups of files into a smaller number of files
    + **Deployment**: Plugins for pushing built files into production.
        + **[gulp-tar](https://github.com/sindresorhus/gulp-tar)**: Create tarball from files.
        + **[vinyl-ftp](https://github.com/morris/vinyl-ftp)**: Blazing fast vinyl adapter for FTP.
        + **[vinyl-s3](https://github.com/izaakschroeder/vinyl-s3)**: Use S3 as a source or destination of vinyl files.
    + **Ecosystem**: The network of developers and plugins around gulp.
        + **[@sindresorhus plugins](https://github.com/search?q=%40sindresorhus+gulp-)**: A collection of plugins by Sindre Sorhus.
        + **[Gulp Friendly NPM Packages](https://www.npmjs.com/browse/keyword/gulpfriendly)**: Normal node packages that work with gulp.
    + **Filters**: Plugins for filtering files in a vinyl stream.
        + **[gulp-cache](https://www.npmjs.com/package/gulp-cache)**: A temp file based caching proxy task for gulp.
        + **[gulp-cached](https://www.npmjs.com/package/gulp-cached)**: A simple in-memory file cache for gulp.
        + **[gulp-changed](https://github.com/sindresorhus/gulp-changed)**: Only pass through changed files.
        + **[gulp-filter](https://www.npmjs.com/package/gulp-filter)**: Filter files in a vinyl stream.
        + **[gulp-newer](https://github.com/tschaub/gulp-newer)**: Pass through newer source files only.
        + **[gulp-remember](https://github.com/ahaurw01/gulp-remember)**: A plugin for gulp that remembers and recalls files passed through it.
        + **[vinyl-diff](https://www.npmjs.com/package/vinyl-diff)**: This library allows you to perform diffs between streams of vinyl.
    + **Images**: Plugins for working with images.
        + **[gulp-imagemin](https://github.com/sindresorhus/gulp-imagemin)**: Minify PNG, JPEG, GIF and SVG images.
        + **[gulp-webp](https://github.com/sindresorhus/gulp-webp)**: Convert PNG, JPEG, TIFF images to WebP.
    + **JavaScript**: Module loaders, minifiers and other tools for working with JavaScript files.
        + **[gulp-pure-cjs](https://www.npmjs.com/package/gulp-pure-cjs)**: Gulp plugin for Pure CommonJS builder.
        + **[gulp-uglify](https://www.npmjs.com/package/gulp-uglify)**: Minify files with UglifyJS.
        + **[yoloader](https://www.npmjs.com/package/yoloader)**: A CommonJS module loader implementation. It provides tools to bundle a CommonJS based project and to load such bundles.
    + **SourceMaps**: A source map provides a way of mapping code within a compressed file back to it’s original position in a source file.
        + **[Plugins with gulp sourcemaps support](https://github.com/floridoo/gulp-sourcemaps/wiki/Plugins-with-gulp-sourcemaps-support)**: A list of plugins which support gulp-sourcemaps.
        + **[gulp-sourcemaps](https://github.com/floridoo/gulp-sourcemaps)**: Source map support for Gulp.js
        + **[vinyl-sourcemaps-apply](https://www.npmjs.com/package/vinyl-sourcemaps-apply)**: Apply a source map to a vinyl file, merging it with preexisting source maps.
    + **Utility**: Tools and parts for building gulp plugins.
        + **[gulp-count](https://www.npmjs.com/package/gulp-count)**: Count files in a vinyl stream.
        + **[gulp-debug](https://www.npmjs.com/package/gulp-debug)**: Debug vinyl file streams to see what files are run through your gulp pipeline.
        + **[gulp-size](https://github.com/sindresorhus/gulp-size)**: Logs out the total size of files in the stream and optionally the individual file-sizes.
        + **[lazypipe](https://www.npmjs.com/package/lazypipe)**: Lazypipe allows you to create an immutable, lazily-initialized pipeline. It's designed to be used in an environment where you want to reuse partial pipelines, such as with gulp.
        + **[map-stream](https://github.com/dominictarr/map-stream)**: Create a through stream from an asyncronous function.
    + **[Vinyl](https://github.com/gulpjs/vinyl)**: Vinyl is a very simple metadata object that describes a file.
        + **[gulp-chmod](https://github.com/sindresorhus/gulp-chmod)**: Change permissions of Vinyl files.
        + **[gulp-rename](https://github.com/hparra/gulp-rename)**: A plugin to rename files easily.
        + **[mem-fs](https://www.npmjs.com/package/mem-fs)**: Simple in-memory vinyl file store.
        + **[vinyl-ast](https://www.npmjs.com/package/vinyl-ast)**: Parse-once and generate-once AST tool bridge for Gulp plugins.
        + **[vinyl-buffer](https://www.npmjs.com/package/vinyl-buffer)**: Creates a transform stream that takes vinyl files as input, and outputs buffered (isStream() === false) vinyl files as output.
        + **[vinyl-file](https://www.npmjs.com/package/vinyl-file)**: Create a vinyl file from an actual file.
        + **[vinyl-fs](https://github.com/wearefractal/vinyl-fs)**: Vinyl adapter for the file system.
        + **[vinyl-fs-fake](https://www.npmjs.com/package/vinyl-fs-fake)**: A vinyl adapter that extends vinyl-fs to allow for easy debugging by passing in virtual files instead of globs, and calling a function instead of writing.
        + **[vinyl-git](https://www.npmjs.com/package/vinyl-git)**: Vinyl adapter for git.
        + **[vinyl-map](https://github.com/hughsk/vinyl-map)**: Map vinyl files' contents as strings, so you can easily use existing code without needing yet another gulp plugin!
        + **[vinyl-paths](https://www.npmjs.com/package/vinyl-paths)**: Get the file paths in a vinyl stream.
        + **[vinyl-source-buffer](https://www.npmjs.com/package/vinyl-source-buffer)**: Convert a text stream into a vinyl pipeline whose content is a buffer.
        + **[vinyl-source-stream](https://www.npmjs.com/package/vinyl-source-stream)**: Use conventional text streams at the start of your gulp or vinyl pipelines, making for nicer interoperability with the existing npm stream.
        + **[vinyl-to-stream](https://www.npmjs.com/package/vinyl-to-stream)**: Convert a vinyl stream to a text stream.
        + **[vinyl-transform](https://www.npmjs.com/package/vinyl-transform)**: Wraps standard text transform streams so you can write fewer gulp plugins. Fulfills a similar use case to vinyl-map and vinyl-source-stream.
+ **[Meteor](https://www.meteor.com/)**: Meteor is a full-stack JavaScript platform for developing modern web and mobile applications. Meteor includes a key set of technologies for building connected-client reactive applications, a build tool, and a curated set of packages.
+ **[React](http://facebook.github.io/react/)**: React is a JavaScript library for creating user interfaces. Many people choose to think of React as the V in MVC. We built React to solve one problem: building large applications with data that changes over time.
    + **[3 Lightweight React Alternatives](https://www.sitepoint.com/react-alternatives-preact-virtualdom-deku/)**: Dan Prince explores Preact, VirtualDom & Deku.
    + **[Block, Element, Modifying Your JavaScript Components](https://medium.com/seek-ui-engineering/block-element-modifying-your-javascript-components-d7f99fcab52b)**: Mark Dalgleish is discussing how to organize React code with BEM and build everything with Webpack.
    + **[CSS Modules To The Rescue.jsx](https://medium.com/@kadmil/css-modules-to-the-rescue-jsx-ded2db874d34)**: If you use react-like templates/components, use webpack CSS loader to enable CSS Modules and forget about global CSS problems.
    + **[Find Your Perfect React Starter Project](http://andrewhfarmer.com/starter-project/)**: A simple search engine for React boilerplates with the ability to pick the ingredients.
    + **[Getting Started with TDD in React](https://semaphoreci.com/community/tutorials/getting-started-with-tdd-in-react)**: Learn how to test React components using a TDD approach with minimal setup, while learning exactly what to test and how to avoid common pitfalls.
    + **[Getting to Grips with React (as an Angular developer)](https://daveceddia.com/to-react-from-angular/)**: In a series of posts Dave Ceddia tries to help you apply your hard-won knowledge of “Angularisms” to React.
    + **[How we use the Flux architecture in Delve](https://medium.com/@delveeng/how-we-use-the-flux-architecture-in-delve-effc551f8fbc)**: Øystein Hallaråker describes how Delve utilizes the Flux application architecture.
    + **[JSX Transform](https://github.com/alexmingoia/jsx-transform)**: JSX transpiler. A standard and configurable implementation of JSX decoupled from React.
    + **[Model-View-Intent with React and RxJS](https://satishchilukuri.com/blog/entry/model-view-intent-with-react-and-rxjs)**: Satish Chilukuri shows an example implementation of MVI pattern with React.
    + **[React App](https://github.com/kriasoft/react-app)**: React App is a small library powered by React, Universal Router and History that handles routing, navigation and rendering logic in isomorphic (universal) and single-page applications.
    + **[React Components, Elements, and Instances](https://medium.com/@dan_abramov/react-components-elements-and-instances-90800811f8ca#.9208ahtfb)**: Dan Abramov explains the Virtual DOM dictionary in React.
    + **[React Demystified](http://blog.reverberate.org/2014/02/react-demystified.html)**: This article is an attempt to explain the core ideas behind React.js and Virtual DOM.
    + **[React Native for Web](https://github.com/necolas/react-native-web)**: This project allows components built upon React Native to be run on the Web, and it manages all component styling out-of-the-box.
    + **[React Starter Kit](https://www.reactstarterkit.com/)**: Isomorphic web app boilerplate including Node.js, Express, GraphQL, React.js, Babel 6, PostCSS, Webpack, Browsersync.
    + **[React vs Incremental DOM vs Glimmer](https://auth0.com/blog/2015/11/20/face-off-virtual-dom-vs-incremental-dom-vs-glimmer/)**: In this post we will explore three technologies to build dynamic DOMs. We will also run benchmarks and find out which one is faster.
    + **[React: Rethinking best practices (2013)](https://www.youtube.com/watch?v=x7cQ3mrcKaY)**: A video introduction to React by Pete Hunt.
    + **[ReactPerfTool](https://github.com/RamonGebben/react-perf-tool)**: ReactPerfTool tries to give you a more visual way of debugging performance of your React application. It does this by using the addons delivered by the React team and community to get measurements and visualize this using graphs.
    + **[Redux Form](https://github.com/erikras/redux-form)**: A Higher Order Component using react-redux to keep form state in a Redux store.
    + **[Removing User Interface Complexity, or Why React is Awesome](http://jlongster.com/Removing-User-Interface-Complexity,-or-Why-React-is-Awesome)**: In this post James Long tries not to evangelize React specifically, but to explain why its technique is profound.
    + **[Retractor](https://github.com/LiquidLabsGmbH/retractor)**: Retractor exposes the internals of a React application for end-to-end testing purposes. This allows you to select DOM nodes based on the name of the React Component that rendered the node as well as its state or properties.
    + **[Taming the React Setup](http://developer.telerik.com/featured/taming-react-setup/)**: Cody Lindley lays out seven React setups in this article and explains the relation of React to BYOA (Bring Your Own Architecture) approach.
    + **[The Redux Ecosystem](https://medium.com/@denisraslov/the-redux-ecosystem-539c630ec521)**: Let’s take a look at most of the features that you’ll have to deal with when the time comes, — and where React & Redux themselves can’t help you.
    + **[Tutorial: Cloning Yelp](https://www.fullstackreact.com/articles/react-tutorial-cloning-yelp/)**: This post will guide you through building a full React app, even with little to no experience in the framework. We are going to build a Yelp clone in React.
    + **[What Developers Need to Know about MVI (Model-View-Intent)](http://thenewstack.io/developers-need-know-mvi-model-view-intent/)**: The article explains the general MVI pattern and how it relates to React, Reactive Programming and Cycle.js
    + **[Why Did You Update?](https://github.com/garbles/why-did-you-update)**: A function that monkey patches React and notifies you in the console when potentially unnecessary re-renders occur.
    + **[Why did we build React?](http://facebook.github.io/react/blog/2013/06/05/why-react.html)**: Pete Hunt tries to explain why Facebook devs built React in the first place.
+ **[Yeoman](http://yeoman.io/)**: Yeoman helps you to kickstart new projects, prescribing best practices and tools to help you stay productive. It provides a generator ecosystem.
+ **[jQuery](https://jquery.com/)**: jQuery is a fast, small, and feature-rich JavaScript library. It makes things like HTML document traversal and manipulation, event handling, animation, and Ajax much simpler.
    + **Alternatives**: Other libraries which intend to replace jQuery in one way or another.
        + **[Minified.js](http://minifiedjs.com/)**: Minified.js is a client-side JavaScript library that's both powerful and small. It offers jQuery-like features and utility functions with a single, consistent API.
        + **[Zepto.js](http://zeptojs.com/)**: Zepto is a minimalist JavaScript library for modern browsers with a largely jQuery-compatible API.
        + **[chibi](https://github.com/kylebarrow/chibi)**: Chibi focuses on just the essentials, melted down and mixed with optimisation rainbows to create a really light micro-library that allows you to do awesome things.
    + **Authoring jQuery Plugins**: jQuery is an utility library and a plugin framework. This section collects resources about creating such plugins.
        + **[Advanced Plugin Concepts](http://learn.jquery.com/plugins/advanced-plugin-concepts/)**: A collection of best practices for jQuery plugin authoring.
        + **[How to Create a Basic Plugin](http://learn.jquery.com/plugins/basic-plugin-creation/)**: The article describes basic plugin creation and provides a simple boilerplate.
        + **[Signs of a poorly written jQuery plugin](https://remysharp.com/2010/06/03/signs-of-a-poorly-written-jquery-plugin)**: Collection of jQuery plugin antipatterns.
        + **[The Ultimate Guide to Writing jQuery Plugins](https://websanova.com/blog/jquery/the-ultimate-guide-to-writing-jquery-plugins)**: A comprehensive guide on how to develop jQuery plugins including a simple boilerplate.
        + **[Writing Stateful Plugins with the jQuery UI Widget Factory](http://learn.jquery.com/plugins/stateful-plugins-with-widget-factory/)**: The article demonstrates the capabilities of the Widget Factory by building a simple progress bar plugin.
        + **[jQuery Boilerplate](https://github.com/jquery-boilerplate/jquery-boilerplate)**: This project won't seek to provide a perfect solution to every possible pattern, but will attempt to cover a simple template for beginners and above.
        + **[jQuery Plugin Patterns](https://github.com/jquery-boilerplate/jquery-patterns)**: This project won't seek to provide implementations for every possible pattern, but will attempt to cover popular patterns developers often use in the wild.
    + **[Pragmatic jQuery Style](https://github.com/yuanyan/pragmatic-jquery)**: Coding guidelines for working with jQuery.
    + **[jQuery Fundamentals](http://jqfundamentals.com/)**: A guide to the basics of jQuery including a built-in editor for examples.
    + **[jQuery UI](http://jqueryui.com/)**: jQuery UI is a curated set of user interface interactions, effects, widgets, and themes built on top of the jQuery JavaScript Library.
        + **[Learning jQuery UI](http://learn.jquery.com/jquery-ui/)**: Series of articles about jQuery UI on learn.jquery.com.


------------------

# License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

Please provide a link back to this repository. This is not necessary for GitHub forks.