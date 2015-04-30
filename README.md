# Simple Angular 2 app written in TypeScript

## Use latest TypeScript compiler
TypeScript 1.5 beta will include everything you need. Until that is released,
we use a GitHub reference to the latest alpha.

    $ npm install -g typescript@^1.5.0-beta

## Start up the compiler

    $ cd ts-quickstart
    $ tsc -w
    message TS6042: Compilation complete. Watching for file changes.

## Use a TypeScript-aware editor
We have good experience using these editors:

* [Visual Studio Code](https://code.visualstudio.com/)
* [Webstorm 10](https://www.jetbrains.com/webstorm/download/)
* [Atom](https://atom.io/) with [TypeScript plugin](https://atom.io/packages/atom-typescript)
* [Sublime Text](http://www.sublimetext.com/3) with [Typescript-Sublime-Plugin](https://github.com/Microsoft/Typescript-Sublime-plugin#installation)

## Load the app
If you want to get up and running immediately, copy the completed sources:

    $ cp complete/* .

From the directory that contains index.html:

    $ npm install -g http-server  # Or sudo npm install -g http-server
    $ http-server                 # Creates a server at localhost:8080
    # In a browser, visit localhost:8080/index.html
