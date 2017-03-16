# Javascript minified and in footer speedtests (network throttle: Regular 2G 300ms, 250kb/s, 50kb/s)

### Network http request / network speedtest

![alt tag](https://raw.githubusercontent.com/zishrodrigues/performance-matters/feature/js/screenshots/bootstrap-network-js.jpg)

The total loading time on a Regular 2G 300ms connection was *30.13 seconds*. This saves about 10 seconds. Adding minfied javascript and butting the js file links in the footer did help a bunch.

### Google Pagespeed test

![alt tag](https://raw.githubusercontent.com/zishrodrigues/performance-matters/feature/js/screenshots/bootstrap-pagespeed-js.jpg)

The page got a *53 out of 100* score. This is clearly better than before. We no longer have the minify Javascript feedback point!
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
