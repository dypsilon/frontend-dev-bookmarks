# JavaScript (EcmaScript)

**Context: [frontend-dev-bookmarks](../README.md) / Languages, Protocols, Browser APIs**

JavaScript is a full-fledged dynamic programming language that, when applied to an HTML document, can provide dynamic interactivity on websites. It is defined by ECMAScript standard.

[![frontend.directory](https://img.shields.io/badge/frontend-directory-blue.svg?style=flat-square)](http://frontend.directory/)
[![Gitter](https://img.shields.io/gitter/room/dypsilon/frontend-dev-bookmarks.svg?style=flat-square&maxAge=2592000)](https://gitter.im/dypsilon/frontend-dev-bookmarks)
[![Twitter](https://img.shields.io/badge/follow-twitter-55acee.svg?style=flat-square)](https://twitter.com/FrontendDir)

-----------------------------------------
+ **Control Flow & Error Handling**: Statements, that you can use to incorporate interactivity in your application.
    + **[A Guide to Proper Error Handling in JavaScript](https://www.sitepoint.com/proper-error-handling-javascript/)**: Camilo Reyes describes ways to handle Exceptions and asynchronous errors in JavaScript.
+ **Enhancement Libraries**: Libraries that attempt to improve and enhance the vanilla JavaScript language by providing utility functions.
    + **[Flow](https://flowtype.org/)**: Flow is a static type checker for JavaScript. It can be used to catch common bugs in JavaScript programs before they run.
    + **[Lodash](https://lodash.com/)**: A modern JavaScript utility library delivering modularity, performance, & extras.
    + **[MOUT](http://moutjs.com/)**: MOUT provides many helper methods similar to those found on other languages standard libraries (ie. Python, Ruby, PHP).
    + **[Ramda](http://ramdajs.com/)**: A practical library designed specifically for a functional programming style, one that makes it easy to create functional pipelines, one that never mutates user data.
        + **Practical Ramda - Functional Programming Examples**: Tom MacWright gives some practical examples of Ramda usage.
    + **[RubyJS](http://rubyjs.org/)**: RubyJS is a JavaScript implementation of all methods from Ruby classes like Array, String, Numbers, Time and more.
+ **Functions**: A function is a JavaScript procedure—a set of statements that performs a task or calculates a value.
    + **[Closures explained by Jim Ley](http://jibbering.com/faq/notes/closures/)**: Explanation of closures in JavaScript.
    + **[Let’s Learn JavaScript Closures](https://medium.freecodecamp.com/lets-learn-javascript-closures-66feb44f6a44)**: So this post will be dedicated to the nuts and bolts of how and why closures work the way they do.
    + **[MDN Guide Chapter about Functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions)**: Defining functions, scope, closures, arguments, parameters, arrow functions and predefined functions.
    + **[MDN Reference for Functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions)**: Defining functions, arguments, parameters, methods, block-level functions and browser compatibility.
+ **Generators**: Generators allow you to define an iterative algorithm by writing a single function which can maintain its own state.
    + **[A Closer Look at Generators Without Promises](http://jlongster.com/A-Closer-Look-at-Generators-Without-Promises)**: Author looks at libraries for asynchronous programming with generators but without promises.
    + **[A Study on Solving Callbacks with JavaScript Generators](http://jlongster.com/A-Study-on-Solving-Callbacks-with-JavaScript-Generators)**: This article describes how Generators help fight callback hell.
    + **[Callbacks vs Coroutines](https://medium.com/@tjholowaychuk/callbacks-vs-coroutines-174f1fe66127)**: In this post TJ Holowaychuk goes through hist experiences with coroutines and why he thinks they’re a great tool.
    + **[Coroutine Event Loops in Javascript](https://x.st/javascript-coroutines/)**: An intriguing use of coroutines is to implement event loops as an alternative to callback functions. This is particularly relevant to Javascript, where the use of callbacks is pervasive.
    + **[Coroutine vs Continuation vs Generator](http://stackoverflow.com/questions/715758/coroutine-vs-continuation-vs-generator)**: StackOverflow Discussion about the difference between Couroutines, Continuations and Generators.
    + **[Regenerator](https://github.com/facebook/regenerator)**: This package implements a source transformation that takes the proposed syntax for generators/yield from future versions of JS and spits out efficient JS-of-today (ES5) that behaves the same way.
+ **Grammar and Types**: JavaScript's basic grammar, variable declarations, data types scope, hoisting and literals.
    + **[Detailed Overview of Well-Known Symbols](https://rainsoft.io/detailed-overview-of-well-known-symbols/)**: Well-known symbols are used by built-in JavaScript algorithms. This article guides through the list of well-known symbols and explains how to use them comfortable in your code.
    + **[Grammar and Types Chapter on the MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Grammar_and_types)**: This chapter discusses JavaScript's basic grammar, variable declarations, data types and literals.
    + **[Variable Hoisting Explained](http://bytearcher.com/articles/variable-hoisting-explained/)**: The author explains how hoisting works in JavaScript including variable declarations and ES6 let operator.
    + **[Variables Lifecycle: Why Let is not Hoisted](https://rainsoft.io/variables-lifecycle-and-why-let-is-not-hoisted/)**: ES2015 provides a different and improved mechanism for let. It demands stricter variable declaration practices and as result better code quality. Let's dive into more details about this process.
+ **JS Coding Conventions**: Coding conventions are a set of guidelines for a specific programming language that recommend programming style, practices and methods for each aspect of a piece program written in this language.
    + **[Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript)**: A reasonable approach to JavaScript by Airbnb.
    + **[Google JavaScript Style Guide](https://google.github.io/styleguide/javascriptguide.xml)**: JavaScript is the main client-side scripting language used by many of Google's open-source projects. This style guide is a list of dos and don'ts for JavaScript programs.
    + **[Idiomatic.js](https://github.com/rwaldron/idiomatic.js/)**: The following list outlines the practices that Rick Waldron uses in all code that he is the original author of.
    + **[JavaScript Standard Style](http://standardjs.com/)**: A set of modules to check and improve the style of your code.
    + **[WordPress JavaScript Coding Standards](https://make.wordpress.org/core/handbook/best-practices/coding-standards/javascript/)**: JavaScript has become a critical component in developing WordPress-based applications (themes and plugins) as well as WordPress core. Standards are needed for formatting and styling JavaScript code.
+ **Objects**: An object is a software bundle of related state and behavior. Software objects are often used to model the real-world objects that you find in everyday life.
    + **[ECMA-262-3 in detail: OOP - The general theory](http://dmitrysoshnikov.com/ecmascript/chapter-7-1-oop-general-theory/)**: In this article we consider major aspects of object-oriented programming in ECMAScript. Much attention is given to theoretical aspects to see these processes from within.
    + **[Gentle explanation of this keyword in JavaScript](http://rainsoft.io/gentle-explanation-of-this-in-javascript/)**: This article is focused on the invocation explanation, how the function call influences this and demonstrates the common pitfalls of identifying the context.
    + **[OOP In JavaScript: What You NEED to Know](http://javascriptissexy.com/oop-in-javascript-what-you-need-to-know/)**: In this article, we are concerned with only Inheritance and Encapsulation since only these two concepts apply to OOP in JavaScript.
    + **[Object-Oriented Design in TypeScript / ES6](http://blog.wolksoftware.com/about-classes-inheritance-and-object-oriented-design-in-typescript-and-es6)**: The author dives into advanced OOP topics such as functional programming principles, inheritance and inversion of control.
    + **[Prototypal Inheritance in JavaScript](http://javascript.crockford.com/prototypal.html)**: An article by Douglas Crockford introducing the Object.create() method and describing the rational behind it.
    + **[Prototypal Object-Oriented Programming using JavaScript](http://alistapart.com/article/prototypal-object-oriented-programming-using-javascript)**: Mehdi Maujood describes the prototypical OO style and compares it to classes in JavaScript.
    + **[Prototypes and Inheritance in JavaScript](https://msdn.microsoft.com/en-us/magazine/ff852808.aspx)**: This article tries to demystify the concept of prototypes in JavaScript. It shows how prototypes allow objects to inherit functionality from other objects, an approach to building objects using the new operator and a constructor function.
+ **Overview**: General, high level guides and introductions to the JavaScript language.
    + **[Eloquent JavaScript (Book)](http://eloquentjavascript.net/)**: A comprehensive book about JavaScript, the language, the browser and Node.js.
    + **[JavaScript Garden](http://bonsaiden.github.io/JavaScript-Garden/)**: JavaScript Garden is a growing collection of documentation about the most quirky parts of the JavaScript programming language. It gives advice to avoid common mistakes and subtle bugs.
    + **[JavaScript Guide by Mozilla Developer Network](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide)**: The JavaScript Guide shows you how to use JavaScript and gives an overview of the language.
    + **[Simplified JavaScript Jargon](http://jargon.js.org/)**: A community-driven attempt at explaining the loads of buzzwords making the current JavaScript ecosystem in a few simple words.
    + **[Understanding ECMAScript 6](https://leanpub.com/understandinges6/read)**: Free (as in pay what you want) E-Book by Nicholas C. Zakas describing the new features in EcmaScript 6.
    + **[What the heck is the event loop anyway?](https://www.youtube.com/watch?v=8aGhZQkoFbQ)**: Philip Roberts, in this video, tries to create an intuitive understanding of what happens when JavaScript runs. He talks about the call stack, event loop, callback queue and other concepts.
    + **[You Dont Know JS](https://github.com/getify/You-Dont-Know-JS)**: These books each take on specific core parts of the language which are most commonly misunderstood or under-understood, and dive very deep and exhaustively into them.
+ **[Promises](https://www.promisejs.org/)**: A promise represents the result of an asynchronous operation.
    + **[Bluebird.js](http://bluebirdjs.com/)**: Bluebird is a full featured promise library with unmatched performance.
    + **[Difference between a Promise and a Task](https://glebbahmutov.com/blog/difference-between-promise-and-task/)**: Once you have a Promise instance the action has already started. Task instance does not run until someone calls .fork()
    + **[ECMAScript Promises Spec](https://tc39.github.io/ecma262/#sec-promise-objects)**: Standard ES specification for promises.
    + **[MDN page on Promises](https://developer.mozilla.org/en/docs/Web/JavaScript/Reference/Global_Objects/Promise)**: The Promise object is used for deferred and asynchronous computations. A Promise represents an operation that hasn't completed yet, but is expected in the future.
    + **[The Promises/A+ Spec](https://promisesaplus.com/)**: An open standard for sound, interoperable JavaScript promises—by implementers, for implementers.
    + **[Tracking Unhandled Rejected Promises](http://www.2ality.com/2016/04/unhandled-rejections.html)**: In Promise-based asynchronous code, rejections are used for error handling. One risk is that rejections may get lost, leading to silent failures.
    + **[What is Promise.try, and why does it matter?](http://cryto.net/~joepie91/blog/)**: In this brief article Sven Slootweg provides a better explanation of what Promise.try is, and why you should always use it, without exceptions.
    + **[What's The Point Of Promises?](http://www.telerik.com/blogs/what-is-the-point-of-promises)**: The point of promises is to represent the eventual resulting value from an operation, but the reason to use them is to better parallel synchronous operations and to solve the callback hell.


------------------

# License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

Please provide a link back to this repository. This is not necessary for GitHub forks.