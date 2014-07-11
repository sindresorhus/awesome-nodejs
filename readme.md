# Awesome Node.js

> A curated list of delightful Node.js [packages](#packages) and [resources](#resources).

Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing.


## Packages

- [Functional programming](#functional-programming)
- [Command-line apps](#command-line-apps)
- [HTTP](#http)
- [Logging](#logging)
- [Web frameworks](#web-frameworks)
- [Command-line utilities](#command-line-utilities)
- [Build tools](#build-tools)
- [Templating](#templating)
- [Documentation](#documentation)
- [Filesystem](#filesystem)
- [Control flow](#control-flow)
- [Streams](#streams)
- [Real-time](#real-time)
- [Date](#date)
- [Image](#image)
- [Humanize](#humanize)
- [Static site generators](#static-site-generators)
- [Content management systems](#content-management-systems)
- [Debugging](#debugging)
- [Database](#database)
- [Testing](#testing)
- [Minifiers](#minifiers)
- [Authentication](#authentication)
- [Node.js management](#nodejs-management)
- [Polyfills](#polyfills)
- [Miscellaneous](#miscellaneous)


### Functional programming

- [Lo-Dash](http://lodash.com) - A utility library delivering consistency, customization, performance, & extras. A better and faster Underscore.js.
- [Underscore.js](http://underscorejs.org) - Provides a whole mess of useful functional programming helpers without extending any built-in objects.
- [Mout](http://moutjs.com) - Utility library with the biggest difference between other existing solutions is that you can choose to load only the modules/functions that you need, no extra overhead.


### Command-line apps

- [npm](https://github.com/npm/npm/) - A package-manager for Node.js.
- [Bower](http://bower.io) - A package manager for the web.
- [Yo](https://github.com/yeoman/yo) - Run Yeoman generators.
- [Pageres](https://github.com/sindresorhus/pageres) - Responsive website screenshots.
- [trash](https://github.com/sindresorhus/trash) - A safer alternative to `rm`.
- [ESLint](http://eslint.org) - The pluggable linting utility for JavaScript.
- [JSHint](http://jshint.com) - A community-driven tool to detect errors and potential problems in JavaScript code.
- [cpy](https://github.com/sindresorhus/cpy) - Copy files.


### HTTP

- [request](https://github.com/mikeal/request) - Simplified HTTP request client.
- [got](https://github.com/sindresorhus/got) - A nicer interface to the built-in `http` module.
- [superagent](https://github.com/visionmedia/superagent) - A small progressive HTTP request library.
- [hyperquest](https://github.com/substack/hyperquest) - Streaming HTTP requests.


### Logging

- [winston](https://github.com/flatiron/winston) - A multi-transport async logging library.
- [Bunyan](https://github.com/trentm/node-bunyan) - A simple and fast JSON logging library.


### Web frameworks

- [Koa](http://koajs.com) - A new web framework designed by the team behind Express, which aims to be a smaller, more expressive, and more robust foundation for web applications and APIs.
- [Express](http://expressjs.com) - A minimal and flexible web application framework, providing a robust set of features for building single and multi-page, and hybrid web applications.
- [Hapi](http://hapijs.com/) - A rich framework for building applications and services.


### Command-line utilities

- [chalk](https://github.com/sindresorhus/chalk) - Terminal string styling done right.
- [minimist](https://github.com/substack/minimist) - Parse command-line flags
- [Inquirer.js](https://github.com/SBoudrias/Inquirer.js) - Interactive command-line prompt.
- [update-notifier](https://github.com/yeoman/update-notifier) - Update notifications for your CLI app.
- [sudo-block](https://github.com/sindresorhus/sudo-block) - Block users from running your app with root permissions.
- [blessed](https://github.com/chjj/blessed) - A curses-like library.
- [cli-table](https://github.com/LearnBoost/cli-table) - Pretty unicode tables.


### Build tools

- [gulp.js](http://gulpjs.com) - Streaming and fast build system that favors code over config.
- [grunt](http://gruntjs.com) - Task runner that can perform repetitive tasks like minification, compilation, unit testing, linting, etc.
- [Broccoli](https://github.com/broccolijs/broccoli) - A fast, reliable asset pipeline, supporting constant-time rebuilds and compact build definitions.


### Templating

- [handlebars.js](https://github.com/wycats/handlebars.js/) - Provides the power necessary to let you build semantic templates effectively with no frustration.
- [Jade](https://github.com/visionmedia/jade) - High performance template engine heavily influenced by Haml.
- [nunjucks](https://github.com/mozilla/nunjucks) - A powerful templating engine with inheritance, asynchronous control, and more (jinja2 inspired).


### Documentation

- [Docco](http://jashkenas.github.io/docco/) - A quick-and-dirty documentation generator which produces an HTML document that displays your comments intermingled with your code.
- [JSDoc](http://usejsdoc.org) - API documentation generator similar to JavaDoc or PHPDoc.
- [dox](https://github.com/visionmedia/dox) - JavaScript documentation generator for Node.js using Markdown and JSDoc.


### Filesystem

- [del](https://github.com/sindresorhus/del) - Delete files/folders using globs.
- [globby](https://github.com/sindresorhus/globby) - Glob files with support for multiple patterns.
- [cpy](https://github.com/sindresorhus/cpy) - Copy files.
- [rimraf](https://github.com/isaacs/rimraf) - Recursively delete files like `rm -rf`.
- [mkdirp](https://github.com/substack/node-mkdirp) - Recursively create directories like `mkdir -p`.
- [graceful-fs](https://github.com/isaacs/node-graceful-fs) - Drop-in replacement for the `fs` module with various improvements.


### Control flow

- [each-async](https://github.com/sindresorhus/each-async) - Async concurrent iterator like forEach.
- [async](https://github.com/caolan/async) - Provides straight-forward, powerful functions for working with asynchronousity.
- [co](https://github.com/visionmedia/co) - The ultimate generator based flow-control goodness.
- [Highland.js](http://highlandjs.org) - Manages synchronous and asynchronous code easily, using nothing more than standard JavaScript and Node-like Streams.
- [native-promise-only](https://www.npmjs.org/package/native-promise-only) - A polyfill for native ES6 Promises.
- [Bluebird](https://github.com/petkaantonov/bluebird) - A fully featured promise library with focus on innovative features and performance.
- [Q](https://github.com/kriskowal/q) - A tool for making and composing asynchronous promises.


### Streams

- [through2](https://github.com/rvagg/through2) - Tiny wrapper around Node streams2 Transform to avoid explicit subclassing noise.
- [concat-stream](https://github.com/maxogden/concat-stream) - Concatenates a stream into strings or binary data.
- [simple-bufferstream](https://github.com/rvagg/node-simple-bufferstream) - Turn a Buffer into a ReadableStream.
- [co-stream](https://github.com/juliangruber/co-stream) - [co](https://github.com/visionmedia/co) generator stream.
- [byline](https://www.npmjs.org/package/byline) - Super-simple line-by-line Stream reader.


### Real-time

- [Socket.io](http://socket.io) - Enables real-time bidirectional event-based communication.


### Date

- [Moment.js](http://momentjs.com) - Parse, validate, manipulate, and display dates.
- [dateformat](https://github.com/felixge/node-dateformat) - Date formatting.


### Image

- [sharp](https://github.com/lovell/sharp) - The fastest module for resizing JPEG, PNG, WebP and TIFF images.


### Humanize

- [pretty-bytes](https://github.com/sindresorhus/pretty-bytes) - Convert bytes to a human readable string: `1337` → `1.34 kB`.
- [pretty-ms](https://github.com/sindresorhus/pretty-ms) - Convert milliseconds to a human readable string: `1337000000` → `15d 11h 23m 20s`.


### Static site generators

- [Metalsmith](http://www.metalsmith.io) - An extremely simple, pluggable static site generator.
- [Wintersmith](http://wintersmith.io) - Flexible, minimalistic, multi-platform static site generator.
- [Assemble](http://assemble.io) - Static site generator for Node.js, Grunt.js, and Yeoman.


### Content management systems

- [KeystoneJS](http://keystonejs.com) - CMS and web application platform built on Express and MongoDB.
- [Calipso](http://calip.so) - A simple content management system, built along similar themes to Drupal and Wordpress, that is designed to be fast, flexible and simple.


### Debugging

- [node-inspector](https://github.com/node-inspector/node-inspector) - Debugger based on Blink Developer Tools.
- [Theseus](https://github.com/adobe-research/theseus) - A new type of JavaScript debugger featuring real-time code coverage, retroactive inspection and asynchronous call tree.
- [longjohn](https://github.com/mattinsler/longjohn) - Long stack traces with configurable call trace length.


### Database

- [LevelUP](https://github.com/rvagg/node-levelup) - LevelDB, Node.js style.


### Testing

- [tape](https://github.com/substack/tape) - [TAP](http://testanything.org)-producing test harness.
- [Mocha](http://visionmedia.github.io/mocha/) - A feature-rich test framework making asynchronous testing simple and fun.


### Minifiers

- [UglifyJS2](http://lisperator.net/uglifyjs/) - JavaScript parser, minifier, compressor or beautifier toolkit.
- [clean-css](https://github.com/GoalSmashers/clean-css) - A fast, efficient, and well tested CSS minifier.
- [minimize](https://github.com/Moveo/minimize) - HTML minifier.
- [imagemin](https://github.com/kevva/imagemin) - Minify images.


### Authentication

- [Passport](http://passportjs.org) - Simple, unobtrusive authentication.


### Node.js management

- [n](https://github.com/visionmedia/n) - Node.js version management.
- [nave](https://github.com/isaacs/nave) - Virtual Environments for Node.js.


### Polyfills

- [object-assign](https://github.com/sindresorhus/object-assign) - ES6 Object.assign() polyfill


### Miscellaneous

- [opn](https://github.com/sindresorhus/opn) - Opens stuff like websites, files, executables.
- [strip-json-comments](https://github.com/sindresorhus/strip-json-comments) - Strip comments from JSON.
- [multiline](https://github.com/sindresorhus/multiline) - Multiline strings in JavaScript.
- [marked](https://github.com/chjj/marked) - A markdown parser and compiler built for speed.
- [semver](https://github.com/isaacs/node-semver) - [semver](http://semver.org) parser.
- [cheerio](https://github.com/cheeriojs/cheerio) - Fast, flexible, and lean implementation of core jQuery designed specifically for the server.


## Resources

### Tutorials

- [Nodeschool](http://nodeschool.io) - Learn Node.js with interactive lessons.
- [The Art of Node](https://github.com/maxogden/art-of-node/#the-art-of-node) - An introduction to Node.js.
- [stream-handbook](https://github.com/substack/stream-handbook) - How to write Node.js programs with streams.

### Articles

- [Error Handling in Node.js](http://www.joyent.com/developers/node/design/errors)

### Videos

- [Introduction to Node.js with Ryan Dahl](https://www.youtube.com/watch?v=jo_B4LTHi3I)

### Podcasts

- [NodeUp](http://nodeup.com)

### Books

- [Node.js in Action](http://www.amazon.com/Node-js-Action-Mike-Cantelon/dp/1617290572)
- [Mastering Node](http://visionmedia.github.io/masteringnode/).

### Courses

- [Real Time Web with Node.js](http://node.codeschool.com)


## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.


## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Sindre Sorhus](http://sindresorhus.com) has waived all copyright and related or neighboring rights to this work.
