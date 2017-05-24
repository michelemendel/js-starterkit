# js-starterkit
Based on Cory House's JavaScript Development Environment (Pluralsight)
https://app.pluralsight.com/library/courses/javascript-development-environment/exercise-files

## Checklist

* __Editors and Configuration__
  * .editorconfig : http://editorconfig.org/
* __Package Management__
  * __npm__ -> install node
  * nvm to handle multiple node versions
  * other package managers: jspm, jam, volo
  * Package security
    * retire.js
    * Node Security Platform : https://nodesecurity.io/
* __Development Web Server__
  * Local Servers
    * __express__ (production grade)
    * live-server (npm package)
    * http-server (npm package)
    * koa, hapi : express competitors
    * budo
    * webpack-dev-server
    * browsersync (IP for sharing on LAN, syncs between browsers, cross-device testing)
    *
  * Sharing Work-in-Progress
    * __localtunnel__ (npm, hole in firewall)
    * ngrok (npm, hole in firewall, secure)
    * Surge (hosted, static files only,)
    * now (hosted, production)
* __Automation__
  * Task runners
    * Grunt - file oriented
    * Gulp - in-memory streams (pipes), faster than Grunt, code over configuration
  * npm scripts - Avoids an extra layer of abstraction. See https://medium.freecodecamp.com/why-i-left-gulp-and-grunt-for-npm-scripts-3d6853dd22b8
    * Run tasks in parallell - npm-run-all or use UNIX &
* __Transpiling__
  * Babel
  * TypeScript
  * Elm
* __Bundling__
  * Module Formats
    * IIFE
    * AMD
    * CommonJS
    * UMD
    * ES6 Modules
  * Bundlers
    * Browserify (CommonJS)
    * Webpack (import JS, images, CSS)
    * Rollup (tree shaking, faster startup)
    * JSPM (SystemJS, load modules at runtime, has its own package manager)
    * RequireJS (old)
* __Linting__
  * Linters
    * JSLint
    * JSHint - approvement on JSLint
    * ESLint - most popular
    * TSLint
  * Presets
    * Recommended
    * airbnb
    * XO
    * Standard JS (not actually a standard)
* __Testing and Continuous Integration__
* __HTTP Calls__
* __Project Structure__
  * Organize files by file type or feature
* __Production Build__
  * minification
  * Error logging
    * TrackJS
    * Sentry
    * New Relic
    * Raygun
  * JS Error Logging - What to look for
    * Error Metadata
      * Browser
      * Stack Trace
      * Previous actions
      * Custom API for enhanced tracking
    * Notifications & integrations
    * Analytics and filtering
    * Price
  
  
* __Production Deploy__

## Course data

package.json
https://gist.github.com/coryhouse/29bd1029b623beb4c7f79b748dcba844
  

## Mock HTTP

* nock
* Static JSON
* Dev server
  * api-mock
  * JSON-server
  * JSON Schema
    * JSON schema faker
      * faker.js
      * chance.js
      * randexp.js
  * BrowserSync
  * Express


## Misc links

* polyfill.io
* Mock data schema for the course: https://gist.github.com/coryhouse/300ed803148caaf9d4f3f45d1a03874d
