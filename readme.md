# Awesome Node.js

> A curated list of delightful Node.js [packages](#packages) and [resources](#resources).

Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing.


## Packages

- [Mad science](#mad-science)
- [Command-line apps](#command-line-apps)
- [Functional programming](#functional-programming)
- [HTTP](#http)
- [Debugging / Profiling](#debugging--profiling)
- [Logging](#logging)
- [Web frameworks](#web-frameworks)
- [Command-line utilities](#command-line-utilities)
- [Package managers](#package-managers)
- [Build tools](#build-tools)
- [Hardware](#hardware)
- [Templating](#templating)
- [Documentation](#documentation)
- [Filesystem](#filesystem)
- [Control flow](#control-flow)
- [Streams](#streams)
- [Real-time](#real-time)
- [Date](#date)
- [Image](#image)
- [Text](#text)
- [Math](#math)
- [Data validation](#data-validation)
- [Parsing](#parsing)
- [Humanize](#humanize)
- [Compression](#compression)
- [Network](#network)
- [Static site generators](#static-site-generators)
- [Content management systems](#content-management-systems)
- [Forum](#forum)
- [Blogging](#blogging)
- [Database](#database)
- [Testing](#testing)
- [Benchmarking](#benchmarking)
- [Minifiers](#minifiers)
- [Authentication](#authentication)
- [Node.js management](#nodejs-management)
- [Email](#email)
- [Polyfills](#polyfills)
- [Natural language processing](#natural-language-processing)
- [Process management](#process-management)
- [AST](#ast)
- [Weird](#weird)
- [Miscellaneous](#miscellaneous)


### Mad science

- [webtorrent](https://github.com/feross/webtorrent) - Streaming torrent client for Node.js and the browser.
- [peerflix](https://github.com/mafintosh/peerflix) - Streaming torrent client.
- [dat](http://dat-data.com) - Real-time replication and versioning for data sets.
- [ipfs](https://github.com/jbenet/node-ipfs) - Distributed file system that seeks to connect all computing devices with the same system of files.
- [Breach](http://breach.cc) - Modular and hackable browser written in JavaScript.
- [peerwiki](https://github.com/mafintosh/peerwiki) - All of Wikipedia on BitTorrent.
- [peercast](https://github.com/mafintosh/peercast) - Stream a torrent video to Chromecast.
- [BitcoinJS](http://bitcoinjs.org) - Clean, readable, proven Bitcoin library.
- [js-git](https://github.com/creationix/js-git) - JavaScript implementation of Git.
- [NodeOS](http://node-os.com) - The first operating system powered by npm.
- [PDFKit](http://pdfkit.org) - PDF generation library.
- [turf](https://github.com/Turfjs/turf/) - Modular geospatial processing and analysis engine.


### Command-line apps

- [pageres](https://github.com/sindresorhus/pageres) - Responsive website screenshots.
- [trash](https://github.com/sindresorhus/trash) - A safer alternative to `rm`.
- [yo](https://github.com/yeoman/yo) - Run Yeoman generators.
- [ESLint](http://eslint.org) - The pluggable linting utility for JavaScript.
- [JSHint](http://jshint.com) - A community-driven tool to detect errors and potential problems in JavaScript code.
- [JSCS](https://github.com/jscs-dev/node-jscs) - JavaScript Code Style checker.
- [cpy](https://github.com/sindresorhus/cpy) - Copy files.
- [torrent](https://github.com/maxogden/torrent) - Download torrents.
- [David](https://github.com/alanshaw/david) - Tells you when your package npm dependencies are out of date.
- [vtop](https://github.com/MrRio/vtop) - More better top, with nice charts.
- [tmpin](https://github.com/sindresorhus/tmpin) - Adds stdin support to any CLI app that accepts file input.
- [normit](https://github.com/pawurb/normit) - Google Translate with speech synthesis in your terminal.
- [esformatter](https://github.com/millermedeiros/esformatter) - JavaScript code beautifier/formatter.
- [is-up](https://github.com/sindresorhus/is-up) - Check whether a website is up or down.
- [ipify](https://github.com/sindresorhus/ipify) - Get your public IP address.
- [http-server](https://github.com/nodeapps/http-server) - Simple, zero-config command-line HTTP server.
- [bcat](https://github.com/kessler/node-bcat) - Pipe command output to web browsers.
- [slap](https://github.com/slap-editor/slap) - Sublime-like terminal-based text editor.


### Functional programming

- [Lo-Dash](http://lodash.com) - A utility library delivering consistency, customization, performance, & extras. A better and faster Underscore.js.
- [Mout](http://moutjs.com) - Utility library with the biggest difference between other existing solutions is that you can choose to load only the modules/functions that you need, no extra overhead.
- [mori](http://swannodette.github.io/mori/) - A library for using ClojureScript's persistent data structures and supporting API from the comfort of vanilla JavaScript.
- [Folktale](http://folktale.github.io) - A suite of libraries for generic functional programming in JavaScript that allows you to write elegant, modular applications with fewer bugs, and more reuse.
- [immutable](https://github.com/facebook/immutable-js) - Immutable data collections.
- [underscore-contrib](http://documentcloud.github.io/underscore-contrib/) - The brass buckles on Underscore's utility belt.
- [Bacon.js](http://baconjs.github.io) - Functional reactive programming.
- [Lazy.js](https://github.com/dtao/lazy.js/) - Utility library similar to Lo-Dash/Underscore but with lazy evaluation, which can translate to superior performance in many cases.

### HTTP

- [request](https://github.com/mikeal/request) - Simplified HTTP request client.
- [got](https://github.com/sindresorhus/got) / [sent](https://github.com/floatdrop/sent) - A nicer interface to the built-in `http` module.
- [superagent](https://github.com/visionmedia/superagent) - A small progressive HTTP request library.
- [hyperquest](https://github.com/substack/hyperquest) - Streaming HTTP requests.
- [spdy](https://github.com/indutny/node-spdy) - Creates SPDY servers with the same API as the built-in `https` module.
- [Nock](https://github.com/pgte/nock) - A HTTP mocking and expectations library.
- [download](https://github.com/kevva/download) - Download and extract files effortlessly.
- [wreck](https://github.com/hapijs/wreck) - HTTP Client Utilities.


### Debugging / Profiling

- [node-inspector](https://github.com/node-inspector/node-inspector) - Debugger based on Blink Developer Tools.
- [Theseus](https://github.com/adobe-research/theseus) - A new type of JavaScript debugger featuring real-time code coverage, retroactive inspection and asynchronous call tree.
- [longjohn](https://github.com/mattinsler/longjohn) - Long stack traces with configurable call trace length.
- [debug](https://github.com/visionmedia/debug) - Tiny debugging utility.
- [jstrace](https://github.com/jstrace/jstrace) - Dynamic tracing for JavaScript, similar to dtrace, ktap etc.
- [TraceGL](https://github.com/traceglMPL/tracegl) - Transforms your JavaScript, injecting monitoring code that produces a log of everything that happens.
- [spy-js](https://github.com/spy-js/spy-js#installation) - Tracing tool for JavaScript, featuring configurable event capturing, searchable call stack, code coverage, recorded object values inspection, multi process and node cluster tracing support.
- [njsTrace](https://github.com/valyouw/njstrace) - Instrument and trace your code, see all function calls, arguments, return values, as well as the time spent in each function.
- [vstream](https://github.com/joyent/node-vstream) - Instrumentable streams mix-ins to inspect a pipeline of streams.
- [stackman](https://github.com/watson/stackman) - Enhance an error stacktrace with code excerpts and other goodies.


### Logging

- [winston](https://github.com/flatiron/winston) - A multi-transport async logging library.
- [Bunyan](https://github.com/trentm/node-bunyan) - A simple and fast JSON logging library.
- [intel](https://seanmonstar.github.io/intel) - A comprehensive logging library (handlers, filters, formatters, console injection).


### Web frameworks

- [Koa](http://koajs.com) - A new web framework designed by the team behind Express, which aims to be a smaller, more expressive, and more robust foundation for web applications and APIs.
- [Express](http://expressjs.com) - A minimal and flexible web application framework, providing a robust set of features for building single and multi-page, and hybrid web applications.
- [Hapi](http://hapijs.com) - A rich framework for building applications and services.
- [LoopBack](http://loopback.io) - Powerful framework for creating REST APIs and easily connecting to backend data sources.
- [Meteor](https://www.meteor.com) - An ultra-simple, database-everywhere, data-on-the-wire, pure-Javascript web framework.
- [SailsJS](http://sailsjs.org) - An MVC web framework with a modern twist, supporting WebSockets, streams, and a data-driven API.
- [Restify](http://mcavage.me/node-restify/) - A node framework built specifically to enable you to build correct REST web services.
- [Derby](https://github.com/derbyjs/derby) - MVC framework, making it easy to write realtime, collaborative applications that run in both Node.js and browsers.
- [Interfake](https://github.com/basicallydan/interfake) - Rapid prototyping framework for making mock HTTP APIs, with a Node, command-line and HTTP interface.


### Command-line utilities

- [chalk](https://github.com/sindresorhus/chalk) - Terminal string styling done right.
- [minimist](https://github.com/substack/minimist) - Parse command-line flags.
- [get-stdin](https://github.com/sindresorhus/get-stdin) - Easier stdin.
- [Inquirer.js](https://github.com/SBoudrias/Inquirer.js) - Interactive command-line prompt.
- [update-notifier](https://github.com/yeoman/update-notifier) - Update notifications for your CLI app.
- [sudo-block](https://github.com/sindresorhus/sudo-block) - Block users from running your app with root permissions.
- [configstore](https://github.com/yeoman/configstore) - Easily load and persist config without having to think about where and how.
- [insight](https://github.com/yeoman/insight) - Helps you understand how your tool is being used by anonymously reporting usage metrics to Google Analytics.
- [sparkly](https://github.com/sindresorhus/sparkly) - Generate sparklines ▁▂▃▅▂▇
- [blessed](https://github.com/chjj/blessed) - A curses-like library.
- [cli-table](https://github.com/LearnBoost/cli-table) - Pretty unicode tables.
- [drawille](https://github.com/madbence/node-drawille) - Draw on the terminal with unicode braille characters.
- [progress](https://github.com/visionmedia/node-progress) - Flexible ascii progress bar.
- [log-symbols](https://github.com/sindresorhus/log-symbols) - Colored symbols for various log levels.
- [columnify](https://github.com/timoxley/columnify) - Create text-based columns suitable for console output. Supports cell wrapping.
- [googleauth](https://github.com/maxogden/googleauth) - Create and load persistent Google authentication tokens for command-line apps.
- [figures](https://github.com/sindresorhus/figures) - Unicode symbols with Windows CMD fallbacks.
- [cli-cursor](https://github.com/sindresorhus/cli-cursor) - Toggle the CLI cursor.


### Package managers

- [npm](https://github.com/npm/npm/) - A package manager for Node.js and the web.
- [Bower](http://bower.io) - A package manager for the web.
- [Component](https://github.com/component/component) - A package manager for building better web apps.
- [Duo](http://duojs.org) - A next-generation package manager for the front-end.
- [jspm.io](http://jspm.io) - Frictionless browser package management with support for ES6, CommonJS, AMD modules.


### Build tools

- [gulp.js](http://gulpjs.com) - Streaming and fast build system that favors code over config.
- [grunt](http://gruntjs.com) - Task runner that can perform repetitive tasks like minification, compilation, unit testing, linting, etc.
- [Broccoli](https://github.com/broccolijs/broccoli) - A fast, reliable asset pipeline, supporting constant-time rebuilds and compact build definitions.
- [browserify](https://github.com/substack/node-browserify) - Browser-side require() the Node.js way.
- [webpack](https://github.com/webpack/webpack) - Packs CommonJS/AMD modules for the browser.
- [Brunch](https://github.com/brunch/brunch) - Front-end web app build tool with simple declarative config, fast incremental compilation, and an opinionated workflow.

### Hardware

- [johnny-five](https://github.com/rwaldron/johnny-five) - Firmata based Arduino Framework.
- [serialport](https://github.com/voodootikigod/node-serialport) - Access serial ports for reading and writing.
- [usb](https://github.com/nonolith/node-usb) - USB library.
- [cylon.js](http://cylonjs.com/) - Next generation robotics framework with support for 26 different platforms.


### Templating

- [handlebars.js](https://github.com/wycats/handlebars.js/) - A superset of Mustache templates which adds powerful features like helpers and more advanced blocks.
- [hogan.js](http://twitter.github.io/hogan.js/) - Twitter's small, fast, phase-separated compiler for Mustache templates.
- [Jade](https://github.com/visionmedia/jade) - High performance template engine heavily influenced by Haml.
- [nunjucks](https://github.com/mozilla/nunjucks) - A powerful templating engine with inheritance, asynchronous control, and more (jinja2 inspired).


### Documentation

- [Docco](http://jashkenas.github.io/docco/) - A quick-and-dirty documentation generator which produces an HTML document that displays your comments intermingled with your code.
- [JSDoc](http://usejsdoc.org) - API documentation generator similar to JavaDoc or PHPDoc.
- [dox](https://github.com/visionmedia/dox) - JavaScript documentation generator using Markdown and JSDoc.
- [jsdox](https://github.com/sutoiku/jsdox) - JSDoc3 to Markdown documentation generator.
- [apiDoc](https://github.com/apidoc/apidoc) - Inline documentation for RESTful web APIs.


### Filesystem

- [del](https://github.com/sindresorhus/del) - Delete files/folders using globs.
- [globby](https://github.com/sindresorhus/globby) - Glob files with support for multiple patterns.
- [cpy](https://github.com/sindresorhus/cpy) - Copy files.
- [rimraf](https://github.com/isaacs/rimraf) - Recursively delete files like `rm -rf`.
- [mkdirp](https://github.com/substack/node-mkdirp) - Recursively create directories like `mkdir -p`.
- [graceful-fs](https://github.com/isaacs/node-graceful-fs) - Drop-in replacement for the `fs` module with various improvements.
- [fs-extra](https://github.com/jprichardson/node-fs-extra) - Extra methods for the `fs` module.


### Control flow

- Callbacks
	- [each-async](https://github.com/sindresorhus/each-async) - Async concurrent iterator like forEach.
	- [async](https://github.com/caolan/async) - Provides straight-forward, powerful functions for working with asynchronousity.
	- [after-all-results](https://github.com/watson/after-all-results) - Bundle results of async functions calls into one callback with all the results.
- Generators
	- [co](https://github.com/visionmedia/co) - The ultimate generator based flow-control goodness.
	- [suspend](https://github.com/jmar777/suspend) - Generator-based control flow that plays nice with callbacks, promises, and thunks.
- Promises
	- [native-promise-only](https://github.com/getify/native-promise-only) - A polyfill for native ES6 Promises.
	- [Bluebird](https://github.com/petkaantonov/bluebird) - A fully featured promise library with focus on innovative features and performance.
	- [Q](https://github.com/kriskowal/q) - A tool for making and composing asynchronous promises.
- Streams
	- [Highland.js](http://highlandjs.org) - Manages synchronous and asynchronous code easily, using nothing more than standard JavaScript and Node-like Streams.
- Channels
	- [js-csp](https://github.com/jlongster/js-csp) - Communicating sequential processes for JavaScript (like Clojurescript core.async, or Go).
- Other
	- [zone](https://github.com/strongloop/zone) - Provides a way to group and track resources and errors across asynchronous operations.

### Streams

- [through2](https://github.com/rvagg/through2) - Tiny wrapper around streams2 Transform to avoid explicit subclassing noise.
- [concat-stream](https://github.com/maxogden/concat-stream) - Concatenates a stream into strings or binary data.
- [simple-bufferstream](https://github.com/rvagg/node-simple-bufferstream) - Turn a Buffer into a ReadableStream.
- [co-stream](https://github.com/juliangruber/co-stream) - [co](https://github.com/visionmedia/co) generator stream.
- [byline](https://github.com/jahewson/node-byline) - Super-simple line-by-line Stream reader.
- [first-chunk-stream](https://github.com/sindresorhus/first-chunk-stream) - Transform the first chunk in a stream.
- [duplexify](https://github.com/mafintosh/duplexify) - Turn a writeable and readable stream into a single streams2 duplex stream.
- [pumpify](https://github.com/mafintosh/pumpify) - Combine an array of streams into a single duplex stream.
- [from2](https://github.com/hughsk/from2) - Convenience wrapper for ReadableStream, inspired by `through2`.
- [from2-array](https://github.com/binocarlos/from2-array) - Create a `from2` stream based on an array of source values.
- [peek-stream](https://github.com/mafintosh/peek-stream) - Transform stream that lets you peek the first line before deciding how to parse it.
- [binary-split](https://github.com/maxogden/binary-split) - A fast newline (or any delimiter) splitter stream.
- [multistream](https://github.com/feross/multistream) - Combine multiple streams into a single stream.
- [graphicsmagick-stream](https://github.com/e-conomic/graphicsmagick-stream/) - Fast conversion/scaling of images using a pool of long lived graphicsmagick processes.
- [readable-stream](https://github.com/isaacs/readable-stream) - Mirror of Streams2 and Streams3 implementations in core.
- [s3-upload-stream](https://github.com/nathanpeck/s3-upload-stream) - Upload a stream to an Amazon S3 bucket using multipart upload.


### Real-time

- [Socket.io](http://socket.io) - Enables real-time bidirectional event-based communication.
- [SocketCluster](https://github.com/topcloud/socketcluster) - Scalable HTTP + WebSocket engine which can run on multiple CPU cores.
- [Primus](https://github.com/primus/primus) - An abstraction layer for real-time frameworks to prevent module lock-in.
- [Straw](https://github.com/simonswain/straw) - Real-time dataflow framework.


### Date

- [Moment.js](http://momentjs.com) - Parse, validate, manipulate, and display dates.
- [dateformat](https://github.com/felixge/node-dateformat) - Date formatting.


### Image

- [sharp](https://github.com/lovell/sharp) - The fastest module for resizing JPEG, PNG, WebP and TIFF images.
- [image-type](https://github.com/sindresorhus/image-type) - Detect the image type of a Buffer/Uint8Array.
- [gm](https://github.com/aheckmann/gm) - GraphicsMagick and ImageMagick wrapper.


### Text

- [Underscore.string](https://github.com/epeli/underscore.string) - Collection of string manipulation utilities.
- [he](https://github.com/mathiasbynens/he) - A robust HTML entity encoder/decoder.
- [iconv-lite](https://github.com/ashtuchkin/iconv-lite) - Convert character encodings.
- [escape-string-regexp](https://github.com/sindresorhus/escape-string-regexp) - Escape RegExp special characters.
- [indent-string](https://github.com/sindresorhus/indent-string) - Indent each line in a string.
- [strip-indent](https://github.com/sindresorhus/strip-indent) - Strip leading whitespace from every line in a string.
- [detect-indent](https://github.com/sindresorhus/detect-indent) - Detect the indentation of code.
- [i18n-node](https://github.com/mashpie/i18n-node) - Simple translation module with dynamic JSON storage.
- [string-length](https://github.com/sindresorhus/string-length) - Get the real length of a string - by correctly counting astral symbols and ignoring ansi escape codes.
- [speakingurl](https://github.com/pid/speakingurl) - Generate a slug from a string with transliteration.


### Math

- [ndarray](https://github.com/mikolalysenko/ndarray) - Multidimensional arrays.
- [mathjs](https://github.com/josdejong/mathjs) - An extensive math library.


### Data validation

- [joi](https://github.com/spumko/joi) - Object schema description language and validator for JavaScript objects.


### Parsing

- [css](https://github.com/reworkcss/css) - CSS parser / stringifier.
- [strip-json-comments](https://github.com/sindresorhus/strip-json-comments) - Strip comments from JSON.
- [marked](https://github.com/chjj/marked) - A markdown parser and compiler built for speed.
- [js-yaml](https://github.com/nodeca/js-yaml) - Very fast YAML parser.
- [URI.js](https://github.com/medialize/URI.js) - URL mutation.
- [JSONStream](https://github.com/dominictarr/JSONStream) - Streaming JSON.parse and stringify.
- [csv-parser](https://github.com/mafintosh/csv-parser) - Streaming CSV parser that aims to be faster than everyone else.
- [excel-stream](https://github.com/dominictarr/excel-stream) - Streaming Excel spreadsheet to JSON parser.
- [parse5](https://github.com/inikulin/parse5) - Fast full-featured spec compliant HTML parser.
- [htmlparser2](https://github.com/fb55/htmlparser2/) - Forgiving HTML/XML parser.
- [PostCSS](https://github.com/postcss/postcss) - Framework for CSS postprocessors, to modify CSS.
- [PEG.js](https://github.com/dmajda/pegjs) - Simple parser generator that produces fast parsers with excellent error reporting.


### Humanize

- [pretty-bytes](https://github.com/sindresorhus/pretty-bytes) - Convert bytes to a human readable string: `1337` → `1.34 kB`.
- [pretty-ms](https://github.com/sindresorhus/pretty-ms) - Convert milliseconds to a human readable string: `1337000000` → `15d 11h 23m 20s`.
- [ms](https://github.com/guille/ms.js) - Tiny millisecond conversion utility.
- [pretty-error](https://github.com/AriaMinaei/pretty-error) - Errors with less clutter.
- [humanize](https://github.com/taijinlee/humanize) - Data formatter for human readability.
- [node-read](https://github.com/bndr/node-read) - Extract readable content from any page.


### Compression

- [Archiver](https://github.com/ctalkington/node-archiver) - Streaming interface for archive generation, supporting ZIP and TAR.
- [decompress-zip](https://github.com/bower/decompress-zip) - Unzip.
- [tar-stream](https://github.com/mafintosh/tar-stream) - Streaming tar parser and generator. Also see [tar-fs](https://github.com/mafintosh/tar-fs).
- [decompress](https://github.com/kevva/decompress) - A pluggable decompression module with support for `tar`, `tar.gz` and `zip` files out of the box.


### Network

- [get-port](https://github.com/sindresorhus/get-port) - Get an available port.
- [ipify](https://github.com/sindresorhus/ipify) - Get your public IP address.


### Static site generators

- [Metalsmith](http://www.metalsmith.io) - An extremely simple, pluggable static site generator.
- [Wintersmith](http://wintersmith.io) - Flexible, minimalistic, multi-platform static site generator.
- [Assemble](http://assemble.io) - Static site generator for Node.js, Grunt.js, and Yeoman.


### Content management systems

- [KeystoneJS](http://keystonejs.com) - CMS and web application platform built on Express and MongoDB.
- [Calipso](http://calip.so) - A simple content management system, built along similar themes to Drupal and Wordpress, that is designed to be fast, flexible and simple.
- [Apostrophe2](http://apostrophenow.org) - A content management system with an emphasis on intuitive front end content editing and administration built on Express and MongoDB.


### Forum

- [nodeBB](https://nodebb.org) - A better forum platform for the modern web.


### Blogging

- [ghost](https://ghost.org) - Simple, powerful publishing platform that allows you to share your story with the world.
- [Hexo](http://hexo.io) - Fast, simple and powerful blogging framework.


### Database

- Drivers
	- [LevelUP](https://github.com/rvagg/node-levelup) - LevelDB.
	- [MongoDB](https://github.com/mongodb/node-mongodb-native) - MongoDB driver.
	- [PostgreSQL](https://github.com/brianc/node-postgres) - PostgreSQL client. Pure JavaScript and native libpq bindings.
	- [MySQL](https://github.com/felixge/node-mysql) - MySQL client.
	- [Redis](https://github.com/mranney/node_redis) - Redis client.
- ODM / ORM
	- [Bookshelf](http://bookshelfjs.org) - ORM for PostgreSQL, MySQL and SQLite3 in the style of Backbone.js.
	- [JugglingDB](https://github.com/1602/jugglingdb) - Multi-database ORM with a common API. Supports Redis, PostgreSQL, MongoDB, MySQL, SQLite, Neo4j, memory, and more.
	- [Mongoose](http://mongoosejs.com) - Elegant MongoDB object modeling.
	- [Sequelize](https://github.com/sequelize/sequelize) - Multi-dialect ORM. Supports PostgreSQL, SQLite, MySQL.
    - [Waterline](https://github.com/balderdashy/waterline) - Datastore-agnostic tool that dramatically simplifies interaction with one or more databases.
	- [Iridium](https://github.com/SierraSoftworks/Iridium) - A high performance MongoDB ORM with support for promises, distributed caching, preprocessing, validation and plugins.
	- [OpenRecord](https://github.com/PhilWaldmann/openrecord) - ORM for PostgreSQL, MySQL, SQLite3 and RESTful datastores. Similar to ActiveRecord.
- Query builder
	- [Knex](http://knexjs.org) - A query builder for PostgreSQL, MySQL and SQLite3, designed to be flexible, portable, and fun to use.


### Testing

- [tape](https://github.com/substack/tape) - [TAP](http://testanything.org)-producing test harness.
- [Mocha](http://visionmedia.github.io/mocha/) - A feature-rich test framework making asynchronous testing simple and fun.
- [Mochify](https://github.com/mantoni/mochify.js) - TDD with Browserify, Mocha, PhantomJS and WebDriver.
- [loadtest](https://github.com/alexfernandez/loadtest) - Run load tests for your web application, with an API for automation.
- [istanbul](https://github.com/gotwarlost/istanbul) - A code coverage tool that computes statement, line, function and branch coverage with module loader hooks to transparently add coverage when running tests.
- [Sinon.JS](https://github.com/cjohansen/Sinon.JS) - Test spies, stubs and mocks.
- [Karma](http://karma-runner.github.io) - Executes code in multiple real browsers.


### Benchmarking

- [Benchmark.js](http://benchmarkjs.com) - A robust benchmarking library that works on nearly all JavaScript platforms, supports high-resolution timers, and returns statistically significant results.
- [matcha](https://github.com/logicalparadox/matcha) - A caffeine driven, simplistic approach to benchmarking.


### Minifiers

- [UglifyJS2](http://lisperator.net/uglifyjs/) - JavaScript minifier.
- [clean-css](https://github.com/GoalSmashers/clean-css) - CSS minifier.
- [minimize](https://github.com/Moveo/minimize) - HTML minifier.
- [imagemin](https://github.com/kevva/imagemin) - Image minifier.


### Authentication

- [Passport](http://passportjs.org) - Simple, unobtrusive authentication.
- [everyauth](https://github.com/bnoguchi/everyauth) - Authentication and authorization (password, facebook, & more) for your Connect and Express apps.
- [passwordless](https://passwordless.net) - Token-based authentication middleware for Express allowing authentication without passwords.
- [Lockit](https://github.com/zemirco/lockit) - Full featured authentication solution for Express. Supports a variety of databases, predefined routes, email and two-factor authentication.


### Node.js management

- [n](https://github.com/visionmedia/n) - Node.js version management.
- [nave](https://github.com/isaacs/nave) - Virtual Environments for Node.js.
- [nodeenv](https://github.com/ekalinin/nodeenv) - A Node.js virtual environment compatible to Python's virtualenv.


### Email

- [Nodemailer](https://github.com/andris9/Nodemailer) - The fastest way to handle email.


### Polyfills

- [object-assign](https://github.com/sindresorhus/object-assign) - ES6 Object.assign() polyfill.
- [harmony-reflect](https://github.com/tvcutsem/harmony-reflect) - ES6 Reflect and Proxy polyfill.
- [es6-shim](https://github.com/paulmillr/es6-shim) - Collection of ES6 polyfills.
- More ES6 polyfills at [es6-tools](https://github.com/addyosmani/es6-tools#polyfills).


### Natural language processing

- [natural](https://github.com/NaturalNode/natural) - A general natural language facility.
- [retext](https://github.com/wooorm/retext) - An extensible natural language system.
- [leven](https://github.com/sindresorhus/leven) - Measure the difference between two strings using the Levenshtein distance algorithm.


### Process management

- [node-windows](https://github.com/coreybutler/node-windows) - Run scripts as a native Windows service and log to the Event viewer.
- [node-mac](https://github.com/coreybutler/node-mac) - Run scripts as a native Mac daemon and log to the console app.
- [node-linux](https://github.com/coreybutler/node-linux) - Run scripts as native system service and log to syslog.
- [forever](https://github.com/nodejitsu/forever) - A simple CLI tool for ensuring that a given script runs continuously (i.e. forever).
- [supervisor](https://github.com/isaacs/node-supervisor) - Restart scripts when they crash or restart when a `*.js` file changes.
- [PM2](https://github.com/Unitech/pm2) - Advanced Process Manager.
- [Phusion Passenger](https://www.phusionpassenger.com/node_weekly) - Friendly process manager that integrates directly into Nginx.


### AST

- [Acorn](https://github.com/marijnh/acorn/) - A tiny, fast JavaScript parser.
- [Rocambole](https://github.com/millermedeiros/rocambole) - Recursively walk and transform JavaScript AST.


### Weird

- [superb](https://github.com/sindresorhus/superb) - Get superb like words.
- [cool-ascii-faces](https://github.com/maxogden/cool-ascii-faces) - Get some cool ascii faces.


### Miscellaneous

- [multiline](https://github.com/sindresorhus/multiline) - Multiline strings in JavaScript.
- [opn](https://github.com/sindresorhus/opn) - Opens stuff like websites, files, executables.
- [semver](https://github.com/isaacs/node-semver) - [semver](http://semver.org) parser.
- [cheerio](https://github.com/cheeriojs/cheerio) - Fast, flexible, and lean implementation of core jQuery designed specifically for the server.
- [require-uncached](https://github.com/sindresorhus/require-uncached) - Require a module bypassing the cache.
- [Faker.js](https://github.com/Marak/Faker.js) - Generate massive amounts of fake data.
- [Bottleneck](https://github.com/SGrondin/bottleneck) - A powerful rate limiter that makes throttling easy.
- [stringify-object](https://github.com/yeoman/stringify-object) - Stringify an object/array like JSON.stringify just without all the double-quotes.
- [strip-bom](https://github.com/sindresorhus/strip-bom) - Strip UTF-8 byte order mark (BOM) from a string/buffer/stream.
- [shelljs](https://github.com/arturadib/shelljs) - Portable Unix shell commands.
- [nan](https://github.com/rvagg/nan) - A header file filled with macro and utility goodness for making add-on development for across Node.js versions easier.
- [ssh2](https://github.com/mscdex/ssh2) - An SSH2 client module.
- [lazy-req](https://github.com/sindresorhus/lazy-req) - Require modules lazily.
- [webworker-threads](https://github.com/audreyt/node-webworker-threads) - Lightweight Web Worker API implementation with native threads.
- [node-pre-gyp](https://github.com/mapbox/node-pre-gyp/) - Makes it easy to publish and install Node.js C++ addons from binaries.
- [opencv](https://github.com/peterbraden/node-opencv) - Bindings for OpenCV. The defacto computer vision library.
- [common-errors](https://github.com/shutterstock/node-common-errors) - Common error classes and utility functions.


## Resources

### Tutorials

- [Nodeschool](http://nodeschool.io) - Learn Node.js with interactive lessons.
- [The Art of Node](https://github.com/maxogden/art-of-node/#the-art-of-node) - An introduction to Node.js.
- [stream-handbook](https://github.com/substack/stream-handbook) - How to write Node.js programs with streams.
- [browserify-handbook](https://github.com/substack/browserify-handbook) - The definitive guide for browserify.

### Discovery

- [node-modules.com](http://node-modules.com/) - An alternative npm search engine with a more intelligent and personal results ranking.

### Articles

- [Error Handling in Node.js](http://www.joyent.com/developers/node/design/errors)

### Newsletters

- [node weekly](http://nodeweekly.com) - Weekly e-mail round-up of Node.js news and articles.

### Videos

- [Introduction to Node.js with Ryan Dahl](https://www.youtube.com/watch?v=jo_B4LTHi3I)
- [LearnAllTheNodes](http://www.learnallthenodes.com) - Series of useful tips, tricks, and packages.

### Podcasts

- [NodeUp](http://nodeup.com)

### Books

- [Node.js in Action](http://www.amazon.com/Node-js-Action-Mike-Cantelon/dp/1617290572)
- [Mastering Node](http://visionmedia.github.io/masteringnode/)
- [Professional Node.js: Building Javascript Based Scalable Software](http://www.amazon.com/Professional-Node-js-Building-Javascript-Scalable-ebook/dp/B009L7QETY/)
- [Practical Node.js: Building Real-World Scalable Web Apps](http://practicalnodebook.com)
- [Mixu's Node book](http://book.mixu.net/node/)

### Blogs

- [Node.js blog](http://blog.nodejs.org)
- [HowToNode](http://howtonode.org) - Teaching how to do various tasks in Node.js as well as teach fundamental concepts that are needed to write effective code.

### Courses

- [Real Time Web with Node.js](http://node.codeschool.com)

### Cheatsheets

- [Express.js](https://github.com/azat-co/cheatsheets/blob/master/express4/index.md)

### Tools

- [GitHub Linker](https://chrome.google.com/webstore/detail/github-linker/jlmafbaeoofdegohdhinkhilhclaklkp) - Chrome extension that linkifies dependencies in package.json on GitHub.

### Miscellaneous

- [nodebots](http://nodebots.io) - Robots powered by JavaScript.


## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.


## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Sindre Sorhus](http://sindresorhus.com) has waived all copyright and related or neighboring rights to this work.
