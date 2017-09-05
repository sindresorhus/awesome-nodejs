# Awesome Node.js [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="https://cdn.rawgit.com/gilbarbara/logos/e7b1dc2666c3dabe6c1276abd0a767b6ebd6af43/logos/nodejs-icon.svg" align="right" width="70">](https://nodejs.org)

> A curated list of delightful Node.js [packages](#packages) and [resources](#resources).

Just type [`node.cool`](https://node.cool) to go here ✨

*You might also like [awesome-npm](https://github.com/sindresorhus/awesome-npm).*
*Please read the [contribution guidelines](contributing.md) before contributing.*


---

<p align="center"><sup>🦄 Support <a href="https://github.com/sindresorhus">my open-source work</a> by buying this awesome video course:</sup><br><b><a href="https://learnnode.com/friend/AWESOME">Learn to build apps and APIs with Node.js</a> by Wes Bos</b><br><sub>Try his free <a href="https://javascript30.com/friend/AWESOME">JavaScript 30</a> course for a taste of what to expect & check out his <a href="https://ES6.io/friend/AWESOME">ES6</a>, <a href="https://ReactForBeginners.com/friend/AWESOME">React</a>, <a href="https://SublimeTextBook.com/friend/AWESOME">Sublime</a> courses.</sub></p>

---


<sub>Check out my [blog](https://blog.sindresorhus.com) and say "hi" on [Twitter](https://twitter.com/sindresorhus).</sub>


## Contents

- [Packages](#packages)
	- [AST](#ast)
	- [Authentication](#authentication)
	- [Automation](#automation)
	- [Benchmarking](#benchmarking)
	- [Blogging](#blogging)
	- [Build tools](#build-tools)
	- [Command-line apps](#command-line-apps)
	- [Command-line utilities](#command-line-utilities)
	- [Compression](#compression)
	- [Content management systems](#content-management-systems)
	- [Control flow](#control-flow)
	- [Data validation](#data-validation)
	- [Database](#database)
	- [Date](#date)
	- [Debugging / Profiling](#debugging--profiling)
	- [Documentation](#documentation)
	- [Email](#email)
	- [Filesystem](#filesystem)
	- [Forum](#forum)
	- [Functional programming](#functional-programming)
	- [Hardware](#hardware)
	- [HTTP](#http)
	- [Humanize](#humanize)
	- [Image](#image)
	- [Job queues](#job-queues)
	- [Logging](#logging)
	- [Mad science](#mad-science)
	- [Math](#math)
	- [Minifiers](#minifiers)
	- [Miscellaneous](#miscellaneous)
	- [Natural language processing](#natural-language-processing)
	- [Network](#network)
	- [Node.js management](#nodejs-management)
	- [Number](#number)
	- [Parsing](#parsing)
	- [Polyfills](#polyfills)
	- [Process management](#process-management)
	- [Real-time](#real-time)
	- [Security](#security)
	- [Static site generators](#static-site-generators)
	- [Streams](#streams)
	- [Templating](#templating)
	- [Testing](#testing)
	- [Text](#text)
	- [URL](#url)
	- [Web frameworks](#web-frameworks)
	- [Weird](#weird)
- [Resources](#resources)
	- [Articles](#articles)
	- [Blogs](#blogs)
	- [Books](#books)
	- [Cheatsheets](#cheatsheets)
	- [Community](#community)
	- [Courses](#courses)
	- [Discovery](#discovery)
	- [Miscellaneous](#miscellaneous)
	- [Newsletters](#newsletters)
	- [Podcasts](#podcasts)
	- [Tools](#tools)
	- [Tutorials](#tutorials)
	- [Videos](#videos)


## Packages

### Mad science

- [BitcoinJS](http://bitcoinjs.org) - Clean, readable, proven Bitcoin library.
- [Bitcore](https://bitcore.io) - Pure and powerful Bitcoin library.
- [Cytoscape.js](http://js.cytoscape.org) - Graph theory (a.k.a. network) modeling and analysis.
- [dat](http://dat-data.com) - Real-time replication and versioning for data sets.
- [GitTorrent](https://github.com/cjb/GitTorrent) - Peer-to-peer network of Git repositories being shared over BitTorrent.
- [ipfs](https://github.com/ipfs/js-ipfs) - Distributed file system that seeks to connect all computing devices with the same system of files.
- [js-git](https://github.com/creationix/js-git) - JavaScript implementation of Git.
- [kad](https://github.com/kadtools/kad) - Kademlia distributed hash table.
- [limdu](https://github.com/erelsgl/limdu) - Machine-learning framework.
- [NodeOS](http://node-os.com) - The first operating system powered by npm.
- [PDFKit](http://pdfkit.org) - PDF generation library.
- [peercast](https://github.com/mafintosh/peercast) - Stream a torrent video to Chromecast.
- [peerflix](https://github.com/mafintosh/peerflix) - Streaming torrent client.
- [peerwiki](https://github.com/mafintosh/peerwiki) - All of Wikipedia on BitTorrent.
- [seedshot](https://github.com/twobucks/seedshot) - Temporary P2P screenshot sharing from your browser.
- [skale](https://github.com/skale-me/skale-engine) - High performance distributed data processing engine.
- [stackgl](http://stack.gl) - Open software ecosystem for WebGL, built on top of browserify and npm.
- [turf](https://github.com/Turfjs/turf) - Modular geospatial processing and analysis engine.
- [webcat](https://github.com/mafintosh/webcat) - p2p pipe across the web using WebRTC that uses your GitHub private/public key for authentication.
- [webtorrent](https://github.com/feross/webtorrent) - Streaming torrent client for Node.js and the browser.


### Command-line apps

- [alex](https://github.com/wooorm/alex) - Catch insensitive, inconsiderate writing.
- [atmo](https://github.com/Raathigesh/Atmo) - Server-side API mocking.
- [auto-install](https://github.com/siddharthkp/auto-install) - Auto installs dependencies as you code.
- [bcat](https://github.com/kessler/node-bcat) - Pipe command output to web browsers.
- [brightness](https://github.com/kevva/brightness-cli) - Change the screen brightness.
- [browser-run](https://github.com/juliangruber/browser-run) - Easily run code in a browser environment.
- [Cash](https://github.com/dthree/cash) - Cross-platform Unix shell commands in pure JavaScript.
- [clipboard-cli](https://github.com/sindresorhus/clipboard-cli) - Copy & paste on the terminal.
- [cost-of-modules](https://github.com/siddharthkp/cost-of-modules) - Find out which dependencies are slowing you down.
- [cpy](https://github.com/sindresorhus/cpy) - Copy files.
- [dark-mode](https://github.com/sindresorhus/dark-mode) - Toggle the macOS Dark Mode.
- [David](https://github.com/alanshaw/david) - Tells you when your package npm dependencies are out of date.
- [dev-time](https://github.com/samverschueren/dev-time-cli) - Get the current local time of a GitHub user.
- [diff2html-cli](https://github.com/rtfpessoa/diff2html-cli) - Pretty git diff to HTML generator.
- [emoj](https://github.com/sindresorhus/emoj) - Find relevant emoji from text on the command-line.
- [empty-trash](https://github.com/sindresorhus/empty-trash) - Empty the trash.
- [esformatter](https://github.com/millermedeiros/esformatter) - JavaScript code beautifier/formatter.
- [ESLint](http://eslint.org) - The pluggable linting utility for JavaScript.
- [fkill](https://github.com/sindresorhus/fkill-cli) - Fabulously kill processes. Cross-platform.
- [gh-home](https://github.com/sindresorhus/gh-home) - Open the GitHub page of the repo in the current directory.
- [http-server](https://github.com/indexzero/http-server) - Simple, zero-config command-line HTTP server.
- [iponmap](https://github.com/nogizhopaboroda/iponmap) - IP location finder.
- [is-online](https://github.com/sindresorhus/is-online) - Check if the internet connection is up.
- [is-up](https://github.com/sindresorhus/is-up) - Check whether a website is up or down.
- [itunes-remote](https://github.com/mischah/itunes-remote) - Interactively control iTunes.
- [jscpd](https://github.com/kucherenko/jscpd) - Copy/paste detector for source code.
- [jsinspect](https://github.com/danielstjules/jsinspect) - Detect copy-pasted and structurally similar code.
- [Jsome](https://github.com/Javascipt/Jsome) - Pretty prints JSON with configurable colors and indentation.
- [kill-tabs](https://github.com/sindresorhus/kill-tabs) - Kill all Chrome tabs to improve performance, decrease battery usage, and save memory.
- [lessmd](https://github.com/linuxenko/lessmd) - Markdown in the terminal.
- [license-checker](https://github.com/davglass/license-checker) - Check licenses of your app's dependencies.
- [Live Server](https://github.com/tapio/live-server) - Development HTTP-server with livereload capability.
- [localtunnel](https://github.com/localtunnel/localtunnel) - Expose your localhost to the world.
- [mobicon](https://github.com/samverschueren/mobicon-cli) - Mobile app icon generator.
- [mobisplash](https://github.com/samverschueren/mobisplash-cli) - Mobile app splash screen generator.
- [modhelp](https://github.com/runvnc/modhelp) - Syntax-highlighted module READMEs in terminal with ANSI-friendly pager.
- [normit](https://github.com/pawurb/normit) - Google Translate with speech synthesis in your terminal.
- [np](https://github.com/sindresorhus/np) - Better `npm publish`.
- [npm-home](https://github.com/sindresorhus/npm-home) - Open the npm page of a package.
- [npm-name](https://github.com/sindresorhus/npm-name) - Check whether a package name is available on npm.
- [pageres](https://github.com/sindresorhus/pageres) - Capture website screenshots.
- [pen](https://github.com/noraesae/pen) - Live Markdown preview in the browser from your favorite editor.
- [pjs](https://github.com/danielstjules/pjs) - Pipeable JavaScript. Quickly filter, map, and reduce from the terminal.
- [public-ip](https://github.com/sindresorhus/public-ip) - Get your public IP address.
- [rtail](https://github.com/kilianc/rtail) - Terminal output to the browser in seconds, using UNIX pipes.
- [slap](https://github.com/slap-editor/slap) - Sublime-like terminal-based text editor.
- [speed-test](https://github.com/sindresorhus/speed-test) - Test your internet connection speed and ping.
- [Standard](https://github.com/feross/standard) - JavaScript Standard Style — One style to rule them all.
- [subdownloader](https://github.com/beatfreaker/subdownloader) - Subtitle downloader for movies and TV series.
- [terminal-recorder](https://github.com/cortezcristian/terminal-recorder) - Record your terminal usage and export it to interactive HTML.
- [text-meme](https://github.com/beatfreaker/text-meme-cli) - Generate a text meme.
- [tfa](https://github.com/jasnell/tfa) - Two-factor authentication client.
- [tmpin](https://github.com/sindresorhus/tmpin) - Adds stdin support to any CLI app that accepts file input.
- [torrent](https://github.com/maxogden/torrent) - Download torrents.
- [trash](https://github.com/sindresorhus/trash) - Safer alternative to `rm`.
- [trymodule](https://github.com/VictorBjelkholm/trymodule) - Try out npm packages in the terminal.
- [ttystudio](https://github.com/chjj/ttystudio) - Record your terminal and compile it to a GIF or APNG without any external dependencies, bash scripts, gif concatenation, etc.
- [vaca](https://github.com/sindresorhus/vaca) - Get a random ASCII 🐮.
- [vantage](https://github.com/dthree/vantage) - Distributed, realtime CLI for your live app.
- [vtop](https://github.com/MrRio/vtop) - More better top, with nice charts.
- [wallpaper](https://github.com/sindresorhus/wallpaper) - Change the desktop wallpaper.
- [wifi-password](https://github.com/kevva/wifi-password-cli) - Get the current wifi password.
- [XO](https://github.com/sindresorhus/xo) - Enforce strict code style using the JavaScript happiness style.


### Functional programming

- [Bacon.js](http://baconjs.github.io) - Functional reactive programming.
- [Folktale](http://folktalejs.org) - Suite of libraries for generic functional programming in JavaScript that allows you to write elegant, modular applications with fewer bugs, and more reuse.
- [immutable](https://github.com/facebook/immutable-js) - Immutable data collections.
- [Kefir.js](https://github.com/rpominov/kefir) - Reactive library with focus on high performance and low memory usage.
- [Lazy.js](https://github.com/dtao/lazy.js) - Utility library similar to lodash/Underscore but with lazy evaluation, which can translate to superior performance in many cases.
- [lodash](https://lodash.com) - Utility library delivering consistency, customization, performance, & extras. A better and faster Underscore.js.
- [mori](http://swannodette.github.io/mori/) - Library for using ClojureScript's persistent data structures and supporting API from the comfort of vanilla JavaScript.
- [Mout](http://moutjs.com) - Utility library with the biggest difference between other existing solutions is that you can choose to load only the modules/functions that you need, no extra overhead.
- [Ramda](http://ramdajs.com) - Utility library with a focus on flexible functional composition enabled by automatic currying and reversed argument order. Avoids mutating data.
- [RxJS](http://reactivex.io) - Functional reactive library for transforming, composing, and querying various kinds of data.
- [underscore-contrib](http://documentcloud.github.io/underscore-contrib/) - The brass buckles on Underscore's utility belt.


### HTTP

- [axios](https://github.com/mzabriskie/axios) - Promise based HTTP client (works in the browser too).
- [download](https://github.com/kevva/download) - Download and extract files effortlessly.
- [flashheart](https://github.com/bbc/flashheart) - REST client.
- [gh-got](https://github.com/sindresorhus/gh-got) - Convenience wrapper for `got` to interact with the GitHub API.
- [got](https://github.com/sindresorhus/got) - Nicer interface to the built-in `http` module.
- [http-fake-backend](https://github.com/micromata/http-fake-backend) - Build a fake backend by providing the content of JSON files or JavaScript objects through configurable routes.
- [http-proxy](https://github.com/nodejitsu/node-http-proxy) - HTTP proxy.
- [Nock](https://github.com/pgte/nock) - HTTP mocking and expectations library.
- [node-fetch](https://github.com/bitinn/node-fetch) - `window.fetch` for Node.js.
- [request](https://github.com/request/request) - Simplified HTTP request client.
- [rocky](https://github.com/h2non/rocky) - Featured, middleware-oriented HTTP proxy with traffic replay and intercept.
- [spdy](https://github.com/indutny/node-spdy) - Creates SPDY servers with the same API as the built-in `https` module.
- [superagent](https://github.com/visionmedia/superagent) - HTTP request library.
- [wreck](https://github.com/hapijs/wreck) - HTTP Client Utilities.


### Debugging / Profiling

- [0x](https://github.com/davidmarkclements/0x) - Flamegraph profiling.
- [bugger](https://github.com/buggerjs/bugger) - Provides Chrome Devtools bindings to debug programs in Chrome.
- [ctrace](https://github.com/automation-stack/ctrace) - Well-formatted and improved trace system calls and signals.
- [debug](https://github.com/visionmedia/debug) - Tiny debugging utility.
- [devtool](https://github.com/Jam3/devtool) - Run Node.js programs through Chrome Dev Tools.
- [ironNode](https://github.com/s-a/iron-node) - Node.js debugger supporting ES2015 out of the box.
- [jstrace](https://github.com/jstrace/jstrace) - Dynamic tracing for JavaScript, similar to dtrace, ktap etc.
- [leakage](https://github.com/andywer/leakage) - Write memory leak tests.
- [locus](https://github.com/alidavut/locus) - Starts a REPL at runtime that has access to all variables.
- [longjohn](https://github.com/mattinsler/longjohn) - Long stack traces with configurable call trace length.
- [njsTrace](https://github.com/valyouw/njstrace) - Instrument and trace your code, see all function calls, arguments, return values, as well as the time spent in each function.
- [node-inspector](https://github.com/node-inspector/node-inspector) - Debugger based on Blink Developer Tools.
- [stackman](https://github.com/watson/stackman) - Enhance an error stacktrace with code excerpts and other goodies.
- [Theseus](https://github.com/adobe-research/theseus) - JavaScript debugger featuring real-time code coverage, retroactive inspection and asynchronous call tree.
- [vstream](https://github.com/joyent/node-vstream) - Instrumentable streams mix-ins to inspect a pipeline of streams.
- [why-is-node-running](https://github.com/mafintosh/why-is-node-running) - Node.js is running but you don't know why?


### Logging

- [Bunyan](https://github.com/trentm/node-bunyan) - JSON logging library.
- [console-log-level](https://github.com/watson/console-log-level) - The most simple logger imaginable with support for log levels and custom prefixes.
- [intel](http://seanmonstar.github.io/intel/) - Logging library (handlers, filters, formatters, console injection).
- [pino](https://github.com/pinojs/pino) - Extremely fast logger inspired by Bunyan.
- [storyboard](https://github.com/guigrpa/storyboard) - End-to-end, hierarchical, real-time, colorful logs and stories.
- [winston](https://github.com/winstonjs/winston) - Multi-transport async logging library.


### Command-line utilities

- [ansi-escapes](https://github.com/sindresorhus/ansi-escapes) - ANSI escape codes for manipulating the terminal.
- [ascii-charts](https://github.com/jstrace/chart) - ASCII bar chart in the terminal.
- [Bit](https://github.com/teambit/bit) - Create, maintain, find and use small modules and components across repositories.
- [blessed](https://github.com/chjj/blessed) - Curses-like library.
- [boxen](https://github.com/sindresorhus/boxen) - Create boxes in the terminal.
- [cfonts](https://github.com/dominikwilkowski/cfonts) - Sexy ASCII fonts for the console.
- [chalk](https://github.com/chalk/chalk) - Terminal string styling done right.
- [cli-columns](https://github.com/shannonmoeller/cli-columns) - Columnated unicode and ansi-safe text lists.
- [cli-cursor](https://github.com/sindresorhus/cli-cursor) - Toggle the CLI cursor.
- [cli-table](https://github.com/Automattic/cli-table) - Pretty unicode tables.
- [cli-truncate](https://github.com/sindresorhus/cli-truncate) - Truncate a string to a specific width in the terminal.
- [columnify](https://github.com/timoxley/columnify) - Create text-based columns suitable for console output. Supports cell wrapping.
- [conf](https://github.com/sindresorhus/conf) - Simple config handling for your app or module.
- [cross-env](https://github.com/kentcdodds/cross-env) - Set environment variables cross-platform.
- [DraftLog](https://github.com/ivanseidel/node-draftlog) - Create multiple updatable log lines. Works just like `console.log`.
- [drawille](https://github.com/madbence/node-drawille) - Draw on the terminal with unicode braille characters.
- [figures](https://github.com/sindresorhus/figures) - Unicode symbols with Windows CMD fallbacks.
- [first-run](https://github.com/sindresorhus/first-run) - Check if it's the first time the process is run.
- [get-stdin](https://github.com/sindresorhus/get-stdin) - Easier stdin.
- [googleauth](https://github.com/maxogden/googleauth) - Create and load persistent Google authentication tokens for command-line apps.
- [gradient-string](https://github.com/bokub/gradient-string) - Beautiful color gradients in terminal output.
- [Inquirer.js](https://github.com/SBoudrias/Inquirer.js) - Interactive command-line prompt.
- [insight](https://github.com/yeoman/insight) - Helps you understand how your tool is being used by anonymously reporting usage metrics to Google Analytics.
- [listr](https://github.com/samverschueren/listr) - Terminal task list.
- [log-symbols](https://github.com/sindresorhus/log-symbols) - Colored symbols for various log levels.
- [log-update](https://github.com/sindresorhus/log-update) - Log by overwriting the previous output in the terminal. Useful for rendering progress bars, animations, etc.
- [loud-rejection](https://github.com/sindresorhus/loud-rejection) - Make unhandled promise rejections fail loudly instead of the default silent fail.
- [meow](https://github.com/sindresorhus/meow) - CLI app helper.
- [minimist](https://github.com/substack/minimist) - Parse command-line flags.
- [multispinner](https://github.com/codekirei/node-multispinner) - Multiple, simultaneous, individually controllable CLI spinners.
- [omelette](https://github.com/f/omelette) - Shell autocompletion helper.
- [ora](https://github.com/sindresorhus/ora) - Elegant terminal spinner.
- [progress](https://github.com/tj/node-progress) - Flexible ascii progress bar.
- [shelljs](https://github.com/shelljs/shelljs) - Portable Unix shell commands.
- [sparkly](https://github.com/sindresorhus/sparkly) - Generate sparklines ▁▂▃▅▂▇
- [string-width](https://github.com/sindresorhus/string-width) - Get the visual width of a string - the number of columns required to display it.
- [sudo-block](https://github.com/sindresorhus/sudo-block) - Block users from running your app with root permissions.
- [term-img](https://github.com/sindresorhus/term-img) - Display images in your terminal.
- [update-notifier](https://github.com/yeoman/update-notifier) - Update notifications for your CLI app.
- [vorpal](https://github.com/dthree/vorpal) - Interactive CLI apps.
- [yargs](https://github.com/yargs/yargs) - Command-line parser that automatically generates an elegant user-interface.
- [yn](https://github.com/sindresorhus/yn) - Parse yes/no like values.


### Build tools

- [Broccoli](https://github.com/broccolijs/broccoli) - Fast, reliable asset pipeline, supporting constant-time rebuilds and compact build definitions.
- [browserify](https://github.com/substack/node-browserify) - Browser-side require() the Node.js way.
- [Brunch](https://github.com/brunch/brunch) - Front-end web app build tool with simple declarative config, fast incremental compilation, and an opinionated workflow.
- [Fly](https://github.com/bucaran/fly) - Modern build system based in co-routines, generators and promises.
- [FuseBox](https://github.com/fuse-box/fuse-box) - Fast build system that combines the power of webpack, JSPM and SystemJS, with first-class TypeScript support.
- [grunt](http://gruntjs.com) - Task runner that can perform repetitive tasks like minification, compilation, unit testing, linting, etc.
- [gulp](http://gulpjs.com) - Streaming and fast build system that favors code over config.
- [pkg](https://github.com/zeit/pkg) - Package your Node.js project into an executable.
- [rollup](https://github.com/rollup/rollup) - Next-generation ES2015 module bundler.
- [start](https://github.com/start-runner/start) - Simple tasks runner powered by composable functions and promise chaining.
- [strong-build](https://github.com/strongloop/strong-build) - Build a node app package and prepare to deploy it as a package to production or use git to commit to a deploy branch.
- [webpack](https://github.com/webpack/webpack) - Packs modules and assets for the browser.
- [ygor](https://github.com/shannonmoeller/ygor) - Promising task runner for when `npm run` isn't enough and everything else is too much.


### Hardware

- [cylon.js](http://cylonjs.com) - Next generation robotics framework with support for 26 different platforms.
- [i2c-bus](https://github.com/fivdi/i2c-bus) - I2C serial bus access.
- [johnny-five](https://github.com/rwaldron/johnny-five) - Firmata based Arduino Framework.
- [onoff](https://github.com/fivdi/onoff) - GPIO access and interrupt detection.
- [pigpio](https://github.com/fivdi/pigpio) - Fast GPIO, PWM, servo control, state change notification, and interrupt handling on the Raspberry Pi.
- [serialport](https://github.com/voodootikigod/node-serialport) - Access serial ports for reading and writing.
- [spi-device](https://github.com/fivdi/spi-device) - SPI serial bus access.
- [usb](https://github.com/nonolith/node-usb) - USB library.


### Templating

- [EJS](https://github.com/mde/ejs) - Simple unopinionated templating language.
- [handlebars.js](https://github.com/wycats/handlebars.js) - Superset of Mustache templates which adds powerful features like helpers and more advanced blocks.
- [hogan.js](http://twitter.github.io/hogan.js/) - Twitter's small, fast, phase-separated compiler for Mustache templates.
- [marko](https://github.com/marko-js/marko) - HTML-based templating engine that compiles templates to CommonJS modules and supports streaming, async rendering and custom tags.
- [nunjucks](https://github.com/mozilla/nunjucks) - Templating engine with inheritance, asynchronous control, and more (jinja2 inspired).
- [Pug](https://github.com/pugjs/pug) - High-performance template engine heavily influenced by Haml.


### Web frameworks

- [ActionHero](http://www.actionherojs.com) - Framework for making reusable & scalable APIs for TCP sockets, WebSockets, and HTTP clients.
- [AdonisJs](http://adonisjs.com) - A true MVC framework for Node.js built on solid foundations of Dependency Injection and IoC container.
- [Catberry](http://catberry.org) - Framework with Flux architecture, isomorphic web-components, and progressive rendering.
- [Express](http://expressjs.com) - Web application framework, providing a robust set of features for building single and multi-page, and hybrid web applications.
- [Feathers](http://feathersjs.com) - Microservice framework built in the spirit of Express.
- [Hapi](http://hapijs.com) - Framework for building applications and services.
- [Hemera](https://github.com/hemerajs/hemera) - Write reliable and fault-tolerant microservices with [NATS](https://nats.io).
- [Interfake](https://github.com/basicallydan/interfake) - Rapid prototyping framework for making mock HTTP APIs, with a Node.js, command-line and HTTP interface.
- [Koa](http://koajs.com) - Framework designed by the team behind Express, which aims to be a smaller, more expressive, and more robust foundation for web applications and APIs.
- [LoopBack](http://loopback.io) - Powerful framework for creating REST APIs and easily connecting to backend data sources.
- [MERN](http://mern.io) - Easily build production-ready universal apps with MongoDB, Express, React, and webpack.
- [Meteor](https://www.meteor.com) - An ultra-simple, database-everywhere, data-on-the-wire, pure-Javascript web framework. *(You might like [awesome-meteor](https://github.com/Urigo/awesome-meteor))*
- [Next.js](https://zeit.co/blog/next) - Minimalistic framework for server-rendered universal JavaScript web apps.
- [Nuxt.js](https://nuxtjs.org) - Minimalistic framework for server-rendered Vue.js apps.
- [Restify](http://restify.com) - Enables you to build correct REST web services.
- [SailsJS](http://sailsjs.org) - An MVC web framework with a modern twist, supporting WebSockets, streams, and a data-driven API.
- [seneca](https://github.com/senecajs/seneca) - Toolkit for writing microservices.
- [ThinkJS](https://thinkjs.org) - Framework with ES2015+ support, WebSockets, REST API.


### Documentation

- [apiDoc](https://github.com/apidoc/apidoc) - Inline documentation for RESTful web APIs.
- [Docco](http://jashkenas.github.io/docco/) - Documentation generator which produces an HTML document that displays your comments intermingled with your code.
- [documentation.js](http://documentation.js.org) - API documentation generator with support for ES2015+ and flow annotation.
- [dox](https://github.com/tj/dox) - JavaScript documentation generator using Markdown and JSDoc.
- [ESDoc](https://esdoc.org) - Documentation generator targeting ES2015, attaching test code and measuring documentation coverage.
- [JSDoc](http://usejsdoc.org) - API documentation generator similar to JavaDoc or PHPDoc.
- [jsdox](https://github.com/sutoiku/jsdox) - JSDoc3 to Markdown documentation generator.
- [YUIDoc](http://yui.github.com/yuidoc/) - Generates API documentation from comments in source.


### Filesystem

- [chokidar](https://github.com/paulmillr/chokidar) - Filesystem watcher which stabilizes events from `fs.watch` and `fs.watchFile` as well as using native `fsevents` on macOS.
- [cpy](https://github.com/sindresorhus/cpy) - Copy files.
- [del](https://github.com/sindresorhus/del) - Delete files/folders using globs.
- [filehound](https://github.com/nspragg/filehound) - Flexible and fluent interface for searching the file system.
- [filenamify](https://github.com/sindresorhus/filenamify) - Convert a string to a valid filename.
- [find-up](https://github.com/sindresorhus/find-up) - Find a file by walking up parent directories.
- [fs-extra](https://github.com/jprichardson/node-fs-extra) - Extra methods for the `fs` module.
- [fs-jetpack](https://github.com/szwacz/fs-jetpack) - Completely redesigned file system API for convenience in everyday use.
- [fs-write-stream-atomic](https://github.com/npm/fs-write-stream-atomic) - Like `fs.createWriteStream()`, but atomic.
- [globby](https://github.com/sindresorhus/globby) - Glob files with support for multiple patterns.
- [graceful-fs](https://github.com/isaacs/node-graceful-fs) - Drop-in replacement for the `fs` module with various improvements.
- [istextorbinary](https://github.com/bevry/istextorbinary) - Check if a file is text or binary.
- [lnfs](https://github.com/kevva/lnfs) - Force create symlinks like `ln -fs`.
- [load-json-file](https://github.com/sindresorhus/load-json-file) - Read and parse a JSON file.
- [make-dir](https://github.com/sindresorhus/make-dir) - Recursively create directories like `mkdir -p`.
- [pkg-dir](https://github.com/sindresorhus/pkg-dir) - Find the root directory of an npm package.
- [proper-lockfile](https://github.com/IndigoUnited/node-proper-lockfile) - Inter-process and inter-machine lockfile utility.
- [rimraf](https://github.com/isaacs/rimraf) - Recursively delete files like `rm -rf`.
- [sander](https://github.com/rich-harris/sander) - Promise-based replacement for the `fs` module.
- [write-json-file](https://github.com/sindresorhus/write-json-file) - Stringify and write JSON to a file atomically.


### Control flow

	- [async](https://github.com/caolan/async) - Provides straight-forward, powerful functions for working with asynchronicity.
	- [bluebird-co](https://github.com/novacrazy/bluebird-co) - High performance yield handlers for Bluebird coroutines.
	- [Bluebird](https://github.com/petkaantonov/bluebird) - Promise library with focus on innovative features and performance.
	- [co](https://github.com/tj/co) - The ultimate generator based flow-control goodness.
	- [delay](https://github.com/sindresorhus/delay) - Delay a promise a specified amount of time.
	- [each-async](https://github.com/sindresorhus/each-async) - Async concurrent iterator like forEach.
	- [Highland.js](http://highlandjs.org) - Manages synchronous and asynchronous code easily, using nothing more than standard JavaScript and Node-like Streams.
	- [iterum](https://github.com/xgbuils/iterum) - Build generator pipelines using Array-like methods.
	- [js-csp](https://github.com/ubolonton/js-csp) - Communicating sequential processes for JavaScript (like Clojurescript core.async, or Go).
	- [More…](https://github.com/sindresorhus/awesome-observables)
	- [More…](https://github.com/wbinnssmith/awesome-promises)
	- [observable-to-promise](https://github.com/sindresorhus/awesome-observables) - Convert an Observable to a Promise.
	- [p-map](https://github.com/sindresorhus/p-map) - Map over promises concurrently.
	- [pify](https://github.com/sindresorhus/pify) - Promisify a callback-style function.
	- [promise-memoize](https://github.com/nodeca/promise-memoize) - Memoize promise-returning functions, with expire and prefetch.
	- [RxJS](https://github.com/ReactiveX/RxJS) - Reactive programming.
	- [valvelet](https://github.com/lpinca/valvelet) - Limit the execution rate of a promise-returning function.
	- [zen-observable](https://github.com/zenparsing/zen-observable) - Implementation of Observables.
	- [zone](https://github.com/strongloop/zone) - Provides a way to group and track resources and errors across asynchronous operations.
- Callbacks
- Channels
- Generators
- Observables
- Other
- Promises
- Streams


### Streams

- [binary-split](https://github.com/maxogden/binary-split) - Newline (or any delimiter) splitter stream.
- [byline](https://github.com/jahewson/node-byline) - Super-simple line-by-line Stream reader.
- [duplexify](https://github.com/mafintosh/duplexify) - Turn a writeable and readable stream into a single streams2 duplex stream.
- [first-chunk-stream](https://github.com/sindresorhus/first-chunk-stream) - Transform the first chunk in a stream.
- [from2](https://github.com/hughsk/from2) - Convenience wrapper for ReadableStream, inspired by `through2`.
- [get-stream](https://github.com/sindresorhus/get-stream) - Get a stream as a string or buffer.
- [graphicsmagick-stream](https://github.com/e-conomic/graphicsmagick-stream) - Fast conversion/scaling of images using a pool of long lived GraphicsMagick processes.
- [into-stream](https://github.com/sindresorhus/into-stream) - Convert a buffer/string/array/object into a stream.
- [multistream](https://github.com/feross/multistream) - Combine multiple streams into a single stream.
- [pad-stream](https://github.com/sindresorhus/pad-stream) - Pad each line in a stream.
- [peek-stream](https://github.com/mafintosh/peek-stream) - Transform stream that lets you peek the first line before deciding how to parse it.
- [pumpify](https://github.com/mafintosh/pumpify) - Combine an array of streams into a single duplex stream.
- [readable-stream](https://github.com/nodejs/readable-stream) - Mirror of Streams2 and Streams3 implementations in core.
- [stream-combiner2](https://github.com/substack/stream-combiner2) - Turn a pipeline into a single stream.
- [through2-concurrent](https://github.com/almost/through2-concurrent) - Transform object streams concurrently.
- [through2](https://github.com/rvagg/through2) - Tiny wrapper around streams2 Transform to avoid explicit subclassing noise.


### Real-time

- [deepstream.io](https://deepstream.io) - Scalable real-time microservice framework.
- [Faye](http://faye.jcoglan.com) - Real-time client-server message bus, based on Bayeux protocol.
- [Kalm](https://github.com/kalm/kalm.js) - Low-level socket router and middleware framework.
- [MQTT.js](https://github.com/mqttjs/MQTT.js) - Client for MQTT - Pub-sub based messaging protocol for use on top of TCP/IP.
- [Primus](https://github.com/primus/primus) - An abstraction layer for real-time frameworks to prevent module lock-in.
- [Socket.io](http://socket.io) - Enables real-time bidirectional event-based communication.
- [SocketCluster](https://github.com/SocketCluster/socketcluster) - Scalable HTTP + WebSocket engine which can run on multiple CPU cores.
- [SockJS](https://github.com/sockjs/sockjs-node) - Low latency, full duplex, cross-domain channel browser-server, with WebSockets or without.
- [Straw](https://github.com/simonswain/straw) - Real-time dataflow framework.
- [µWebSockets](https://github.com/uWebSockets/uWebSockets) - Highly scalable WebSocket server & client library.


### Image

- [gm](https://github.com/aheckmann/gm) - GraphicsMagick and ImageMagick wrapper.
- [image-type](https://github.com/sindresorhus/image-type) - Detect the image type of a Buffer/Uint8Array.
- [is-progressive](https://github.com/sindresorhus/is-progressive) - Check if a JPEG image is progressive.
- [jimp](https://github.com/oliver-moran/jimp) - Image processing in pure JavaScript.
- [lwip](https://github.com/EyalAr/lwip) - Lightweight image processor which does not require ImageMagick.
- [pica](https://github.com/nodeca/pica) - High quality & fast resize (lanczos3) in pure JS. Alternative to canvas drawImage(), when no pixelation allowed.
- [probe-image-size](https://github.com/nodeca/probe-image-size) - Get the size of most image formats without a full download.
- [sharp](https://github.com/lovell/sharp) - The fastest module for resizing JPEG, PNG, WebP and TIFF images.


### Text

- [babelfish](https://github.com/nodeca/babelfish) - i18n with very easy syntax for plurals.
- [camelcase](https://github.com/sindresorhus/camelcase) - Convert a dash/dot/underscore/space separated string to camelCase: foo-bar → fooBar.
- [detect-indent](https://github.com/sindresorhus/detect-indent) - Detect the indentation of code.
- [escape-string-regexp](https://github.com/sindresorhus/escape-string-regexp) - Escape RegExp special characters.
- [execall](https://github.com/sindresorhus/execall) - Find multiple RegExp matches in a string.
- [hanging-indent](https://github.com/codekirei/hanging-indent) - Format a string into a hanging-indented paragraph.
- [he](https://github.com/mathiasbynens/he) - HTML entity encoder/decoder.
- [i18n-node](https://github.com/mashpie/i18n-node) - Simple translation module with dynamic JSON storage.
- [iconv-lite](https://github.com/ashtuchkin/iconv-lite) - Convert character encodings.
- [indent-string](https://github.com/sindresorhus/indent-string) - Indent each line in a string.
- [matcher](https://github.com/sindresorhus/matcher) - Simple wildcard matching.
- [splice-string](https://github.com/sindresorhus/splice-string) - Remove or replace part of a string like `Array#splice`.
- [string-length](https://github.com/sindresorhus/string-length) - Get the real length of a string - by correctly counting astral symbols and ignoring ansi escape codes.
- [strip-indent](https://github.com/sindresorhus/strip-indent) - Strip leading whitespace from every line in a string.
- [Underscore.string](https://github.com/epeli/underscore.string) - Collection of string manipulation utilities.
- [unhomoglyph](https://github.com/nodeca/unhomoglyph) - Normalize visually similar unicode characters.


### Number

- [random-float](https://github.com/sindresorhus/random-float) - Generate a random float.
- [random-int](https://github.com/sindresorhus/random-int) - Generate a random integer.
- [round-to](https://github.com/sindresorhus/round-to) - Round a number to a specific number of decimal places: `1.234` → `1.2`.
- [unique-random](https://github.com/sindresorhus/unique-random) - Generate random numbers that are consecutively unique.


### Math

- [algebra](https://github.com/fibo/algebra) - Algebraic structures.
- [math-clamp](https://github.com/sindresorhus/math-clamp) - Clamp a number.
- [math-sum](https://github.com/sindresorhus/math-sum) - Sum numbers.
- [mathjs](https://github.com/josdejong/mathjs) - An extensive math library.
- [ndarray](https://github.com/scijs/ndarray) - Multidimensional arrays.


### Date

- [cctz](https://github.com/floatdrop/node-cctz) - Fast parsing, formatting, and timezone conversation for dates.
- [date-fns](https://github.com/date-fns/date-fns) - Modern date utility.
- [dateformat](https://github.com/felixge/node-dateformat) - Date formatting.
- [Moment Timezone](http://momentjs.com/timezone/) - IANA Time Zone Database + Moment.js.
- [Moment.js](http://momentjs.com) - Parse, validate, manipulate, and display dates.
- [tz-format](https://github.com/samverschueren/tz-format) - Format a date with timezone: `2015-11-30T10:40:35+01:00`.


### URL

- [embedza](https://github.com/nodeca/embedza) - Create HTML snippets/embeds from URLs using info from oEmbed, Open Graph, meta tags.
- [humanize-url](https://github.com/sindresorhus/humanize-url) - Humanize a URL: http://sindresorhus.com → sindresorhus.com.
- [linkify-it](https://github.com/markdown-it/linkify-it) - Link patterns detector with full unicode support.
- [normalize-url](https://github.com/sindresorhus/normalize-url) - Normalize a URL.
- [speakingurl](https://github.com/pid/speakingurl) - Generate a slug from a string with transliteration.
- [url-pattern](https://github.com/snd/url-pattern) - Easier than regex string matching patterns for URLs and other strings.
- [url-unshort](https://github.com/nodeca/url-unshort) - Expand shortened URLs.


### Data validation

- [ajv](https://github.com/epoberezkin/ajv) - The fastest JSON Schema validator. Supports v5 proposals.
- [is-my-json-valid](https://github.com/mafintosh/is-my-json-valid) - JSON Schema validator that uses code generation to be extremely fast.
- [joi](https://github.com/hapijs/joi) - Object schema description language and validator for JavaScript objects.
- [property-validator](https://github.com/nettofarah/property-validator) - Easy property validation for Express.
- [schema-inspector](https://github.com/Atinux/schema-inspector) - JSON API sanitization and validation.


### Parsing

- [binary-extract](https://github.com/juliangruber/binary-extract) - Extract a value from a buffer of JSON without parsing the whole thing.
- [csv-parser](https://github.com/mafintosh/csv-parser) - Streaming CSV parser that aims to be faster than everyone else.
- [excel-stream](https://github.com/dominictarr/excel-stream) - Streaming Excel spreadsheet to JSON parser.
- [google-libphonenumber](https://github.com/seegno/google-libphonenumber) - Parse, format, store and validate phone numbers.
- [Jison](http://zaach.github.io/jison/) - Friendly JavaScript parser generator. It shares genes with Bison, Yacc and family.
- [js-yaml](https://github.com/nodeca/js-yaml) - Very fast YAML parser.
- [json-mask](https://github.com/nemtsov/json-mask) - Tiny language and engine for selecting parts of an object, hiding/masking the rest.
- [JSONStream](https://github.com/dominictarr/JSONStream) - Streaming JSON.parse and stringify.
- [markdown-it](https://github.com/markdown-it/markdown-it) - Markdown parser with 100% CommonMark support, extensions and syntax plugins.
- [nearley](https://github.com/Hardmath123/nearley) - Simple, fast, powerful parsing for JavaScript.
- [neat-csv](https://github.com/sindresorhus/neat-csv) - Fast CSV parser. Callback interface for the above.
- [parse-json](https://github.com/sindresorhus/parse-json) - Parse JSON with more helpful errors.
- [parse5](https://github.com/inikulin/parse5) - Fast full-featured spec compliant HTML parser.
- [PEG.js](https://github.com/pegjs/pegjs) - Simple parser generator that produces fast parsers with excellent error reporting.
- [PostCSS](https://github.com/postcss/postcss) - CSS parser / stringifier.
- [ref](https://github.com/TooTallNate/ref) - Read/write structured binary data in Buffers.
- [remark](https://github.com/wooorm/remark) - Markdown processor powered by plugins.
- [strip-css-comments](https://github.com/sindresorhus/strip-css-comments) - Strip comments from CSS.
- [strip-json-comments](https://github.com/sindresorhus/strip-json-comments) - Strip comments from JSON.
- [Stylecow](https://github.com/stylecow/stylecow) - Parse, manipulate and convert modern CSS to make it compatible with all browsers. Extensible with plugins.
- [URI.js](https://github.com/medialize/URI.js) - URL mutation.
- [x-ray](https://github.com/lapwinglabs/x-ray) - Web scraping utility.
- [xlsx-populate](https://github.com/dtjohnson/xlsx-populate) - Read/write Excel XLSX.
- [xml2js](https://github.com/Leonidas-from-XIV/node-xml2js) - XML to JavaScript object converter.


### Humanize

- [humanize](https://github.com/taijinlee/humanize) - Data formatter for human readability.
- [ms](https://github.com/rauchg/ms.js) - Tiny millisecond conversion utility.
- [pretty-bytes](https://github.com/sindresorhus/pretty-bytes) - Convert bytes to a human readable string: `1337` → `1.34 kB`.
- [pretty-error](https://github.com/AriaMinaei/pretty-error) - Errors with less clutter.
- [pretty-ms](https://github.com/sindresorhus/pretty-ms) - Convert milliseconds to a human readable string: `1337000000` → `15d 11h 23m 20s`.
- [read-art](https://github.com/Tjatse/node-readability) - Extract readable content from any page.


### Compression

- [Archiver](https://github.com/archiverjs/node-archiver) - Streaming interface for archive generation, supporting ZIP and TAR.
- [decompress](https://github.com/kevva/decompress) - Decompression module with support for `tar`, `tar.gz` and `zip` files out of the box.
- [pako](https://github.com/nodeca/pako) - High speed zlib port to pure js (deflate, inflate, gzip).
- [tar-stream](https://github.com/mafintosh/tar-stream) - Streaming tar parser and generator. Also see [tar-fs](https://github.com/mafintosh/tar-fs).
- [yauzl](https://github.com/thejoshwolfe/yauzl) - Unzip.
- [yazl](https://github.com/thejoshwolfe/yazl) - Zip.


### Network

- [DHCP](https://github.com/infusion/node-dhcp) - DHCP client and server.
- [get-port](https://github.com/sindresorhus/get-port) - Get an available port.
- [getmac](https://github.com/bevry/getmac) - Get the computer MAC address.
- [ipify](https://github.com/sindresorhus/ipify) - Get your public IP address.
- [polo](https://github.com/mafintosh/polo) - Zero-config service discovery.


### Database

	- [Aerospike](https://github.com/aerospike/aerospike-client-nodejs) - Aerospike client.
	- [Bookshelf](http://bookshelfjs.org) - ORM for PostgreSQL, MySQL and SQLite3 in the style of Backbone.js.
	- [Couchbase](https://github.com/couchbase/couchnode) - Couchbase client.
	- [firenze](https://github.com/fahad19/firenze) - Adapter-based ORM for MySQL, Memory, Redis, localStorage and more.
	- [Iridium](https://github.com/SierraSoftworks/Iridium) - MongoDB ORM with support for promises, distributed caching, preprocessing, validation and plugins.
	- [Knex](http://knexjs.org) - Query builder for PostgreSQL, MySQL and SQLite3, designed to be flexible, portable, and fun to use.
	- [LevelUP](https://github.com/Level/levelup) - LevelDB.
	- [Lowdb](https://github.com/typicode/lowdb) - Small JavaScript database powered by Lodash.
	- [Massive](https://github.com/robconery/massive-js) - PostgreSQL data access tool.
	- [MongoDB](https://github.com/mongodb/node-mongodb-native) - MongoDB driver.
	- [Mongoose](http://mongoosejs.com) - Elegant MongoDB object modeling.
	- [MySQL](https://github.com/mysqljs/mysql) - MySQL client.
	- [nano](https://github.com/dscape/nano) - CouchDB client.
	- [NeDB](https://github.com/louischatriot/nedb) - Embedded persistent database written in JavaScript.
	- [Objection.js](https://github.com/Vincit/objection.js) - Lightweight ORM built on the SQL query builder Knex.
	- [OpenRecord](https://github.com/PhilWaldmann/openrecord) - ORM for PostgreSQL, MySQL, SQLite3 and RESTful datastores. Similar to ActiveRecord.
	- [orm2](https://github.com/dresende/node-orm2) - ORM for PostgreSQL, MariaDB, MySQL, Amazon Redshift, SQLite, MongoDB.
	- [pg-promise](https://github.com/vitaly-t/pg-promise) - PostgreSQL framework for native SQL using promises.
	- [PostgreSQL](https://github.com/brianc/node-postgres) - PostgreSQL client. Pure JavaScript and native libpq bindings.
	- [Redis](https://github.com/luin/ioredis) - Redis client.
	- [Sequelize](https://github.com/sequelize/sequelize) - Multi-dialect ORM. Supports PostgreSQL, SQLite, MySQL.
	- [Waterline](https://github.com/balderdashy/waterline) - Datastore-agnostic tool that dramatically simplifies interaction with one or more databases.
- Drivers
- ODM / ORM
- Other
- Query builder


### Testing

- [AVA](https://ava.li) - Futuristic test runner.
- [hook-std](https://github.com/sindresorhus/hook-std) - Hook and modify stdout/stderr.
- [intern](https://github.com/theintern/intern) - Code testing stack.
- [Jest](https://github.com/facebook/jest) - Painless JavaScript testing.
- [loadtest](https://github.com/alexfernandez/loadtest) - Run load tests for your web application, with an API for automation.
- [Mocha](http://mochajs.org) - Feature-rich test framework making asynchronous testing simple and fun.
- [Mochify](https://github.com/mantoni/mochify.js) - TDD with Browserify, Mocha, PhantomJS and WebDriver.
- [navit](https://github.com/nodeca/navit) - PhantomJS / SlimerJS wrapper to simplify browser test scripting.
- [Nightwatch](https://github.com/nightwatchjs/nightwatch) - Automated UI testing framework based on Selenium WebDriver.
- [nock](https://github.com/pgte/nock) - HTTP mocking and expectations.
- [nyc](https://github.com/bcoe/nyc) - Code coverage tool built on istanbul that works with subprocesses.
- [power-assert](https://github.com/power-assert-js/power-assert) - Provides descriptive assertion messages through the standard assert interface.
- [Sinon.JS](https://github.com/sinonjs/sinon) - Test spies, stubs and mocks.
- [tap](https://github.com/isaacs/node-tap) - TAP test framework.
- [tape](https://github.com/substack/tape) - TAP-producing test harness.
- [TestCafe](https://github.com/DevExpress/testcafe) - Automated browser testing.
- [testen](https://github.com/egoist/testen) - Run tests for multiple versions of Node.js locally with NVM.
- [toxy](https://github.com/h2non/toxy) - Hackable HTTP proxy to simulate failure scenarios and network conditions.
- [trevor](https://github.com/vdemedes/trevor) - Run tests against multiple versions of Node.js without switching versions manually or pushing to Travis CI.
- [WebdriverIO](http://webdriver.io) - Automated testing based on the WebDriver protocol.


### Security

- [nsp](https://github.com/nodesecurity/nsp) - CLI tool to identify known vulnerabilities in your project.
- [RegEx-DoS](https://github.com/jagracey/RegEx-DoS) - CLI tool to identify possible regex denial of service (ReDos) vulnerabilities in your project.
- [snyk](https://github.com/Snyk/snyk) - CLI and build-time tool to find & fix vulnerable npm dependencies.


### Benchmarking

- [Benchmark.js](http://benchmarkjs.com) - Benchmarking library that supports high-resolution timers and returns statistically significant results.
- [matcha](https://github.com/logicalparadox/matcha) - Simplistic approach to benchmarking.


### Minifiers

- [babili](https://github.com/babel/babili) - ES2015+ aware minifier based on the Babel toolchain.
- [clean-css](https://github.com/jakubpawlowicz/clean-css) - CSS minifier.
- [imagemin](https://github.com/imagemin/imagemin) - Image minifier.
- [minimize](https://github.com/Swaagie/minimize) - HTML minifier.
- [UglifyJS2](http://lisperator.net/uglifyjs/) - JavaScript minifier.


### Authentication

- [CloudRail](https://github.com/CloudRail/cloudrail-si-node-sdk) - Unified API for social authentication (Facebook, Twitter, Slack, Instagram, …).
- [everyauth](https://github.com/bnoguchi/everyauth) - Authentication and authorization (password, Facebook, etc) for your Connect and Express apps.
- [Grant](https://github.com/simov/grant) - OAuth middleware for Express, Koa, and Hapi.
- [Lockit](https://github.com/zemirco/lockit) - Full featured authentication solution for Express. Supports a variety of databases, predefined routes, email and two-factor authentication.
- [Passport](http://passportjs.org) - Simple, unobtrusive authentication.
- [passwordless](https://passwordless.net) - Token-based authentication middleware for Express allowing authentication without passwords.


### Email

- [emailjs](https://github.com/eleith/emailjs) - Send text/HTML emails with attachments to any SMTP server.
- [Nodemailer](https://github.com/andris9/Nodemailer) - The fastest way to handle email.


### Job queues

- [agenda](https://github.com/rschmukler/agenda) - Lightweight job scheduling on MongoDB.
- [bull](https://github.com/OptimalBits/bull) - Persistent job and message queue.
- [idoit](https://github.com/nodeca/idoit) - Redis-backed job queue engine with advanced job control.
- [kue](https://github.com/Automattic/kue) - Priority job queue backed by Redis.
- [node-resque](https://github.com/taskrabbit/node-resque) - Redis-backed job queue.


### Node.js management

- [n](https://github.com/tj/n) - Node.js version management.
- [nave](https://github.com/isaacs/nave) - Virtual Environments for Node.js.
- [nodeenv](https://github.com/ekalinin/nodeenv) - Node.js virtual environment compatible to Python's virtualenv.
- [nvm for Windows](https://github.com/coreybutler/nvm-windows) - Version management for Windows.


### Polyfills

	- [buffer-includes](https://github.com/sindresorhus/buffer-includes) - Node.js 5.3 `buffer.includes()` ponyfill.
	- [deep-strict-equal](https://github.com/sindresorhus/deep-strict-equal) - Test for deep equality - Node.js `assert.deepStrictEqual()` algorithm as a standalone module.
	- [es6-shim](https://github.com/paulmillr/es6-shim) - Collection of ES2015 polyfills.
	- [harmony-reflect](https://github.com/tvcutsem/harmony-reflect) - ES2015 `Reflect` and `Proxy` polyfill.
	- [user-info](https://github.com/sindresorhus/user-info) - Node.js 6 `os.userInfo()` ponyfill.
- JavaScript
- Node.js


### Natural language processing

- [franc](https://github.com/wooorm/franc) - Detect the language of text.
- [leven](https://github.com/sindresorhus/leven) - Measure the difference between two strings using the Levenshtein distance algorithm.
- [natural](https://github.com/NaturalNode/natural) - Natural language facility.
- [retext](https://github.com/wooorm/retext) - An extensible natural language system.


### Process management

- [forever](https://github.com/foreverjs/forever) - Ensures that a given script runs continuously.
- [naught](https://github.com/andrewrk/naught) - Process manager with zero downtime deployment.
- [node-linux](https://github.com/coreybutler/node-linux) - Run scripts as native system service and log to syslog.
- [node-mac](https://github.com/coreybutler/node-mac) - Run scripts as a native Mac daemon and log to the console app.
- [node-windows](https://github.com/coreybutler/node-windows) - Run scripts as a native Windows service and log to the Event viewer.
- [nodemon](https://github.com/remy/nodemon) - Monitor for changes in your app and automatically restart the server.
- [Phusion Passenger](https://www.phusionpassenger.com) - Friendly process manager that integrates directly into Nginx.
- [PM2](https://github.com/Unitech/pm2) - Advanced Process Manager.
- [supervisor](https://github.com/petruisfan/node-supervisor) - Restart scripts when they crash or restart when a `*.js` file changes.


### Automation

- [robotjs](https://github.com/octalmage/robotjs) - Desktop Automation: control the mouse, keyboard and read the screen.


### AST

- [Acorn](https://github.com/ternjs/acorn) - Tiny, fast JavaScript parser.
- [Rocambole](https://github.com/millermedeiros/rocambole) - Recursively walk and transform JavaScript AST.


### Static site generators

- [Assemble](http://assemble.io) - Static site generator for Node.js, Grunt.js, and Yeoman.
- [DocPad](https://github.com/docpad/docpad) - Static site generator with dynamic abilities and huge plugin ecosystem.
- [docsify](https://docsify.js.org) - Markdown documentation site generator with no statically built HTML files.
- [Metalsmith](http://www.metalsmith.io) - Pluggable static site generator.
- [Phenomic](https://phenomic.io) - Modern static website generator based on the React and Webpack ecosystem.
- [Wintersmith](http://wintersmith.io) - Flexible, minimalistic, multi-platform static site generator.


### Content management systems

- [Apostrophe2](http://apostrophenow.org) - Content management system with an emphasis on intuitive front end content editing and administration built on Express and MongoDB.
- [KeystoneJS](http://keystonejs.com) - CMS and web application platform built on Express and MongoDB.


### Forum

- [nodeBB](https://nodebb.org) - Forum platform for the modern web.


### Blogging

- [ghost](https://ghost.org) - Simple, powerful publishing platform.
- [Hexo](https://hexo.io) - Fast, simple and powerful blogging framework.


### Weird

- [cat-ascii-faces](https://github.com/melaniecebula/cat-ascii-faces) - ₍˄·͈༝·͈˄₎◞ ̑̑ෆ⃛ (=ↀωↀ=)✧ (^･o･^)ﾉ”
- [cat-names](https://github.com/sindresorhus/cat-names) - Get popular cat names.
- [cool-ascii-faces](https://github.com/maxogden/cool-ascii-faces) - Get some cool ascii faces.
- [cows](https://github.com/sindresorhus/cows) - ASCII cows.
- [dog-names](https://github.com/sindresorhus/dog-names) - Get popular dog names.
- [nerds](https://github.com/SkyHacks/nerds) - Get data from nerdy topics like Harry Potter, Star Wars, and Pokémon.
- [superb](https://github.com/sindresorhus/superb) - Get superb like words.
- [superheroes](https://github.com/sindresorhus/superheroes) - Get superhero names.
- [supervillains](https://github.com/sindresorhus/supervillains) - Get supervillain names.


### Miscellaneous



## Resources
- [adit](https://github.com/markelog/adit) - SSH tunneling made simple.
- [Bottleneck](https://github.com/SGrondin/bottleneck) - Rate limiter that makes throttling easy.
- [cheerio](https://github.com/cheeriojs/cheerio) - Fast, flexible, and lean implementation of core jQuery designed specifically for the server.
- [clipboardy](https://github.com/sindresorhus/clipboardy) - Access the system clipboard (copy/paste).
- [dot-prop](https://github.com/sindresorhus/dot-prop) - Get a property from a nested object using a dot path.
- [dotenv](https://github.com/motdotla/dotenv) - Load environment variables from .env file.
- [Electron](https://github.com/atom/electron) - Build cross platform desktop apps with web technologies. *(You might like [awesome-electron](https://github.com/sindresorhus/awesome-electron))*
- [execa](https://github.com/sindresorhus/execa) - Better `child_process`.
- [Faker.js](https://github.com/Marak/Faker.js) - Generate massive amounts of fake data.
- [file-type](https://github.com/sindresorhus/file-type) - Detect the file type of a Buffer.
- [hasha](https://github.com/sindresorhus/hasha) - Hashing made simple. Get the hash of a buffer/string/stream/file.
- [hypernova](https://github.com/airbnb/hypernova) - Server-side rendering your JavaScript views.
- [import-fresh](https://github.com/sindresorhus/import-fresh) - Import a module while bypassing the cache.
- [import-lazy](https://github.com/sindresorhus/import-lazy) - Import a module lazily.
- [jsdom](https://github.com/tmpvar/jsdom) - JavaScript implementation of HTML and the DOM.
- [json-strictify](https://github.com/pigulla/json-strictify) - Safely serialize a value to JSON without data loss or going into an infinite loop.
- [mem](https://github.com/sindresorhus/mem) - Memoize functions - an optimization technique used to speed up consecutive function calls by caching the result of calls with identical input.
- [nan](https://github.com/nodejs/nan) - Makes native add-on development for across Node.js versions easier.
- [node-pre-gyp](https://github.com/mapbox/node-pre-gyp) - Makes it easy to publish and install Node.js C++ addons from binaries.
- [nodegit](https://github.com/nodegit/nodegit) - Native bindings to Git.
- [onetime](https://github.com/sindresorhus/onetime) - Only run a function once.
- [opencv](https://github.com/peterbraden/node-opencv) - Bindings for OpenCV. The defacto computer vision library.
- [opn](https://github.com/sindresorhus/opn) - Opens stuff like websites, files, executables.
- [os-locale](https://github.com/sindresorhus/os-locale) - Get the system locale.
- [parent-module](https://github.com/sindresorhus/parent-module) - Get the path of the parent module.
- [remote-git-tags](https://github.com/sindresorhus/remote-git-tags) - Get tags from a remote git repo.
- [resolve-from](https://github.com/sindresorhus/resolve-from) - Resolve the path of a module like `require.resolve()` but from a given path.
- [semver](https://github.com/npm/node-semver) - [semver](http://semver.org) parser.
- [simplecrawler](https://github.com/cgiffard/node-simplecrawler) - Event driven web crawler.
- [ssh2](https://github.com/mscdex/ssh2) - SSH2 client and server module.
- [strip-bom](https://github.com/sindresorhus/strip-bom) - Strip UTF-8 byte order mark (BOM) from a string/buffer/stream.
- [webworker-threads](https://github.com/audreyt/node-webworker-threads) - Lightweight Web Worker API implementation with native threads.

### Tutorials

- [browserify-handbook](https://github.com/substack/browserify-handbook) - The definitive guide for browserify.
- [module-best-practices](https://github.com/mattdesl/module-best-practices) - Some good practices when writing new npm modules.
- [Nodeschool](http://nodeschool.io) - Learn Node.js with interactive lessons.
- [stream-handbook](https://github.com/substack/stream-handbook) - How to write Node.js programs with streams.
- [The Art of Node](https://github.com/maxogden/art-of-node/#the-art-of-node) - An introduction to Node.js.
- [The Node Way](http://thenodeway.io) - An entire philosophy of Node.js best practices and guiding principles exists for writing maintainable modules, scalable applications, and code that is actually pleasant to read.
- [You Don't Know Node.js](https://github.com/azat-co/you-dont-know-node) - Introduction to Node.js core features and asynchronous JavaScript.


### Discovery

- [node-modules.com](http://node-modules.com) - An alternative npm search engine with a more intelligent and personal results ranking.
- [npm addict](https://npmaddict.com) - Your daily injection of npm packages.
- [npmcompare.com](https://npmcompare.com) - Compare and discover npm packages.
- [npms](https://npms.io) - Superb package search with deep analysis of package quality using a [myriad of metrics](https://npms.io/about).

### Articles

- [Art of README](https://github.com/noffle/art-of-readme) - Learn the art of writing quality READMEs.
- [Error Handling in Node.js](https://www.joyent.com/node-js/production/design/errors)
- [Mastering the filesystem in Node.js](https://medium.com/@yoshuawuyts/mastering-the-filesystem-in-node-js-4706b7cb0801)
- [Semver: A Primer](https://nodesource.com/blog/semver-a-primer/)
- [Semver: Tilde and Caret](https://nodesource.com/blog/semver-tilde-and-caret/)
- [Teach Yourself Node.js in 10 Steps](https://ponyfoo.com/articles/teach-yourself-nodejs-in-10-steps)
- [Understanding Object Streams](https://nodesource.com/blog/understanding-object-streams/)
- [Understanding the Node.js Event Loop](https://nodesource.com/blog/understanding-the-nodejs-event-loop/)
- [Why Asynchronous?](https://nodesource.com/blog/why-asynchronous/)

### Newsletters

- [nmotw](http://nmotw.in) - Node Module Of The Week, weekly dose of hand picked node modules.
- [node weekly](http://nodeweekly.com) - Weekly e-mail round-up of Node.js news and articles.

### Videos

- [Full Streams Ahead](http://dry.ly/full-streams-ahead) - Introduction to streams.
- [Hands on with Node.js](https://learn.bevry.me/node/preface)
- [Introduction to Node.js Fundamentals](http://strongloop.com/node-js/videos/#a-video-intro-to-nodejs-fundamentals)
- [Introduction to Node.js with Ryan Dahl](https://www.youtube.com/watch?v=jo_B4LTHi3I)
- [Node Interactive 2015](https://github.com/duffn/nodeinteractive-2015) - List of talks, keynotes and panels from the 2015 Node Interactive conference.
- [Nodetuts](http://nodetuts.com) - Series of talks, including TCP & HTTP API servers, async programming, and more.
- [StrongLoop Talks](https://strongloop.com/node-js/videos/) - Series of talks.
- [thenewboston's Node.js for Beginners](https://www.thenewboston.com/videos.php?cat=355)

### Podcasts

- [Mostly Node](http://mostlynode.com)
- [NodeUp](http://nodeup.com)

### Books

- [Express in Action](https://www.manning.com/books/express-in-action)
- [Mastering Node](http://visionmedia.github.io/masteringnode/)
- [Mixu's Node book](http://book.mixu.net/node/)
- [Node.js in Action](http://www.amazon.com/Node-js-Action-Mike-Cantelon/dp/1617290572)
- [Node.js in Practice](http://www.amazon.com/Node-js-Practice-Alex-R-Young/dp/1617290939)
- [Practical Node.js: Building Real-World Scalable Web Apps](http://practicalnodebook.com)
- [Pro Express.js](http://proexpressjs.com)
- [Professional Node.js: Building Javascript Based Scalable Software](http://www.amazon.com/Professional-Node-js-Building-Javascript-Scalable-ebook/dp/B009L7QETY/)
- [Secure Your Node.js Web Application](http://www.amazon.com/Secure-Your-Node-js-Web-Application/dp/1680500856)
- [Web Development with Node and Express](http://shop.oreilly.com/product/0636920032977.do)

### Blogs

- [HowToNode](http://howtonode.org) - Teaching how to do various tasks in Node.js as well as teach fundamental concepts that are needed to write effective code.
- [Node.js blog](https://nodejs.org/en/blog/)
- [webapplog.com](http://webapplog.com/tag/node-js/) - Blog posts on Node.js and JavaScript from the author of Practical Node.js and Pro Express.js Azat Mardan.

### Courses

- [Learn and Understand Node.js](https://www.udemy.com/understand-nodejs)
- [Learn to build apps and APIs with Node.js](https://learnnode.com/friend/AWESOME) - Video course by Wes Bos.
- [Real Time Web with Node.js](https://www.codeschool.com/courses/real-time-web-with-node-js)

### Cheatsheets

- [Express.js](https://github.com/azat-co/cheatsheets/blob/master/express4)
- [Stream FAQs](https://github.com/stephenplusplus/stream-faqs) - Answering common questions about streams, covering pagination, events, and more.

### Tools

- [npm-hub](https://chrome.google.com/webstore/detail/npm-hub/kbbbjimdjbjclaebffknlabpogocablj) - Chrome extension to display npm dependencies at the bottom of a repo's readme.
- [OctoLinker](https://chrome.google.com/webstore/detail/octolinker/jlmafbaeoofdegohdhinkhilhclaklkp) - Chrome extension that linkifies dependencies in package.json, .js, .jsx, .coffee and .md files on GitHub.
- [RequireBin](http://requirebin.com) - Shareable JavaScript programs powered by npm and browserify.
- [RunKit](http://blog.tonicdev.com/2015/09/30/embedded-tonic.html) - Embed a Node.js environment on any website.

### Community

- [`#node.js` on Freenode](http://webchat.freenode.net/?channels=node.js)
- [Gitter](https://gitter.im/nodejs/node)
- [Hashnode](https://hashnode.com/n/nodejs)
- [Reddit](https://www.reddit.com/r/node)
- [Stack Overflow](http://stackoverflow.com/questions/tagged/node.js)
- [Twitter](https://twitter.com/nodejs)

### Miscellaneous

- [awesome-cross-platform-nodejs](https://github.com/bcoe/awesome-cross-platform-nodejs) - Resources for writing and testing cross-platform code.
- [generator-nm](https://github.com/sindresorhus/generator-nm) - Scaffold out a node module.
- [Microsoft Node.js Guidelines](https://github.com/Microsoft/nodejs-guidelines) - Tips, tricks, and resources for working with Node.js on Microsoft platforms.
- [node-module-boilerplate](https://github.com/sindresorhus/node-module-boilerplate) - Boilerplate to kickstart creating a node module.
- [nodebots](http://nodebots.io) - Robots powered by JavaScript.


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Sindre Sorhus](http://sindresorhus.com) has waived all copyright and related or neighboring rights to this work.
