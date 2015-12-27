# Awesome Node.js [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of delightful Node.js [packages](#packages) and [resources](#resources).

Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing.

**Check out my [blog](https://blog.sindresorhus.com) 🦄 or say *hi* on [Twitter](https://twitter.com/sindresorhus).**


## Packages

- [Mad science](#mad-science)
- [Command-line apps](#command-line-apps)
- [Functional programming](#functional-programming)
- [HTTP](#http)
- [Debugging / Profiling](#debugging--profiling)
- [Logging](#logging)
- [Command-line utilities](#command-line-utilities)
- [Build tools](#build-tools)
- [Hardware](#hardware)
- [Templating](#templating)
- [Web frameworks](#web-frameworks)
- [Documentation](#documentation)
- [Filesystem](#filesystem)
- [Control flow](#control-flow)
- [Streams](#streams)
- [Real-time](#real-time)
- [Image](#image)
- [Text](#text)
- [Number](#number)
- [Math](#math)
- [Date](#date)
- [URL](#url)
- [Data validation](#data-validation)
- [Parsing](#parsing)
- [Humanize](#humanize)
- [Compression](#compression)
- [Network](#network)
- [Database](#database)
- [Testing](#testing)
- [Benchmarking](#benchmarking)
- [Minifiers](#minifiers)
- [Authentication](#authentication)
- [Email](#email)
- [Node.js management](#nodejs-management)
- [Polyfills](#polyfills)
- [Natural language processing](#natural-language-processing)
- [Process management](#process-management)
- [Automation](#automation)
- [AST](#ast)
- [Static site generators](#static-site-generators)
- [Content management systems](#content-management-systems)
- [Forum](#forum)
- [Blogging](#blogging)
- [Weird](#weird)
- [Miscellaneous](#miscellaneous)


### Mad science

- [webtorrent](https://github.com/feross/webtorrent) - Streaming torrent client for Node.js and the browser.
- [GitTorrent](https://github.com/cjb/GitTorrent) - Peer-to-peer network of Git repositories being shared over BitTorrent.
- [peerflix](https://github.com/mafintosh/peerflix) - Streaming torrent client.
- [dat](http://dat-data.com) - Real-time replication and versioning for data sets.
- [ipfs](https://github.com/ipfs/js-ipfs) - Distributed file system that seeks to connect all computing devices with the same system of files.
- [stackgl](http://stack.gl) - Open software ecosystem for WebGL, built on top of browserify and npm.
- [peerwiki](https://github.com/mafintosh/peerwiki) - All of Wikipedia on BitTorrent.
- [peercast](https://github.com/mafintosh/peercast) - Stream a torrent video to Chromecast.
- [BitcoinJS](http://bitcoinjs.org) - Clean, readable, proven Bitcoin library.
- [Bitcore](https://bitcore.io/) - A pure and powerful Bitcoin library.
- [PDFKit](http://pdfkit.org) - PDF generation library.
- [turf](https://github.com/Turfjs/turf) - Modular geospatial processing and analysis engine.
- [webcat](https://github.com/mafintosh/webcat) - p2p pipe across the web using WebRTC that uses your GitHub private/public key for authentication.
- [js-git](https://github.com/creationix/js-git) - JavaScript implementation of Git.
- [NodeOS](http://node-os.com) - The first operating system powered by npm.
- [limdu](https://github.com/erelsgl/limdu) - Machine-learning framework.
- [Cytoscape.js](http://js.cytoscape.org) - Graph theory (a.k.a. network) modeling and analysis.


### Command-line apps

- [pageres](https://github.com/sindresorhus/pageres) - Capture website screenshots.
- [trash](https://github.com/sindresorhus/trash) - A safer alternative to `rm`.
- [npm-name](https://github.com/sindresorhus/npm-name) - Check whether a package name is available on npm.
- [XO](https://github.com/sindresorhus/xo) - Enforce strict code style using the JavaScript happiness style.
- [speed-test](https://github.com/sindresorhus/speed-test) - Test your internet connection speed and ping.
- [np](https://github.com/sindresorhus/np) - A better `npm publish`.
- [yo](https://github.com/yeoman/yo) - Run Yeoman generators.
- [ESLint](http://eslint.org) - The pluggable linting utility for JavaScript.
- [JSCS](https://github.com/jscs-dev/node-jscs) - JavaScript Code Style checker.
- [Standard](https://github.com/feross/standard) - JavaScript Standard Style — One style to rule them all.
- [cpy](https://github.com/sindresorhus/cpy) - Copy files.
- [fkill](https://github.com/sindresorhus/fkill-cli) - Fabulously kill processes. Cross-platform.
- [vantage](https://github.com/dthree/vantage) - Distributed, realtime CLI for your live app.
- [vtop](https://github.com/MrRio/vtop) - More better top, with nice charts.
- [tmpin](https://github.com/sindresorhus/tmpin) - Adds stdin support to any CLI app that accepts file input.
- [empty-trash](https://github.com/sindresorhus/empty-trash) - Empty the trash.
- [is-up](https://github.com/sindresorhus/is-up) - Check whether a website is up or down.
- [is-online](https://github.com/sindresorhus/is-online) - Check if the internet connection is up.
- [public-ip](https://github.com/sindresorhus/public-ip) - Get your public IP address.
- [dark-mode](https://github.com/sindresorhus/dark-mode) - Toggle the OS X Dark Mode.
- [ttystudio](https://github.com/chjj/ttystudio) - Record your terminal and compile it to a GIF or APNG without any external dependencies, bash scripts, gif concatenation, etc.
- [David](https://github.com/alanshaw/david) - Tells you when your package npm dependencies are out of date.
- [http-server](https://github.com/indexzero/http-server) - Simple, zero-config command-line HTTP server.
- [Live Server](https://github.com/tapio/live-server) - A simple development HTTP-server with livereload capability.
- [bcat](https://github.com/kessler/node-bcat) - Pipe command output to web browsers.
- [normit](https://github.com/pawurb/normit) - Google Translate with speech synthesis in your terminal.
- [slap](https://github.com/slap-editor/slap) - Sublime-like terminal-based text editor.
- [jsinspect](https://github.com/danielstjules/jsinspect) - Detect copy-pasted and structurally similar code.
- [esformatter](https://github.com/millermedeiros/esformatter) - JavaScript code beautifier/formatter.
- [pjs](https://github.com/danielstjules/pjs) - Pipeable JavaScript. Quickly filter, map, and reduce from the terminal.
- [license-checker](https://github.com/davglass/license-checker) - Check licenses of your app's dependencies.
- [browser-run](https://github.com/juliangruber/browser-run) - Easily run code in a browser environment.
- [modhelp](https://github.com/runvnc/modhelp) - Syntax-highlighted module READMEs in terminal with ANSI-friendly pager.
- [wifi-password](https://github.com/kevva/wifi-password) - Get the current wifi password.
- [wallpaper](https://github.com/sindresorhus/wallpaper) - Change the desktop wallpaper.
- [brightness](https://github.com/kevva/brightness-cli) - Change the screen brightness.
- [torrent](https://github.com/maxogden/torrent) - Download torrents.
- [tfa](https://github.com/jasnell/tfa) - Two-factor authentication client.
- [rtail](https://github.com/kilianc/rtail) - Terminal output to the browser in seconds, using UNIX pipes.
- [kill-tabs](https://github.com/sindresorhus/kill-tabs) - Kill all Chrome tabs to improve performance, decrease battery usage, and save memory.
- [alex](https://github.com/wooorm/alex) - Catch insensitive, inconsiderate writing.
- [pen](https://github.com/noraesae/pen) - Live Markdown preview in the browser from your favorite editor.
- [subdownloader](https://github.com/beatfreaker/subdownloader) - Subtitle downloader for movies and TV series.
- [iponmap](https://github.com/nogizhopaboroda/iponmap) - IP location finder.
- [Jsome](https://github.com/Javascipt/Jsome) - Pretty prints JSON with configurable colors and indentation.
- [itunes-remote](https://github.com/mischah/itunes-remote) - Interactively control iTunes.
- [dev-time](https://github.com/samverschueren/dev-time-cli) - Get the current local time of a GitHub user.
- [text-meme](https://github.com/beatfreaker/text-meme-cli) - Generate a text meme.
- [mobicon](https://github.com/samverschueren/mobicon-cli) - Mobile app icon generator.


### Functional programming

- [lodash](https://lodash.com/) - A utility library delivering consistency, customization, performance, & extras. A better and faster Underscore.js.
- [immutable](https://github.com/facebook/immutable-js) - Immutable data collections.
- [mori](http://swannodette.github.io/mori/) - A library for using ClojureScript's persistent data structures and supporting API from the comfort of vanilla JavaScript.
- [Ramda](http://ramdajs.com) - A utility library with a focus on flexible functional composition enabled by automatic currying and reversed argument order. Avoids mutating data.
- [Folktale](http://folktalejs.org/) - A suite of libraries for generic functional programming in JavaScript that allows you to write elegant, modular applications with fewer bugs, and more reuse.
- [underscore-contrib](http://documentcloud.github.io/underscore-contrib/) - The brass buckles on Underscore's utility belt.
- [Mout](http://moutjs.com) - Utility library with the biggest difference between other existing solutions is that you can choose to load only the modules/functions that you need, no extra overhead.
- [Bacon.js](http://baconjs.github.io) - Functional reactive programming.
- [RxJS](http://reactivex.io) - Functional reactive library for transforming, composing, and querying various kinds of data.
- [Lazy.js](https://github.com/dtao/lazy.js) - Utility library similar to lodash/Underscore but with lazy evaluation, which can translate to superior performance in many cases.


### HTTP

- [got](https://github.com/sindresorhus/got) - A nicer interface to the built-in `http` module.
- [gh-got](https://github.com/sindresorhus/gh-got) - Convenience wrapper for `got` to interact with the GitHub API.
- [request](https://github.com/request/request) - Simplified HTTP request client.
- [Nock](https://github.com/pgte/nock) - A HTTP mocking and expectations library.
- [hyperquest](https://github.com/substack/hyperquest) - Streaming HTTP requests.
- [axios](https://github.com/mzabriskie/axios) - Promise based HTTP client (works in the browser too).
- [spdy](https://github.com/indutny/node-spdy) - Creates SPDY servers with the same API as the built-in `https` module.
- [wreck](https://github.com/hapijs/wreck) - HTTP Client Utilities.
- [download](https://github.com/kevva/download) - Download and extract files effortlessly.
- [http-proxy](https://github.com/nodejitsu/node-http-proxy) - A full-featured HTTP proxy.
- [rocky](https://github.com/h2non/rocky) - Featured, middleware-oriented HTTP proxy with traffic replay and intercept.
- [superagent](https://github.com/visionmedia/superagent) - A small progressive HTTP request library.


### Debugging / Profiling

- [ironNode](https://github.com/s-a/iron-node) - Node.js debugger supporting ES2015 out of the box.
- [node-inspector](https://github.com/node-inspector/node-inspector) - Debugger based on Blink Developer Tools.
- [Theseus](https://github.com/adobe-research/theseus) - A new type of JavaScript debugger featuring real-time code coverage, retroactive inspection and asynchronous call tree.
- [longjohn](https://github.com/mattinsler/longjohn) - Long stack traces with configurable call trace length.
- [debug](https://github.com/visionmedia/debug) - Tiny debugging utility.
- [jstrace](https://github.com/jstrace/jstrace) - Dynamic tracing for JavaScript, similar to dtrace, ktap etc.
- [njsTrace](https://github.com/valyouw/njstrace) - Instrument and trace your code, see all function calls, arguments, return values, as well as the time spent in each function.
- [vstream](https://github.com/joyent/node-vstream) - Instrumentable streams mix-ins to inspect a pipeline of streams.
- [stackman](https://github.com/watson/stackman) - Enhance an error stacktrace with code excerpts and other goodies.
- [TraceGL](https://github.com/traceglMPL/tracegl) - Transforms your JavaScript, injecting monitoring code that produces a log of everything that happens.
- [locus](https://github.com/alidavut/locus) - Starts a REPL at runtime that has access to all variables.


### Logging

- [winston](https://github.com/winstonjs/winston) - A multi-transport async logging library.
- [Bunyan](https://github.com/trentm/node-bunyan) - A simple and fast JSON logging library.
- [intel](http://seanmonstar.github.io/intel/) - A comprehensive logging library (handlers, filters, formatters, console injection).
- [console-log-level](https://github.com/watson/console-log-level) - The most simple logger imaginable with support for log levels and custom prefixes.


### Command-line utilities

- [chalk](https://github.com/chalk/chalk) - Terminal string styling done right.
- [meow](https://github.com/sindresorhus/meow) - CLI app helper.
- [minimist](https://github.com/substack/minimist) - Parse command-line flags.
- [get-stdin](https://github.com/sindresorhus/get-stdin) - Easier stdin.
- [user-home](https://github.com/sindresorhus/user-home) - Get the path to the user home directory.
- [log-update](https://github.com/sindresorhus/log-update) - Log by overwriting the previous output in the terminal. Useful for rendering progress bars, animations, etc.
- [Inquirer.js](https://github.com/SBoudrias/Inquirer.js) - Interactive command-line prompt.
- [update-notifier](https://github.com/yeoman/update-notifier) - Update notifications for your CLI app.
- [ansi-escapes](https://github.com/sindresorhus/ansi-escapes) - ANSI escape codes for manipulating the terminal.
- [sudo-block](https://github.com/sindresorhus/sudo-block) - Block users from running your app with root permissions.
- [configstore](https://github.com/yeoman/configstore) - Easily load and persist config without having to think about where and how.
- [insight](https://github.com/yeoman/insight) - Helps you understand how your tool is being used by anonymously reporting usage metrics to Google Analytics.
- [log-symbols](https://github.com/sindresorhus/log-symbols) - Colored symbols for various log levels.
- [figures](https://github.com/sindresorhus/figures) - Unicode symbols with Windows CMD fallbacks.
- [string-width](https://github.com/sindresorhus/string-width) - Get the visual width of a string - the number of columns required to display it.
- [first-run](https://github.com/sindresorhus/first-run) - Check if it's the first time the process is run.
- [sparkly](https://github.com/sindresorhus/sparkly) - Generate sparklines ▁▂▃▅▂▇
- [vorpal](https://github.com/dthree/vorpal) - A framework for interactive CLI apps.
- [blessed](https://github.com/chjj/blessed) - A curses-like library.
- [yn](https://github.com/sindresorhus/yn) - Parse yes/no like values.
- [cli-table](https://github.com/Automattic/cli-table) - Pretty unicode tables.
- [drawille](https://github.com/madbence/node-drawille) - Draw on the terminal with unicode braille characters.
- [googleauth](https://github.com/maxogden/googleauth) - Create and load persistent Google authentication tokens for command-line apps.
- [ascii-charts](https://github.com/jstrace/chart) - ASCII bar chart in the terminal.
- [progress](https://github.com/tj/node-progress) - Flexible ascii progress bar.
- [cli-cursor](https://github.com/sindresorhus/cli-cursor) - Toggle the CLI cursor.
- [columnify](https://github.com/timoxley/columnify) - Create text-based columns suitable for console output. Supports cell wrapping.
- [cfonts](https://github.com/dominikwilkowski/cfonts) - Sexy ASCII fonts for the console.
- [multispinner](https://github.com/codekirei/node-multispinner) - Multiple, simultaneous, individually controllable CLI spinners.


### Build tools

- [gulp](http://gulpjs.com) - Streaming and fast build system that favors code over config.
- [Broccoli](https://github.com/broccolijs/broccoli) - A fast, reliable asset pipeline, supporting constant-time rebuilds and compact build definitions.
- [browserify](https://github.com/substack/node-browserify) - Browser-side require() the Node.js way.
- [webpack](https://github.com/webpack/webpack) - Packs modules and assets for the browser.
- [Brunch](https://github.com/brunch/brunch) - Front-end web app build tool with simple declarative config, fast incremental compilation, and an opinionated workflow.
- [strong-build](https://github.com/strongloop/strong-build) - Build a node app package and prepare to deploy it as a package to production or use git to commit to a deploy branch.
- [grunt](http://gruntjs.com) - Task runner that can perform repetitive tasks like minification, compilation, unit testing, linting, etc.


### Hardware

- [johnny-five](https://github.com/rwaldron/johnny-five) - Firmata based Arduino Framework.
- [serialport](https://github.com/voodootikigod/node-serialport) - Access serial ports for reading and writing.
- [usb](https://github.com/nonolith/node-usb) - USB library.
- [cylon.js](http://cylonjs.com) - Next generation robotics framework with support for 26 different platforms.
- [i2c-bus](https://github.com/fivdi/i2c-bus) - I2C serial bus access.


### Templating

- [marko](https://github.com/marko-js/marko) - A fast and lightweight HTML-based templating engine that compiles templates to CommonJS modules and supports streaming, async rendering and custom tags.
- [nunjucks](https://github.com/mozilla/nunjucks) - A powerful templating engine with inheritance, asynchronous control, and more (jinja2 inspired).
- [handlebars.js](https://github.com/wycats/handlebars.js) - A superset of Mustache templates which adds powerful features like helpers and more advanced blocks.
- [hogan.js](http://twitter.github.io/hogan.js/) - Twitter's small, fast, phase-separated compiler for Mustache templates.
- [EJS](https://github.com/mde/ejs) - Simple unopinionated templating language.
- [Jade](https://github.com/jadejs/jade) - High-performance template engine heavily influenced by Haml.


### Web frameworks

- [Koa](http://koajs.com) - A new web framework designed by the team behind Express, which aims to be a smaller, more expressive, and more robust foundation for web applications and APIs.
- [Express](http://expressjs.com) - A minimal and flexible web application framework, providing a robust set of features for building single and multi-page, and hybrid web applications.
- [Hapi](http://hapijs.com) - A rich framework for building applications and services.
- [LoopBack](http://loopback.io) - Powerful framework for creating REST APIs and easily connecting to backend data sources.
- [Meteor](https://www.meteor.com) - An ultra-simple, database-everywhere, data-on-the-wire, pure-Javascript web framework. *(You might like [awesome-meteor](https://github.com/Urigo/awesome-meteor))*
- [SailsJS](http://sailsjs.org) - An MVC web framework with a modern twist, supporting WebSockets, streams, and a data-driven API.
- [Restify](http://restify.com) - A node framework built specifically to enable you to build correct REST web services.
- [Interfake](https://github.com/basicallydan/interfake) - Rapid prototyping framework for making mock HTTP APIs, with a Node.js, command-line and HTTP interface.
- [Derby](https://github.com/derbyjs/derby) - MVC framework, making it easy to write realtime, collaborative applications that run in both Node.js and browsers.
- [Restberry](http://restberry.com) - Framework for setting up RESTful JSON APIs, applied to your database models without needing to write any code.
- [Catberry](http://catberry.org) - Framework with Flux architecture, isomorphic web-components, and progressive rendering.


### Documentation

- [Docco](http://jashkenas.github.io/docco/) - A quick-and-dirty documentation generator which produces an HTML document that displays your comments intermingled with your code.
- [JSDoc](http://usejsdoc.org) - API documentation generator similar to JavaDoc or PHPDoc.
- [dox](https://github.com/tj/dox) - JavaScript documentation generator using Markdown and JSDoc.
- [jsdox](https://github.com/sutoiku/jsdox) - JSDoc3 to Markdown documentation generator.
- [apiDoc](https://github.com/apidoc/apidoc) - Inline documentation for RESTful web APIs.


### Filesystem

- [del](https://github.com/sindresorhus/del) - Delete files/folders using globs.
- [globby](https://github.com/sindresorhus/globby) - Glob files with support for multiple patterns.
- [cpy](https://github.com/sindresorhus/cpy) - Copy files.
- [rimraf](https://github.com/isaacs/rimraf) - Recursively delete files like `rm -rf`.
- [mkdirp](https://github.com/substack/node-mkdirp) - Recursively create directories like `mkdir -p`.
- [graceful-fs](https://github.com/isaacs/node-graceful-fs) - Drop-in replacement for the `fs` module with various improvements.
- [chokidar](https://github.com/paulmillr/chokidar) - Filesystem watcher which stabilizes events from `fs.watch` and `fs.watchFile` as well as using native `fsevents` on OS X.
- [find-up](https://github.com/sindresorhus/find-up) - Find a file by walking up parent directories.
- [load-json-file](https://github.com/sindresorhus/load-json-file) - Read and parse a JSON file.
- [write-json-file](https://github.com/sindresorhus/write-json-file) - Stringify and write JSON to a file atomically.
- [fs-write-stream-atomic](https://github.com/npm/fs-write-stream-atomic) - Like `fs.createWriteStream()`, but atomic.
- [filenamify](https://github.com/sindresorhus/filenamify) - Convert a string to a valid filename.
- [lnfs](https://github.com/kevva/lnfs) - Force create symlinks like `ln -fs`.
- [istextorbinary](https://github.com/bevry/istextorbinary) - Check if a file is text or binary.
- [fs-jetpack](https://github.com/szwacz/fs-jetpack) - Completely redesigned file system API for convenience in everyday use.
- [fs-extra](https://github.com/jprichardson/node-fs-extra) - Extra methods for the `fs` module.
- [pkg-dir](https://github.com/sindresorhus/pkg-dir) - Find the root directory of a npm package.


### Control flow

- Promises
	- [Bluebird](https://github.com/petkaantonov/bluebird) - A fully featured promise library with focus on innovative features and performance.
	- [pinkie-promise](https://github.com/floatdrop/pinkie-promise) - Promise ponyfill.
	- [pify](https://github.com/sindresorhus/pify) - Promisify a callback-style function.
- Callbacks
	- [each-async](https://github.com/sindresorhus/each-async) - Async concurrent iterator like forEach.
	- [async](https://github.com/caolan/async) - Provides straight-forward, powerful functions for working with asynchronicity.
	- [async-chainable](https://github.com/hash-bang/async-chainable) - Chainable, pluggable async functionality.
	- [after-all-results](https://github.com/watson/after-all-results) - Bundle results of async functions calls into one callback with all the results.
- Generators
	- [co](https://github.com/tj/co) - The ultimate generator based flow-control goodness.
	- [suspend](https://github.com/jmar777/suspend) - Generator-based control flow that plays nice with callbacks, promises, and thunks.
	- [bluebird-co](https://github.com/novacrazy/bluebird-co) - A set of high performance yield handlers for Bluebird coroutines.
- Streams
	- [Highland.js](http://highlandjs.org) - Manages synchronous and asynchronous code easily, using nothing more than standard JavaScript and Node-like Streams.
- Channels
	- [js-csp](https://github.com/jlongster/js-csp) - Communicating sequential processes for JavaScript (like Clojurescript core.async, or Go).
- Other
	- [zone](https://github.com/strongloop/zone) - Provides a way to group and track resources and errors across asynchronous operations.


### Streams

- [through2](https://github.com/rvagg/through2) - Tiny wrapper around streams2 Transform to avoid explicit subclassing noise.
- [from2](https://github.com/hughsk/from2) - Convenience wrapper for ReadableStream, inspired by `through2`.
- [get-stream](https://github.com/sindresorhus/get-stream) - Get a stream as a string or buffer.
- [concat-stream](https://github.com/maxogden/concat-stream) - Concatenates a stream into strings or binary data.
- [into-stream](https://github.com/sindresorhus/into-stream) - Convert a buffer/string/array/object into a stream.
- [duplexify](https://github.com/mafintosh/duplexify) - Turn a writeable and readable stream into a single streams2 duplex stream.
- [pumpify](https://github.com/mafintosh/pumpify) - Combine an array of streams into a single duplex stream.
- [peek-stream](https://github.com/mafintosh/peek-stream) - Transform stream that lets you peek the first line before deciding how to parse it.
- [binary-split](https://github.com/maxogden/binary-split) - A fast newline (or any delimiter) splitter stream.
- [byline](https://github.com/jahewson/node-byline) - Super-simple line-by-line Stream reader.
- [first-chunk-stream](https://github.com/sindresorhus/first-chunk-stream) - Transform the first chunk in a stream.
- [pad-stream](https://github.com/sindresorhus/pad-stream) - Pad each line in a stream.
- [multistream](https://github.com/feross/multistream) - Combine multiple streams into a single stream.
- [stream-combiner2](https://github.com/substack/stream-combiner2) - Turn a pipeline into a single stream.
- [readable-stream](https://github.com/nodejs/readable-stream) - Mirror of Streams2 and Streams3 implementations in core.
- [through2-concurrent](https://github.com/almost/through2-concurrent) - Transform object streams concurrently.
- [graphicsmagick-stream](https://github.com/e-conomic/graphicsmagick-stream) - Fast conversion/scaling of images using a pool of long lived GraphicsMagick processes.


### Real-time

- [Socket.io](http://socket.io) - Enables real-time bidirectional event-based communication.
- [SockJS](https://github.com/sockjs/sockjs-node) - Low latency, full duplex, cross-domain channel browser-server, with WebSockets or without.
- [Faye](http://faye.jcoglan.com) - Real-time client-server message bus, based on Bayeux protocol.
- [SocketCluster](https://github.com/SocketCluster/socketcluster) - Scalable HTTP + WebSocket engine which can run on multiple CPU cores.
- [Primus](https://github.com/primus/primus) - An abstraction layer for real-time frameworks to prevent module lock-in.
- [Straw](https://github.com/simonswain/straw) - Real-time dataflow framework.


### Image

- [sharp](https://github.com/lovell/sharp) - The fastest module for resizing JPEG, PNG, WebP and TIFF images.
- [image-type](https://github.com/sindresorhus/image-type) - Detect the image type of a Buffer/Uint8Array.
- [gm](https://github.com/aheckmann/gm) - GraphicsMagick and ImageMagick wrapper.
- [lwip](https://github.com/EyalAr/lwip) - Lightweight image processor which does not require ImageMagick.
- [pica](https://github.com/nodeca/pica) - High quality & fast resize (lanczos3) in pure JS. Alternative to canvas drawImage(), when no pixelation allowed.
- [jimp](https://github.com/oliver-moran/jimp) - Image processing in pure JavaScript.
- [is-progressive](https://github.com/sindresorhus/is-progressive) - Check if a JPEG image is progressive.
- [probe-image-size](https://github.com/nodeca/probe-image-size) - Get the size of most image formats without a full download.


### Text

- [Underscore.string](https://github.com/epeli/underscore.string) - Collection of string manipulation utilities.
- [iconv-lite](https://github.com/ashtuchkin/iconv-lite) - Convert character encodings.
- [repeating](https://github.com/sindresorhus/repeating) - Repeat a string.
- [string-length](https://github.com/sindresorhus/string-length) - Get the real length of a string - by correctly counting astral symbols and ignoring ansi escape codes.
- [camelcase](https://github.com/sindresorhus/camelcase) - Convert a dash/dot/underscore/space separated string to camelCase: foo-bar → fooBar.
- [escape-string-regexp](https://github.com/sindresorhus/escape-string-regexp) - Escape RegExp special characters.
- [execall](https://github.com/sindresorhus/execall) - Find multiple RegExp matches in a string.
- [splice-string](https://github.com/sindresorhus/splice-string) - Remove or replace part of a string like `Array#splice`.
- [indent-string](https://github.com/sindresorhus/indent-string) - Indent each line in a string.
- [strip-indent](https://github.com/sindresorhus/strip-indent) - Strip leading whitespace from every line in a string.
- [detect-indent](https://github.com/sindresorhus/detect-indent) - Detect the indentation of code.
- [he](https://github.com/mathiasbynens/he) - A robust HTML entity encoder/decoder.
- [i18n-node](https://github.com/mashpie/i18n-node) - Simple translation module with dynamic JSON storage.
- [babelfish](https://github.com/nodeca/babelfish/) - i18n with very easy syntax for plurals.
- [parse-columns](https://github.com/sindresorhus/parse-columns) - Parse text columns, like the output of Unix commands.
- [hanging-indent](https://github.com/codekirei/hanging-indent) - Format a string into a hanging-indented paragraph.


## Number

- [random-int](https://github.com/sindresorhus/random-int) - Generate a random integer.
- [random-float](https://github.com/sindresorhus/random-float) - Generate a random float.
- [unique-random](https://github.com/sindresorhus/unique-random) - Generate random numbers that are consecutively unique.
- [round-to](https://github.com/sindresorhus/round-to) - Round a number to a specific number of decimal places: `1.234` → `1.2`.


### Math

- [ndarray](https://github.com/scijs/ndarray) - Multidimensional arrays.
- [mathjs](https://github.com/josdejong/mathjs) - An extensive math library.
- [math-sum](https://github.com/sindresorhus/math-sum) - Sum numbers.
- [math-clamp](https://github.com/sindresorhus/math-clamp) - Clamp a number.


### Date

- [Moment.js](http://momentjs.com) - Parse, validate, manipulate, and display dates.
- [Moment Timezone](http://momentjs.com/timezone/) - IANA Time Zone Database + Moment.js.
- [dateformat](https://github.com/felixge/node-dateformat) - Date formatting.


### URL

- [normalize-url](https://github.com/sindresorhus/normalize-url) - Normalize a URL.
- [humanize-url](https://github.com/sindresorhus/humanize-url) - Humanize a URL: http://sindresorhus.com → sindresorhus.com.
- [url-unshort](https://github.com/nodeca/url-unshort) - Expand shortened URLs.
- [speakingurl](https://github.com/pid/speakingurl) - Generate a slug from a string with transliteration.
- [linkify-it](https://github.com/markdown-it/linkify-it) - Link patterns detector with full unicode support.
- [url-pattern](https://github.com/snd/url-pattern) - Easier than regex string matching patterns for URLs and other strings.
- [embedza](https://github.com/nodeca/embedza) - Create HTML snippets/embeds from URLs using info from oEmbed, Open Graph, meta tags.


### Data validation

- [joi](https://github.com/hapijs/joi) - Object schema description language and validator for JavaScript objects.
- [is-my-json-valid](https://github.com/mafintosh/is-my-json-valid) - JSON Schema validator that uses code generation to be extremely fast.


### Parsing

- [remark](https://github.com/wooorm/remark) - Markdown processor powered by plugins.
- [markdown-it](https://github.com/markdown-it/markdown-it) - A very fast markdown parser with 100% CommonMark support, extensions and syntax plugins.
- [parse5](https://github.com/inikulin/parse5) - Fast full-featured spec compliant HTML parser.
- [strip-json-comments](https://github.com/sindresorhus/strip-json-comments) - Strip comments from JSON.
- [strip-css-comments](https://github.com/sindresorhus/strip-css-comments) - Strip comments from CSS.
- [parse-json](https://github.com/sindresorhus/parse-json) - Parse JSON with more helpful errors.
- [URI.js](https://github.com/medialize/URI.js) - URL mutation.
- [PostCSS](https://github.com/postcss/postcss) - CSS parser / stringifier.
- [JSONStream](https://github.com/dominictarr/JSONStream) - Streaming JSON.parse and stringify.
- [csv-parser](https://github.com/mafintosh/csv-parser) - Streaming CSV parser that aims to be faster than everyone else.
- [neat-csv](https://github.com/sindresorhus/neat-csv) - Fast CSV parser. Callback interface for the above.
- [PEG.js](https://github.com/pegjs/pegjs) - Simple parser generator that produces fast parsers with excellent error reporting.
- [x-ray](https://github.com/lapwinglabs/x-ray) - A web scraping utility to see through the `<html>` noise.
- [nearley](https://github.com/Hardmath123/nearley) - Simple, fast, powerful parsing for JavaScript.
- [binary-extract](https://github.com/juliangruber/binary-extract) - Extract a value from a buffer of JSON without parsing the whole thing.
- [json-mask](https://github.com/nemtsov/json-mask) - Tiny language and engine for selecting parts of an object, hiding/masking the rest.
- [Stylecow](https://github.com/stylecow/stylecow) - Parse, manipulate and convert modern CSS to make it compatible with all browsers. Extensible with plugins.
- [js-yaml](https://github.com/nodeca/js-yaml) - Very fast YAML parser.
- [excel-stream](https://github.com/dominictarr/excel-stream) - Streaming Excel spreadsheet to JSON parser.
- [xml2js](https://github.com/Leonidas-from-XIV/node-xml2js) - XML to JavaScript object converter.
- [Jison](http://zaach.github.io/jison/) - Friendly JavaScript parser generator. It shares genes with Bison, Yacc and family.


### Humanize

- [pretty-bytes](https://github.com/sindresorhus/pretty-bytes) - Convert bytes to a human readable string: `1337` → `1.34 kB`.
- [pretty-ms](https://github.com/sindresorhus/pretty-ms) - Convert milliseconds to a human readable string: `1337000000` → `15d 11h 23m 20s`.
- [ms](https://github.com/rauchg/ms.js) - Tiny millisecond conversion utility.
- [pretty-error](https://github.com/AriaMinaei/pretty-error) - Errors with less clutter.
- [humanize](https://github.com/taijinlee/humanize) - Data formatter for human readability.
- [read-art](https://github.com/Tjatse/node-readability) - Extract readable content from any page.


### Compression

- [Archiver](https://github.com/archiverjs/node-archiver) - Streaming interface for archive generation, supporting ZIP and TAR.
- [decompress-zip](https://github.com/bower/decompress-zip) - Unzip.
- [pako](https://github.com/nodeca/pako) - High speed zlib port to pure js (deflate, inflate, gzip).
- [tar-stream](https://github.com/mafintosh/tar-stream) - Streaming tar parser and generator. Also see [tar-fs](https://github.com/mafintosh/tar-fs).
- [decompress](https://github.com/kevva/decompress) - A pluggable decompression module with support for `tar`, `tar.gz` and `zip` files out of the box.


### Network

- [get-port](https://github.com/sindresorhus/get-port) - Get an available port.
- [ipify](https://github.com/sindresorhus/ipify) - Get your public IP address.
- [getmac](https://github.com/bevry/getmac) - Get the computer MAC address.


### Database

- Drivers
	- [LevelUP](https://github.com/Level/levelup) - LevelDB.
	- [MongoDB](https://github.com/mongodb/node-mongodb-native) - MongoDB driver.
	- [PostgreSQL](https://github.com/brianc/node-postgres) - PostgreSQL client. Pure JavaScript and native libpq bindings.
	- [MySQL](https://github.com/felixge/node-mysql) - MySQL client.
	- [Redis](https://github.com/luin/ioredis) - Redis client.
- ODM / ORM
	- [Bookshelf](http://bookshelfjs.org) - ORM for PostgreSQL, MySQL and SQLite3 in the style of Backbone.js.
	- [Massive](https://github.com/robconery/massive-js) - PostgreSQL data access tool.
	- [Mongoose](http://mongoosejs.com) - Elegant MongoDB object modeling.
	- [Sequelize](https://github.com/sequelize/sequelize) - Multi-dialect ORM. Supports PostgreSQL, SQLite, MySQL.
	- [Waterline](https://github.com/balderdashy/waterline) - Datastore-agnostic tool that dramatically simplifies interaction with one or more databases.
	- [Iridium](https://github.com/SierraSoftworks/Iridium) - A high performance MongoDB ORM with support for promises, distributed caching, preprocessing, validation and plugins.
	- [OpenRecord](https://github.com/PhilWaldmann/openrecord) - ORM for PostgreSQL, MySQL, SQLite3 and RESTful datastores. Similar to ActiveRecord.
	- [orm2](https://github.com/dresende/node-orm2) - ORM for PostgreSQL, MariaDB, MySQL, Amazon Redshift, SQLite, MongoDB.
	- [firenze](https://github.com/fahad19/firenze) - Adapter-based ORM for MySQL, Memory, Redis, localStorage and more.
- Query builder
	- [Knex](http://knexjs.org) - A query builder for PostgreSQL, MySQL and SQLite3, designed to be flexible, portable, and fun to use.
- Other
	- [NeDB](https://github.com/louischatriot/nedb) - Embedded persistent database written in JavaScript.


### Testing

- [AVA](https://ava.li) - Futuristic test runner.
- [tap](https://github.com/isaacs/node-tap) - A TAP test framework.
- [tape](https://github.com/substack/tape) - TAP-producing test harness.
- [Mocha](http://mochajs.org) - A feature-rich test framework making asynchronous testing simple and fun.
- [Mochify](https://github.com/mantoni/mochify.js) - TDD with Browserify, Mocha, PhantomJS and WebDriver.
- [trevor](https://github.com/vdemedes/trevor) - Run tests against multiple versions of Node.js without switching versions manually or pushing to Travis CI.
- [loadtest](https://github.com/alexfernandez/loadtest) - Run load tests for your web application, with an API for automation.
- [istanbul](https://github.com/gotwarlost/istanbul) - A code coverage tool that computes statement, line, function and branch coverage with module loader hooks to transparently add coverage when running tests.
- [nyc](https://github.com/bcoe/nyc) - Code coverage tool built on istanbul that works with subprocesses.
- [Sinon.JS](https://github.com/sinonjs/sinon) - Test spies, stubs and mocks.
- [navit](https://github.com/nodeca/navit) - PhantomJS / SlimerJS wrapper to simplify browser test scripting.
- [nock](https://github.com/pgte/nock) - HTTP mocking and expectations.
- [intern](https://github.com/theintern/intern) - A next-generation code testing stack for JavaScript.
- [toxy](https://github.com/h2non/toxy) - Hackable HTTP proxy to simulate failure scenarios and network conditions.


### Benchmarking

- [Benchmark.js](http://benchmarkjs.com) - A robust benchmarking library that works on nearly all JavaScript platforms, supports high-resolution timers, and returns statistically significant results.
- [matcha](https://github.com/logicalparadox/matcha) - A caffeine-driven, simplistic approach to benchmarking.


### Minifiers

- [UglifyJS2](http://lisperator.net/uglifyjs/) - JavaScript minifier.
- [clean-css](https://github.com/jakubpawlowicz/clean-css) - CSS minifier.
- [minimize](https://github.com/Swaagie/minimize) - HTML minifier.
- [imagemin](https://github.com/imagemin/imagemin) - Image minifier.


### Authentication

- [Passport](http://passportjs.org) - Simple, unobtrusive authentication.
- [everyauth](https://github.com/bnoguchi/everyauth) - Authentication and authorization (password, Facebook, etc) for your Connect and Express apps.
- [passwordless](https://passwordless.net) - Token-based authentication middleware for Express allowing authentication without passwords.
- [Lockit](https://github.com/zemirco/lockit) - Full featured authentication solution for Express. Supports a variety of databases, predefined routes, email and two-factor authentication.
- [Grant](https://github.com/simov/grant) - OAuth middleware for Express, Koa, and Hapi.


### Email

- [Nodemailer](https://github.com/andris9/Nodemailer) - The fastest way to handle email.
- [emailjs](https://github.com/eleith/emailjs) - Send text/HTML emails with attachments to any SMTP server.


### Node.js management

- [n](https://github.com/tj/n) - Node.js version management.
- [nave](https://github.com/isaacs/nave) - Virtual Environments for Node.js.
- [nodeenv](https://github.com/ekalinin/nodeenv) - A Node.js virtual environment compatible to Python's virtualenv.
- [nvm for Windows](https://github.com/coreybutler/nvm-windows) - Version management for Windows.


### Polyfills

- Node.js
	- [set-immediate-shim](https://github.com/sindresorhus/set-immediate-shim) - Simple `setImmediate()` ponyfill.
	- [path-is-absolute](https://github.com/sindresorhus/path-is-absolute) - Node.js 0.12 `path.isAbsolute()` ponyfill.
	- [os-tmpdir](https://github.com/sindresorhus/os-tmpdir) - Node.js `os.tmpdir()` ponyfill.
	- [os-homedir](https://github.com/sindresorhus/os-homedir) - Node.js 4.0 `os.homedir()` ponyfill.
	- [debug-log](https://github.com/sindresorhus/debug-log) - Node.js 0.12 `util.debuglog()` ponyfill.
	- [buffer-equals](https://github.com/sindresorhus/buffer-equals) - Node.js 0.12 `buffer.equals()` ponyfill.
	- [buf-indexof](https://github.com/sindresorhus/buf-indexof) - Node.js 4.0 `buffer.indexOf()` ponyfill.
	- [buf-compare](https://github.com/sindresorhus/buf-compare) - Node.js 0.12 `Buffer.compare()` ponyfill.
	- [fs-access](https://github.com/sindresorhus/fs-access) - Node.js 0.12 `fs.access()` & `fs.accessSync()` ponyfill.
	- [exec-file-sync](https://github.com/sindresorhus/exec-file-sync) - Node.js 0.12 `childProcess.execFileSync()` ponyfill.
	- [child-process-ctor](https://github.com/sindresorhus/child-process-ctor) - Node.js 4.0 `childProcess.ChildProcess` ponyfill.
	- [node-status-codes](https://github.com/sindresorhus/node-status-codes) - Node.js `http.STATUS_CODES` ponyfill.
	- [exit-code](https://github.com/isaacs/exit-code) - Node.js 0.12 `process.exitCode` polyfill.
	- [core-assert](https://github.com/sindresorhus/core-assert) - Node.js `assert` as a standalone module.
	- [deep-strict-equal](https://github.com/sindresorhus/deep-strict-equal) - Test for deep equality - Node.js `assert.deepStrictEqual()` algorithm as a standalone module.
- JavaScript
	- [object-assign](https://github.com/sindresorhus/object-assign) - ES2015 `Object.assign()` ponyfill.
	- [pinkie-promise](https://github.com/floatdrop/pinkie-promise) - ES2015 `Promise` ponyfill.
	- [harmony-reflect](https://github.com/tvcutsem/harmony-reflect) - ES2015 `Reflect` and `Proxy` polyfill.
	- [es6-shim](https://github.com/paulmillr/es6-shim) - Collection of ES2015 polyfills.
	- More ES2015 polyfills at [es6-tools](https://github.com/addyosmani/es6-tools#polyfills).


### Natural language processing

- [retext](https://github.com/wooorm/retext) - An extensible natural language system.
- [franc](https://github.com/wooorm/franc) - Detect the language of text.
- [leven](https://github.com/sindresorhus/leven) - Measure the difference between two strings using the Levenshtein distance algorithm.
- [natural](https://github.com/NaturalNode/natural) - A general natural language facility.


### Process management

- [PM2](https://github.com/Unitech/pm2) - Advanced Process Manager.
- [node-windows](https://github.com/coreybutler/node-windows) - Run scripts as a native Windows service and log to the Event viewer.
- [node-mac](https://github.com/coreybutler/node-mac) - Run scripts as a native Mac daemon and log to the console app.
- [node-linux](https://github.com/coreybutler/node-linux) - Run scripts as native system service and log to syslog.
- [forever](https://github.com/foreverjs/forever) - A simple CLI tool for ensuring that a given script runs continuously (i.e. forever).
- [nodemon](https://github.com/remy/nodemon) - Monitor for changes in your app and automatically restart the server.
- [supervisor](https://github.com/petruisfan/node-supervisor) - Restart scripts when they crash or restart when a `*.js` file changes.
- [Phusion Passenger](https://www.phusionpassenger.com/node_weekly) - Friendly process manager that integrates directly into Nginx.
- [naught](https://github.com/andrewrk/naught) - Process manager with zero downtime deployment.


### Automation

- [robotjs](https://github.com/octalmage/robotjs) -  Desktop Automation: control the mouse, keyboard and read the screen.


### AST

- [Acorn](https://github.com/ternjs/acorn) - A tiny, fast JavaScript parser.
- [Rocambole](https://github.com/millermedeiros/rocambole) - Recursively walk and transform JavaScript AST.


### Static site generators

- [Metalsmith](http://www.metalsmith.io) - An extremely simple, pluggable static site generator.
- [Wintersmith](http://wintersmith.io) - Flexible, minimalistic, multi-platform static site generator.
- [Assemble](http://assemble.io) - Static site generator for Node.js, Grunt.js, and Yeoman.
- [DocPad](https://github.com/docpad/docpad) - Static site generator with dynamic abilities and huge plugin ecosystem.


### Content management systems

- [KeystoneJS](http://keystonejs.com) - CMS and web application platform built on Express and MongoDB.
- [Calipso](http://calip.so) - A simple content management system, built along similar themes to Drupal and Wordpress, that is designed to be fast, flexible and simple.
- [Apostrophe2](http://apostrophenow.org) - A content management system with an emphasis on intuitive front end content editing and administration built on Express and MongoDB.


### Forum

- [nodeBB](https://nodebb.org) - A better forum platform for the modern web.


### Blogging

- [ghost](https://ghost.org) - Simple, powerful publishing platform that allows you to share your story with the world.
- [Hexo](https://hexo.io/) - Fast, simple and powerful blogging framework.


### Weird

- [superb](https://github.com/sindresorhus/superb) - Get superb like words.
- [cat-names](https://github.com/sindresorhus/cat-names) - Get popular cat names.
- [dog-names](https://github.com/sindresorhus/dog-names) - Get popular dog names.
- [superheroes](https://github.com/sindresorhus/superheroes) - Get superhero names.
- [supervillains](https://github.com/sindresorhus/supervillains) - Get supervillain names.
- [cool-ascii-faces](https://github.com/maxogden/cool-ascii-faces) - Get some cool ascii faces.
- [cat-ascii-faces](https://github.com/melaniecebula/cat-ascii-faces) - ₍˄·͈༝·͈˄₎◞ ̑̑ෆ⃛ (=ↀωↀ=)✧ (^･o･^)ﾉ”


### Miscellaneous

- [cheerio](https://github.com/cheeriojs/cheerio) - Fast, flexible, and lean implementation of core jQuery designed specifically for the server.
- [Electron](https://github.com/atom/electron) - Build cross platform desktop apps with web technologies. *(You might like [awesome-electron](https://github.com/sindresorhus/awesome-electron))*
- [opn](https://github.com/sindresorhus/opn) - Opens stuff like websites, files, executables.
- [hasha](https://github.com/sindresorhus/hasha) - Hashing made simple. Get the hash of a buffer/string/stream/file.
- [dot-prop](https://github.com/sindresorhus/dot-prop) - Get a property from a nested object using a dot path.
- [onetime](https://github.com/sindresorhus/onetime) - Only run a function once.
- [require-uncached](https://github.com/sindresorhus/require-uncached) - Require a module bypassing the cache.
- [stringify-object](https://github.com/yeoman/stringify-object) - Stringify an object/array like JSON.stringify just without all the double-quotes.
- [strip-bom](https://github.com/sindresorhus/strip-bom) - Strip UTF-8 byte order mark (BOM) from a string/buffer/stream.
- [deep-assign](https://github.com/sindresorhus/deep-assign) - Recursive `Object.assign()`.
- [shelljs](https://github.com/shelljs/shelljs) - Portable Unix shell commands.
- [os-locale](https://github.com/sindresorhus/os-locale) - Get the system locale.
- [nan](https://github.com/nodejs/nan) - A header file filled with macro and utility goodness for making add-on development for across Node.js versions easier.
- [multiline](https://github.com/sindresorhus/multiline) - Multiline strings in JavaScript.
- [ssh2](https://github.com/mscdex/ssh2) - An SSH2 client module.
- [lazy-req](https://github.com/sindresorhus/lazy-req) - Require modules lazily.
- [file-type](https://github.com/sindresorhus/file-type) - Detect the file type of a Buffer.
- [Bottleneck](https://github.com/SGrondin/bottleneck) - A powerful rate limiter that makes throttling easy.
- [webworker-threads](https://github.com/audreyt/node-webworker-threads) - Lightweight Web Worker API implementation with native threads.
- [node-pre-gyp](https://github.com/mapbox/node-pre-gyp) - Makes it easy to publish and install Node.js C++ addons from binaries.
- [opencv](https://github.com/peterbraden/node-opencv) - Bindings for OpenCV. The defacto computer vision library.
- [common-errors](https://github.com/shutterstock/node-common-errors) - Common error classes and utility functions.
- [agenda](https://github.com/rschmukler/agenda) - Lightweight job scheduling on MongoDB.
- [dotenv](https://github.com/motdotla/dotenv) - Load environment variables from .env file.
- [remote-git-tags](https://github.com/sindresorhus/remote-git-tags) - Get tags from a remote git repo.
- [semver](https://github.com/npm/node-semver) - [semver](http://semver.org) parser.
- [nar](https://github.com/h2non/nar) - Create self-contained executable binaries.
- [node-bell](https://github.com/eleme/bell.js) - Real-time anomalies detection for periodic time series.
- [Faker.js](https://github.com/Marak/Faker.js) - Generate massive amounts of fake data.
- [nodegit](https://github.com/nodegit/nodegit) - Native bindings to Git.


## Resources

### Tutorials

- [Nodeschool](http://nodeschool.io) - Learn Node.js with interactive lessons.
- [The Art of Node](https://github.com/maxogden/art-of-node/#the-art-of-node) - An introduction to Node.js.
- [stream-handbook](https://github.com/substack/stream-handbook) - How to write Node.js programs with streams.
- [browserify-handbook](https://github.com/substack/browserify-handbook) - The definitive guide for browserify.
- [module-best-practices](https://github.com/mattdesl/module-best-practices) - Some good practices when writing new npm modules.
- [The Node Way](http://thenodeway.io) — An entire philosophy of Node.js best practices and guiding principles exists for writing maintainable modules, scalable applications, and code that is actually pleasant to read.

### Discovery

- [node-modules.com](http://node-modules.com) - An alternative npm search engine with a more intelligent and personal results ranking.

### Articles

- [Error Handling in Node.js](http://www.joyent.com/developers/node/design/errors)
- [Teach Yourself Node.js in 10 Steps](https://ponyfoo.com/articles/teach-yourself-nodejs-in-10-steps)
- [Mastering the filesystem in Node.js](https://medium.com/@yoshuawuyts/mastering-the-filesystem-in-node-js-4706b7cb0801)

### Newsletters

- [node weekly](http://nodeweekly.com) - Weekly e-mail round-up of Node.js news and articles.
- [nmotw](http://nmotw.in) - Node Module Of The Week, weekly dose of hand picked node modules.

### Videos

- [Introduction to Node.js with Ryan Dahl](https://www.youtube.com/watch?v=jo_B4LTHi3I)
- [LearnAllTheNodes](https://www.learnallthenodes.com/) - Series of useful tips, tricks, and packages.
- [Introduction to Node.js Fundamentals](http://strongloop.com/node-js/videos/#a-video-intro-to-nodejs-fundamentals)
- [Hands on with Node.js](https://learn.bevry.me/node/preface)
- [Full Streams Ahead](http://dry.ly/full-streams-ahead) - Introduction to streams.
- [StrongLoop Talks](https://strongloop.com/node-js/videos/) - Series of talks.
- [thenewboston's Node.js for Beginners](https://www.thenewboston.com/videos.php?cat=355)
- [Nodetuts](http://nodetuts.com) - Series of talks, including TCP & HTTP API servers, async programming, and more.
- [Node Interactive 2015](https://github.com/duffn/nodeinteractive-2015) - List of talks, keynotes and panels from the 2015 Node Interactive conference.

### Podcasts

- [NodeUp](http://nodeup.com)

### Books

- [Node.js in Action](http://www.amazon.com/Node-js-Action-Mike-Cantelon/dp/1617290572)
- [Node.js in Practice](http://www.amazon.com/Node-js-Practice-Alex-R-Young/dp/1617290939)
- [Mastering Node](http://visionmedia.github.io/masteringnode/)
- [Professional Node.js: Building Javascript Based Scalable Software](http://www.amazon.com/Professional-Node-js-Building-Javascript-Scalable-ebook/dp/B009L7QETY/)
- [Practical Node.js: Building Real-World Scalable Web Apps](http://practicalnodebook.com)
- [Mixu's Node book](http://book.mixu.net/node/)
- [Web Development with Node and Express](http://shop.oreilly.com/product/0636920032977.do)
- [Pro Express.js](http://proexpressjs.com)

### Blogs

- [Node.js blog](https://nodejs.org/en/blog/)
- [HowToNode](http://howtonode.org) - Teaching how to do various tasks in Node.js as well as teach fundamental concepts that are needed to write effective code.
- [webapplog.com](http://webapplog.com/tag/node-js/) — Blog posts on Node.js and JavaScript from the author of Practical Node.js and Pro Express.js Azat Mardan.

### Courses

- [Real Time Web with Node.js](http://campus.codeschool.com/auth/codeschool)
- [Learn and Understand Node.js](https://www.udemy.com/understand-nodejs)

### Cheatsheets

- [Express.js](https://github.com/azat-co/cheatsheets/blob/master/express4/index.md)
- [Stream FAQs](https://github.com/stephenplusplus/stream-faqs) - Answering common questions about streams, covering pagination, events, and more.

### Tools

- [GitHub Linker](https://chrome.google.com/webstore/detail/github-linker/jlmafbaeoofdegohdhinkhilhclaklkp) - Chrome extension that linkifies dependencies in package.json, .js, .jsx, .coffee and .md files on GitHub.
- [npm-hub](https://chrome.google.com/webstore/detail/npm-hub/kbbbjimdjbjclaebffknlabpogocablj) - Chrome extension to display npm dependencies at the bottom of a repo's readme.
- [RequireBin](http://requirebin.com) - Shareable JavaScript programs powered by npm and browserify.
- [Tonic](http://blog.tonicdev.com/2015/09/30/embedded-tonic.html) - Embed a Node.js environment on any website.

### Miscellaneous

- [nodebots](http://nodebots.io) - Robots powered by JavaScript.
- [node-module-boilerplate](https://github.com/sindresorhus/node-module-boilerplate) - Boilerplate to kickstart creating a node module.
- [generator-nm](https://github.com/sindresorhus/generator-nm) - Scaffold out a node module.
- [awesome-cross-platform-nodejs](https://github.com/bcoe/awesome-cross-platform-nodejs) - Resources for writing and testing cross-platform code.


## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.


## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Sindre Sorhus](http://sindresorhus.com) has waived all copyright and related or neighboring rights to this work.
