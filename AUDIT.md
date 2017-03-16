# page Audit

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

#### All in all quite a bad score. The page took way to long to load and there was little done for optimization. I set out to change this.

## final speedtests (network throttle: Regular 2G 300ms, 250kb/s, 50kb/s)

### Network http request / network speedtest

![alt tag](https://raw.githubusercontent.com/zishrodrigues/performance-matters/master/screenshots/bootstrap-network-total.jpg)

The total loading time on a Regular 2G 300ms connection was *5,60 seconds*. This is much better than we first started. We took about 40 seconds of the loading time and managed to make each request happen fast and in an order which doesn't allow for much blocking.

### Google Pagespeed test

![alt tag](https://raw.githubusercontent.com/zishrodrigues/performance-matters/master/screenshots/bootstrap-pagespeed-total.jpg)

The page got whopping a *88 out of 100* score. This is a lot better than we had before. Pagespeeds tells us we can do some extra images optimization but this could have an impact on the quality of the image. webp is also an upcoming possibility which we choose not to use, but is becoming a more enticing possibility with each week.

List of branch specific README's:

* [Images optimization](https://github.com/Zishrodrigues/performance-matters-bootstrap/tree/feature/images)
* [CSS optimization](https://github.com/Zishrodrigues/performance-matters-bootstrap/tree/feature/css)
* [JS optimization](https://github.com/Zishrodrigues/performance-matters-bootstrap/tree/feature/js)
* [Compression](https://github.com/Zishrodrigues/performance-matters-bootstrap/tree/feature/compress)
