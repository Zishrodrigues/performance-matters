# Gzip compression speedtests (network throttle: Regular 2G 300ms, 250kb/s, 50kb/s)

### Network http request / network speedtest

![alt tag](https://raw.githubusercontent.com/zishrodrigues/performance-matters/feature/compress/screenshots/bootstrap-network-compress.jpg)

The total loading time on a Regular 2G 300ms connection was *33.25 seconds*. This is better and compressing the project saved us about 9 seconds.

### Google Pagespeed test

![alt tag](https://raw.githubusercontent.com/zishrodrigues/performance-matters/feature/compress/screenshots/bootstrap-pagespeed-compress.jpg)

The page got a *57 out of 100* score. And a 59 / 100 on mobile This is better. We no longer have the "compress files" feedback point!

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
