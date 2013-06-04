Experiments with the new Generators in Harmony
==============================================

Some experiments with [harmony generators](http://wiki.ecmascript.org/doku.php?id=harmony:generator_expressions).

## Run with Node

Install version 0.11.2 version of Node or higher, with [nvm](https://github.com/creationix/nvm) you can do

    nvm install v0.11.2

to install node. And then to run make sure you include the `--harmony` flag. For example

    node --harmony iteration.js

## Run with Chrome Canary

Install [Chrome Canary](https://www.google.com/intl/en/chrome/browser/canary.html). Open `iteration.html` in Chrome Canary.

Next serve the file via http using something like 

    python -m SimpleHTTPServer