# Build Tools

**Context: [frontend-dev-bookmarks](../README.md) / Workflow**

Toolkits and their ecosystems, that help you automate painful and repeated tasks.

[![frontend.directory](https://img.shields.io/badge/frontend-directory-blue.svg?style=flat-square)](http://frontend.directory/)
[![Gitter](https://img.shields.io/gitter/room/dypsilon/frontend-dev-bookmarks.svg?style=flat-square&maxAge=2592000)](https://gitter.im/dypsilon/frontend-dev-bookmarks)
[![Twitter](https://img.shields.io/badge/follow-twitter-55acee.svg?style=flat-square)](https://twitter.com/FrontendDir)

-----------------------------------------
+ **[Automaton](http://indigounited.com/automaton/)**: Task automation tool built in JavaScript.
+ **[Grunt](http://gruntjs.com/)**: Grunt is a task-based command line build tool for JavaScript projects.
    + **[A beginner’s guide to Grunt: Redux](http://mattbailey.io/a-beginners-guide-to-grunt-redux.html)**: Simple Grunt boilerplate for frontend workflow with detailed instructions.
    + **[GruntStart](https://github.com/tsvensen/gruntstart)**: A Grunt-enabled head-start with the H5BP, jQuery, Modernizr, and Respond. The building blocks to quickly get started with Grunt to create an optimized website.
    + **[Synchronised Testing Between Browsers/Devices](http://mattbailey.io/grunt-synchronised-testing-between-browsers-devices)**: The article describes an easy way to test your projects on your devices.
    + **[Web development is getting complex. Let's go shopping.](http://ruudud.github.io/2012/12/22/grunt/)**: A step by step tutorial for building a new project with grunt.
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
+ **[Mimosa](http://mimosajs.com)**: Mimosa is a batteries included web development workflow tool that will get you coding in seconds rather than hunting down plugins and wrangling config for hours.
+ **[Plop](https://github.com/amwmedia/plop)**: Micro-generator framework that makes it easy for an entire team to create files with a level or uniformity.
    + **[Automating Workflow with plop](http://newbranch.cn/ui-development-with-es6-javascript-part-x-automating-workflow-with-plop/)**: Automating UI Development with Riot.js and ES6 Javascript.
+ **[Webpack](http://webpack.github.io/)**: Webpack is a module bundler. It takes modules with dependencies and generates static assets representing those modules.
    + **[Block, Element, Modifying Your JavaScript Components](https://medium.com/seek-ui-engineering/block-element-modifying-your-javascript-components-d7f99fcab52b)**: Mark Dalgleish is discussing how to organize React code with BEM and build everything with Webpack.
    + **[Developing with Docker and Webpack](http://dapperdeveloper.com/2016/05/18/developing-with-docker-and-webpack/)**: Chris Harrington explains how to create a development environment with Webpack and Docker to match the production as much as possible.
    + **[Full-Stack Redux Tutorial](http://teropa.info/blog/2015/09/10/full-stack-redux-tutorial.html)**: We will go through all the steps of constructing a Node+Redux backend and a React+Redux frontend for a real-world application, using test-first development.
    + **[How to Set Up Webpack Image Loader](http://www.davidmeents.com/how-to-set-up-webpack-image-loader/)**: This brief tutorial will help you set up an image loader in Webpack.
    + **[The SoundCloud Client in React + Redux](http://www.robinwieruch.de/the-soundcloud-client-in-react-redux/)**: After finishing this step by step tutorial you will be able to author your own React + Redux project with Webpack and Babel.
    + **[Webpack from Apprentice to Master](http://survivejs.com/webpack/)**: The purpose of this guide is to help you get started with Webpack and then go beyond basics.
    + **[WebpackBin](http://www.webpackbin.com/)**: A webpack code sandbox.
    + **[Why I think Webpack is the Right Approach To Build Pipelines](http://devlog.disco.zone/2016/06/01/webpack/)**: Thomas Boyt compares how Grunt, Gulp, Broccoli and Webpack discover dependencies.
+ **[Yeoman](http://yeoman.io/)**: Yeoman helps you to kickstart new projects, prescribing best practices and tools to help you stay productive. It provides a generator ecosystem.


------------------

# License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

Please provide a link back to this repository. This is not necessary for GitHub forks.