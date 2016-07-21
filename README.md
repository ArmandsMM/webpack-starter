# Webpack Starter

Webpack-Starter is a clean and simple boilerplate for building webpack-powered applications. It includes the es2015 preset and allows you to use both CommonJS and es2015 module syntax

### Version
1.0.0

### Usage


### Installation

Webpack-Starter requires [Node.js](https://nodejs.org/) v4+ to run.

```sh
$ npm install
```

### Dev Server

```sh
$ npm run server
```
IMPORTANT: The dev server runs on port **8080** by default. If you get an error it may be because that port is in use. If so, go to **/node_modules/webpack-dev-server/bin/webpack-dev-server.js** and change the 2 instances of **"8080"** to **"8000"** or whatever port you want

Then visit  [http://localhost:8080/](http://localhost:8080/) or whatever port you changed it to

### Compile
To compile all js to dist/app.bundle.js

```sh
$ webpack
```
