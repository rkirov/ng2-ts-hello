# Simple Angular 2 app written in TS

## Use latest TypeScript compiler
TypeScript 1.5 beta will include everything you need. Until that is released,
we use a GitHub reference to the latest alpha.

    $ npm install -g github:mhegazy/TypeScript

## Start up the compiler

    $ cd ng2-ts-hello
    $ tsc -w
    message TS6042: Compilation complete. Watching for file changes.

## Use a TypeScript-aware editor
We have good experience using these editors:

* [Webstorm 10](https://www.jetbrains.com/webstorm/download/)
* [Atom](https://atom.io/) with [TypeScript plugin](https://atom.io/packages/atom-typescript)
* [Sublime Text](http://www.sublimetext.com/3) with [Typescript-Sublime-Plugin](https://github.com/Microsoft/Typescript-Sublime-plugin#installation)

## Load the app
From the directory that contains index.html:

    npm install -g http-server  # Or sudo npm install -g http-server
    http-server                 # Creates a server at localhost:8080
    # In a browser, visit localhost:8080/index.html
