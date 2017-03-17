# Performance matters

I did an Audit of the Bootstrap documentation website. In each branch I added functionality or optimization which makes the page ever so fast. Check the [AUDIT.md](AUDIT.md) file for my first test and total result. Check the README.md of each branch to see how the specific optimization impacted speed. The development branch was used for our final test.

[Audit of the Bootstrap documentation website](AUDIT.md)

List of branche specific README's:

* [Images optimization](https://github.com/Zishrodrigues/performance-matters-bootstrap/tree/feature/images)
* [CSS optimization](https://github.com/Zishrodrigues/performance-matters-bootstrap/tree/feature/css)
* [JS optimization](https://github.com/Zishrodrigues/performance-matters-bootstrap/tree/feature/js)
* [Compression](https://github.com/Zishrodrigues/performance-matters-bootstrap/tree/feature/compress)

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
