# Simple Angular 2 app written in TS

## Use latest TypeScript compiler
TypeScript 1.5 beta will include everything you need. Until that is released,
build your own TypeScript at HEAD. Follow the
[instructions on the TypeScript repo](https://github.com/Microsoft/TypeScript/#building)

## Start up the compiler
Because we built our own TypeScript, the command to run it is longer:

    $ cd ng2-ts-hello
    $ node ../TypeScript/built/local/tsc.js -w
    message TS6042: Compilation complete. Watching for file changes.

## Use a TypeScript-aware editor
We have good experience using these editors:

* [Webstorm 10](https://www.jetbrains.com/webstorm/download/)
* [Atom](https://atom.io/) with a modified [TypeScript plugin](https://atom.io/packages/atom-typescript)
* [Sublime Text](http://www.sublimetext.com/3) with [Typescript-Sublime-Plugin](https://github.com/Microsoft/Typescript-Sublime-plugin#installation)

## Load the app
From the directory that contains index.html:

    npm install -g http-server  # Or sudo npm install -g http-server
    http-server                 # Creates a server at localhost:8080
    # In a browser, visit localhost:8080/index.html
