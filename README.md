# Performance matters

## Initial speedtests (network throttle: Regular 2G 300ms, 250kb/s, 50kb/s)

### Network http request / network speedtest

![alt tag](https://raw.githubusercontent.com/zishrodrigues/performance-matters/master/screenshots/bootstrap-network.jpg)

The total loading time on a Regular 2G 300ms connection was *41,92 seconds*. A lot of this has to do with images, fonts and unefficient code.

### Google Pagespeed test

![alt tag](https://raw.githubusercontent.com/zishrodrigues/performance-matters/master/screenshots/bootstrap-pagespeed.jpg)

The page got a *48 out of 100* score. This is not good. The following feedback points came up:
* Javascript and CSS position
* Minimizing files
* Image compression

<<<<<<< HEAD
## Image compression speedtests (network throttle: Regular 2G 300ms, 250kb/s, 50kb/s)
=======


## **Image**

## Project setup

This project serves an adapted version of the [Bootstrap documentation website](http://getbootstrap.com/). It is based on the [github pages branche of Bootstrap](https://github.com/twbs/bootstrap/tree/gh-pages).

Differences from actual Bootstrap documentation:

- Added custom webfont
- Removed third party scripts
- The src directory is served with [Express](https://expressjs.com/).
- Templating is done with [Nunjucks](https://mozilla.github.io/nunjucks/)

## Getting started

- Install dependencies: `npm install`
- Serve: `npm start`
- Expose localhost: `npm run expose`
