# JavaScript Tools

**Context: [frontend-dev-bookmarks](../README.md) / Workflow**

Tools for static analysis, pre and post processing of JavaScript files.

[![frontend.directory](https://img.shields.io/badge/frontend-directory-blue.svg?style=flat-square)](http://frontend.directory/)
[![Gitter](https://img.shields.io/gitter/room/dypsilon/frontend-dev-bookmarks.svg?style=flat-square&maxAge=2592000)](https://gitter.im/dypsilon/frontend-dev-bookmarks)
[![Twitter](https://img.shields.io/badge/follow-twitter-55acee.svg?style=flat-square)](https://twitter.com/FrontendDir)

-----------------------------------------
+ **[Babel](https://babeljs.io/)**: Babel is a generic multi-purpose compiler for JavaScript. Using Babel you can use (and create) the next generation of JavaScript, as well as the next generation of JavaScript tooling.
    + **[Full-Stack Redux Tutorial](http://teropa.info/blog/2015/09/10/full-stack-redux-tutorial.html)**: We will go through all the steps of constructing a Node+Redux backend and a React+Redux frontend for a real-world application, using test-first development.
    + **[JavaScript Transpilers: What They Are & Why We Need Them](https://scotch.io/tutorials/javascript-transpilers-what-they-are-why-we-need-them)**: Learn how to use Babel, and what has to do with the future of JavaScript.
+ **[Closure Compiler](https://developers.google.com/closure/compiler/)**: The Closure Compiler parses your JavaScript, analyzes it, removes dead code and rewrites and minimizes what's left. It also checks syntax, variable references, and types, and warns about common JavaScript pitfalls.
+ **[Flow](https://flowtype.org/)**: Flow is a static type checker for JavaScript. It can be used to catch common bugs in JavaScript programs before they run.
+ **[JSCodeshift](https://github.com/facebook/jscodeshift)**: Codemods are tools that assist large-scale, partially automatable codebase refactoring. JSCodeshift is a toolkit for running codemods over multiple JS files.
    + **[Turbocharged JavaScript Refactoring with Codemods](https://medium.com/airbnb-engineering/turbocharged-javascript-refactoring-with-codemods-b0cae8b326b9)**: Joe Lencioni describes how they used codemods to transform a large JavaScript code base at AirBnB
+ **JavaScript Code Linting**: Linting is the process of running a program that will analyse code for potential errors.
    + **[ESLint](http://eslint.org/)**: The pluggable linting utility for JavaScript and JSX.
    + **[JSHint](http://jshint.com/)**: JSHint is a tool for more flexible static analysis of JavaScript programs.
    + **[JSLint](http://jslint.com/)**: JSLint is a tool for detecting errors or problems by static analysis of JavaScript programs.
    + **[JSLint, JSHint and ESLint Error Explanations](http://jslinterrors.com)**: JSLint Error Explanations is designed to help you improve your JavaScript by understanding the sometimes cryptic error messages produced by JSLint, JSHint and ESLint, and teaching you how to avoid such errors.
+ **Module Bundlers and Loaders**: Libraries for bundling JavaScript Modules into one or several files.
    + **[Browserify](http://browserify.org/)**: Browserify lets you require('modules') in the browser by bundling up all of your dependencies.
        + **[Budo](https://github.com/mattdesl/budo)**: A browserify development server, focused on incremental reloading, LiveReload integration (including CSS injection), and other high-level features.
        + **[Watchify](https://www.npmjs.org/package/watchify)**: Watch mode for browserify builds.
    + **[CrapLoader](https://github.com/gregersrygg/crapLoader)**: The goal of crapLoader is to load ads, widgets or any JavaScript code with document.write in it. This library hijacks document.write and delegates the content loaded from each script into the correct position.
    + **[Modules Webmake](https://github.com/medikoo/modules-webmake)**: A CommonJS module bundler similar to Browserify but much faster due to different requirements finder.
    + **[Require.js](http://requirejs.org/)**: RequireJS is a JavaScript file and AMD module loader. It is optimized for in-browser use, but it can be used in other JavaScript environments.
    + **[Require1k](http://stuk.github.io/require1k/)**: CommonJS require for the browser in 1KB, with no build needed.
    + **[Rollup.js](http://rollupjs.org/)**: Rollup is a next-generation JavaScript module bundler. Author your app or library using ES2015 modules, then efficiently bundle them up into a single file for use in browsers and Node.js.
    + **[SystemJS](https://github.com/systemjs/systemjs)**: Universal dynamic module loader - loads ES6 modules, AMD, CommonJS and global scripts in the browser and NodeJS. Works with both Traceur and Babel.
        + **[Modular JavaScript: A Beginners Guide to SystemJS & JSPM](http://www.sitepoint.com/modular-javascript-systemjs-jspm/)**: The combination of jspm and SystemJS provides a unified way of installing and loading dependencies.
    + **[URequire](https://github.com/anodynos/urequire)**: The Ultimate JavaScript Module Builder & Automagical Task Runner.
    + **[Webpack](http://webpack.github.io/)**: Webpack is a module bundler. It takes modules with dependencies and generates static assets representing those modules.
        + **[Block, Element, Modifying Your JavaScript Components](https://medium.com/seek-ui-engineering/block-element-modifying-your-javascript-components-d7f99fcab52b)**: Mark Dalgleish is discussing how to organize React code with BEM and build everything with Webpack.
        + **[Developing with Docker and Webpack](http://dapperdeveloper.com/2016/05/18/developing-with-docker-and-webpack/)**: Chris Harrington explains how to create a development environment with Webpack and Docker to match the production as much as possible.
        + **[Full-Stack Redux Tutorial](http://teropa.info/blog/2015/09/10/full-stack-redux-tutorial.html)**: We will go through all the steps of constructing a Node+Redux backend and a React+Redux frontend for a real-world application, using test-first development.
        + **[How to Set Up Webpack Image Loader](http://www.davidmeents.com/how-to-set-up-webpack-image-loader/)**: This brief tutorial will help you set up an image loader in Webpack.
        + **[The SoundCloud Client in React + Redux](http://www.robinwieruch.de/the-soundcloud-client-in-react-redux/)**: After finishing this step by step tutorial you will be able to author your own React + Redux project with Webpack and Babel.
        + **[Webpack from Apprentice to Master](http://survivejs.com/webpack/)**: The purpose of this guide is to help you get started with Webpack and then go beyond basics.
        + **[WebpackBin](http://www.webpackbin.com/)**: A webpack code sandbox.
        + **[Why I think Webpack is the Right Approach To Build Pipelines](http://devlog.disco.zone/2016/06/01/webpack/)**: Thomas Boyt compares how Grunt, Gulp, Broccoli and Webpack discover dependencies.
+ **[Regenerator](https://github.com/facebook/regenerator)**: This package implements a source transformation that takes the proposed syntax for generators/yield from future versions of JS and spits out efficient JS-of-today (ES5) that behaves the same way.


------------------

# License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

Please provide a link back to this repository. This is not necessary for GitHub forks.