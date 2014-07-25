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
- [Debugging](#debugging)
- [Database](#database)
- [Testing](#testing)
- [Minifiers](#minifiers)
- [Authentication](#authentication)
- [Node.js management](#nodejs-management)
- [Polyfills](#polyfills)
- [AST](#ast)
- [Weird](#weird)
- [Miscellaneous](#miscellaneous)


### Functional programming

- [Lo-Dash](http://lodash.com) - A utility library delivering consistency, customization, performance, & extras. A better and faster Underscore.js.
- [Underscore.js](http://underscorejs.org) - Provides a whole mess of useful functional programming helpers without extending any built-in objects.
- [Mout](http://moutjs.com) - Utility library with the biggest difference between other existing solutions is that you can choose to load only the modules/functions that you need, no extra overhead.
- [Folktale](http://folktale.github.io/) - A suite of libraries for generic functional programming in JavaScript that allows you to write elegant modular applications with fewer bugs, and more reuse.


### Command-line apps

- [npm](https://github.com/npm/npm/) - A package-manager for Node.js.
- [Bower](http://bower.io) - A package manager for the web.
- [Yo](https://github.com/yeoman/yo) - Run Yeoman generators.
- [Pageres](https://github.com/sindresorhus/pageres) - Responsive website screenshots.
- [PM2](https://github.com/Unitech/pm2) - Advanced Process Manager for Node.js.
- [trash](https://github.com/sindresorhus/trash) - A safer alternative to `rm`.
- [ESLint](http://eslint.org) - The pluggable linting utility for JavaScript.
- [JSHint](http://jshint.com) - A community-driven tool to detect errors and potential problems in JavaScript code.
- [cpy](https://github.com/sindresorhus/cpy) - Copy files.
- [torrent](https://github.com/maxogden/torrent) - Download torrents.
- [David](https://github.com/alanshaw/david) - Tells you when your package npm dependencies are out of date.
- [vtop](https://github.com/MrRio/vtop) - More better top, with nice charts.


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
- [Hapi](http://hapijs.com) - A rich framework for building applications and services.
- [Meteor](https://www.meteor.com) - An ultra-simple, database-everywhere, data-on-the-wire, pure-Javascript web framework.
- [SailsJS](http://sailsjs.org) - An MVC web framework with a modern twist, supporting WebSockets, streams, and a data-driven API.
- [Restify](http://mcavage.me/node-restify/) - A node framework built specifically to enable you to build correct REST web services.


### Command-line utilities

- [chalk](https://github.com/sindresorhus/chalk) - Terminal string styling done right.
- [minimist](https://github.com/substack/minimist) - Parse command-line flags
- [Inquirer.js](https://github.com/SBoudrias/Inquirer.js) - Interactive command-line prompt.
- [update-notifier](https://github.com/yeoman/update-notifier) - Update notifications for your CLI app.
- [sudo-block](https://github.com/sindresorhus/sudo-block) - Block users from running your app with root permissions.
- [configstore](https://github.com/yeoman/configstore) - Easily load and persist config without having to think about where and how.
- [insight](https://github.com/yeoman/insight) - Helps you understand how your tool is being used by anonymously reporting usage metrics to Google Analytics.
- [blessed](https://github.com/chjj/blessed) - A curses-like library.
- [cli-table](https://github.com/LearnBoost/cli-table) - Pretty unicode tables.
- [drawille](https://github.com/madbence/node-drawille) - Draw on the terminal with unicode braille characters.
- [progress](https://github.com/visionmedia/node-progress) - Flexible ascii progress bar.


### Build tools

- [gulp.js](http://gulpjs.com) - Streaming and fast build system that favors code over config.
- [grunt](http://gruntjs.com) - Task runner that can perform repetitive tasks like minification, compilation, unit testing, linting, etc.
- [Broccoli](https://github.com/broccolijs/broccoli) - A fast, reliable asset pipeline, supporting constant-time rebuilds and compact build definitions.


### Templating

- [handlebars.js](https://github.com/wycats/handlebars.js/) - A superset of Mustache templates which adds powerful features like helpers and more advanced blocks.
- [hogan.js](http://twitter.github.io/hogan.js/) - Twitter's small, fast, phase-separated compiler for Mustache templates.
- [Jade](https://github.com/visionmedia/jade) - High performance template engine heavily influenced by Haml.
- [nunjucks](https://github.com/mozilla/nunjucks) - A powerful templating engine with inheritance, asynchronous control, and more (jinja2 inspired).


### Documentation

- [Docco](http://jashkenas.github.io/docco/) - A quick-and-dirty documentation generator which produces an HTML document that displays your comments intermingled with your code.
- [JSDoc](http://usejsdoc.org) - API documentation generator similar to JavaDoc or PHPDoc.
- [dox](https://github.com/visionmedia/dox) - JavaScript documentation generator for Node.js using Markdown and JSDoc.
- [jsdox](https://github.com/sutoiku/jsdox) - JSDoc3 to Markdown documentation generator.


### Filesystem

- [del](https://github.com/sindresorhus/del) - Delete files/folders using globs.
- [globby](https://github.com/sindresorhus/globby) - Glob files with support for multiple patterns.
- [cpy](https://github.com/sindresorhus/cpy) - Copy files.
- [rimraf](https://github.com/isaacs/rimraf) - Recursively delete files like `rm -rf`.
- [mkdirp](https://github.com/substack/node-mkdirp) - Recursively create directories like `mkdir -p`.
- [graceful-fs](https://github.com/isaacs/node-graceful-fs) - Drop-in replacement for the `fs` module with various improvements.
- [fs-extra](https://github.com/jprichardson/node-fs-extra) - Extra methods for the `fs` module.


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
- [SocketCluster](https://github.com/topcloud/socketcluster) - Scalable HTTP + WebSocket engine which can run on multiple CPU cores.
- [Primus](https://github.com/primus/primus) - An abstraction layer for real-time frameworks to prevent module lock-in.


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
- [i18n-node](https://github.com/mashpie/i18n-node) - Lightweight simple translation module for node.js / express.js with dynamic json storage.


### Math

- [ndarray](https://github.com/mikolalysenko/ndarray) - Multidimensional arrays.
- [mathjs](https://github.com/josdejong/mathjs) - An extensive math library for JavaScript and Node.js.


### Data validation

- [joi](https://github.com/spumko/joi) - Object schema description language and validator for JavaScript objects.


### Parsing

- [css](https://github.com/reworkcss/css) - CSS parser / stringifier.
- [strip-json-comments](https://github.com/sindresorhus/strip-json-comments) - Strip comments from JSON.
- [marked](https://github.com/chjj/marked) - A markdown parser and compiler built for speed.
- [js-yaml](https://github.com/nodeca/js-yaml) - Very fast YAML parser.
- [URI.js](https://github.com/medialize/URI.js) - URL mutation.
- [JSONStream](https://github.com/dominictarr/JSONStream) - Streaming JSON.parse and stringify.


### Humanize

- [pretty-bytes](https://github.com/sindresorhus/pretty-bytes) - Convert bytes to a human readable string: `1337` → `1.34 kB`.
- [pretty-ms](https://github.com/sindresorhus/pretty-ms) - Convert milliseconds to a human readable string: `1337000000` → `15d 11h 23m 20s`.
- [ms](https://github.com/guille/ms.js) - Tiny milisecond conversion utility.
- [pretty-error](https://github.com/AriaMinaei/pretty-error) - Errors with less clutter.
- [humanize](https://github.com/taijinlee/humanize) - Data formatter for human readability.
- [node-read](https://github.com/bndr/node-read) - Extract readable content from any page.


### Compression

- [Archiver](https://github.com/ctalkington/node-archiver) - A streaming interface for archive generation, supporting ZIP and TAR.
- [decompress-zip](https://github.com/bower/decompress-zip) - Unzip.


### Network

- [get-port](https://github.com/sindresorhus/get-port) - Get an available port.


### Static site generators

- [Metalsmith](http://www.metalsmith.io) - An extremely simple, pluggable static site generator.
- [Wintersmith](http://wintersmith.io) - Flexible, minimalistic, multi-platform static site generator.
- [Assemble](http://assemble.io) - Static site generator for Node.js, Grunt.js, and Yeoman.


### Content management systems

- [KeystoneJS](http://keystonejs.com) - CMS and web application platform built on Express and MongoDB.
- [Calipso](http://calip.so) - A simple content management system, built along similar themes to Drupal and Wordpress, that is designed to be fast, flexible and simple.
- [Apostrophe2](http://apostrophenow.org/) - A content management system with an emphasis on intuitive front end content editing and administration built on Express and MongoDB.


### Forum

- [nodeBB](https://nodebb.org) - A better forum platform for the modern web.


### Blogging

- [ghost](https://ghost.org) - Simple, powerful publishing platform that allows you to share your story with the world.
- [Hexo](http://hexo.io) - Fast, simple and powerful blogging framework.


### Debugging

- [node-inspector](https://github.com/node-inspector/node-inspector) - Debugger based on Blink Developer Tools.
- [Theseus](https://github.com/adobe-research/theseus) - A new type of JavaScript debugger featuring real-time code coverage, retroactive inspection and asynchronous call tree.
- [longjohn](https://github.com/mattinsler/longjohn) - Long stack traces with configurable call trace length.
- [debug](https://github.com/visionmedia/debug) - Tiny debugging utility.


### Database

- Drivers
  - [LevelUP](https://github.com/rvagg/node-levelup) - LevelDB, Node.js style.
  - [MongoDB](https://github.com/mongodb/node-mongodb-native) - Native MongoDB driver for Node.js.
  - [MySQL](https://github.com/felixge/node-mysql) - A pure Node.js JavaScript Client implementing the MySQL protocol.
  - [PostgreSQL](https://github.com/brianc/node-postgres) - PostgreSQL client for node.js. Pure JavaScript and native libpq bindings.
  - [Redis](https://github.com/mranney/node_redis) - Redis client for Node.js.
- ODM / ORM
  - [Bookshelf](http://bookshelfjs.org/) - A Node.js ORM for PostgreSQL, MySQL and SQLite3 in the style of Backbone.js.
  - [Mongoose](http://mongoosejs.com/) - Elegant MongoDB object modeling for Node.js.
  - [Sequelize](https://github.com/sequelize/sequelize) - Multi-dialect ORM. Supports SQLite, MySQL, PostgreSQL.
- Query builder
  - [Knex](http://knexjs.org/) - A query builder for PostgreSQL, MySQL and SQLite3, designed to be flexible, portable, and fun to use.


### Testing

- [tape](https://github.com/substack/tape) - [TAP](http://testanything.org)-producing test harness.
- [Mocha](http://visionmedia.github.io/mocha/) - A feature-rich test framework making asynchronous testing simple and fun.
- [loadtest](https://github.com/alexfernandez/loadtest) - Run load tests for your web application, with an API for automation.


### Minifiers

- [UglifyJS2](http://lisperator.net/uglifyjs/) - JavaScript minifier.
- [clean-css](https://github.com/GoalSmashers/clean-css) - CSS minifier.
- [minimize](https://github.com/Moveo/minimize) - HTML minifier.
- [imagemin](https://github.com/kevva/imagemin) - Image minifier.


### Authentication

- [Passport](http://passportjs.org) - Simple, unobtrusive authentication.


### Node.js management

- [n](https://github.com/visionmedia/n) - Node.js version management.
- [nave](https://github.com/isaacs/nave) - Virtual Environments for Node.js.
- [nodeenv](https://github.com/ekalinin/nodeenv) - A Node.js virtual environment compatible to Python's virtualenv.


### Polyfills

- [object-assign](https://github.com/sindresorhus/object-assign) - ES6 Object.assign() polyfill.
- [harmony-reflect](https://github.com/tvcutsem/harmony-reflect) - ES6 Reflect and Proxy polyfill.
- [es6-shim](https://github.com/paulmillr/es6-shim) - Collection of ES6 polyfills.
- More ES6 polyfills at [es6-tools](https://github.com/addyosmani/es6-tools#polyfills).


### AST

- [Esprima](http://esprima.org) - A high performance, standard-compliant JavaScript parser.
- [Rocambole](https://github.com/millermedeiros/rocambole) - Recursively walk and transform JavaScript AST.


### Weird

- [superb](https://github.com/sindresorhus/superb) - Get superb like words.
- [cool-ascii-faces](https://github.com/maxogden/cool-ascii-faces) - Get some cool ascii faces.


### Miscellaneous

- [multiline](https://github.com/sindresorhus/multiline) - Multiline strings in JavaScript.
- [opn](https://github.com/sindresorhus/opn) - Opens stuff like websites, files, executables.
- [semver](https://github.com/isaacs/node-semver) - [semver](http://semver.org) parser.
- [cheerio](https://github.com/cheeriojs/cheerio) - Fast, flexible, and lean implementation of core jQuery designed specifically for the server.
- [browserify](https://github.com/substack/node-browserify) - Browser-side require() the Node.js way.
- [Faker.js](https://github.com/Marak/Faker.js) - Generate massive amounts of fake data.


## Resources

### Tutorials

- [Nodeschool](http://nodeschool.io) - Learn Node.js with interactive lessons.
- [The Art of Node](https://github.com/maxogden/art-of-node/#the-art-of-node) - An introduction to Node.js.
- [stream-handbook](https://github.com/substack/stream-handbook) - How to write Node.js programs with streams.
- [browserify-handbook](https://github.com/substack/browserify-handbook) - The definitive guide for browserify.

### Articles

- [Error Handling in Node.js](http://www.joyent.com/developers/node/design/errors)

### Videos

- [Introduction to Node.js with Ryan Dahl](https://www.youtube.com/watch?v=jo_B4LTHi3I)

### Podcasts

- [NodeUp](http://nodeup.com)

### Books

- [Node.js in Action](http://www.amazon.com/Node-js-Action-Mike-Cantelon/dp/1617290572)
- [Mastering Node](http://visionmedia.github.io/masteringnode/)
- [Professional Node.js: Building Javascript Based Scalable Software](http://www.amazon.com/Professional-Node-js-Building-Javascript-Scalable-ebook/dp/B009L7QETY/)

### Blogs

- [Node.js blog](http://blog.nodejs.org)
- [HowToNode](http://howtonode.org) - Teaching how to do various tasks in Node.js as well as teach fundamental concepts that are needed to write effective code.

### Courses

- [Real Time Web with Node.js](http://node.codeschool.com)

### Tools

- [GitHub Linker](https://chrome.google.com/webstore/detail/github-linker/jlmafbaeoofdegohdhinkhilhclaklkp) - Chrome extension that linkifies dependencies in package.json on GitHub.


## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.


## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Sindre Sorhus](http://sindresorhus.com) has waived all copyright and related or neighboring rights to this work.
