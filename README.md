# css minify speedtests (network throttle: Regular 2G 300ms, 250kb/s, 50kb/s)

### Network http request / network speedtest

![alt tag](https://raw.githubusercontent.com/zishrodrigues/performance-matters/feature/css/screenshots/bootstrap-network-css.jpg)

The loading time with css minified and with critical css was 32.32 seconds. We saved 10 seconds by fixing the css.

### Google Pagespeed test

![alt tag](https://raw.githubusercontent.com/zishrodrigues/performance-matters/feature/css/screenshots/bootstrap-pagespeed-css.jpg)

Somehow got a *49 out of 100* score. This is not good. I don't know why the wizards at pagespeed did this to us as the total loading time did decrease and we didn't get any new feedback points.

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
