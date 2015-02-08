---
title: Presentation
author: Duncan McPherson
---

A basic node.js  server designed to run on a local machine for serving reveal.js presentations while not connected to the interwebs. Nearly all the work has been done by others, I have just put the bits together in the order I like.

It is designed to work with .Rmd files that are converted to HTML by my R package [Rcandoo](https://github.com/duncandoo/Rcandoo).

## Installation

1. Install [nvm](https://github.com/creationix/nvm)
```
$ git clone https://github.com/creationix/nvm ~/.nvm
$ cd ~/.nvm
$ source ~/.nvm/nvm.sh
```

2. Install [node](https://http://nodejs.org/)
```
$ nvm install stable
$ nvm alias default stable
```

3. Install [grunt](http://gruntjs.com/)
```
$ npm install -g grunt-cli
```

3. Clone and install this repo
```
$ git clone https://github.com/duncandoo/presentation
$ cd presentation
$ npm install
$ grunt serve
```
This should open your browser to [](http://localhost:8000) and display index.html.

4. Make your presentations  
Head over to [Rcandoo](https://github.com/duncandoo/Rcandoo) for details.

