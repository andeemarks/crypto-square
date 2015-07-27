# crypto-square

[![Build Status](https://travis-ci.org/andeemarks/crypto-square.svg?branch=master)](https://travis-ci.org/andeemarks/crypto-square)

A minimal Compojure web-app built for a presentation at [Yow West 2015][1], and providing a basic UI for the Crypto Square solution found [here][3].

![](https://github.com/andeemarks/column-handler/blob/master/resources/public/img/services.png)

## Prerequisites

Currently building on [Leiningen][2] 2.5.1

## Running

To start a web server for the application, run:

    ./up.sh

## Browser Tests

To test the app using [clj-webdriver][4] on port 4000, run:

    lein midje

Note: this assumes you have the [Chrome Driver][5] installed at ~/bin/chromedriver

## License

Copyright © 2015

[1]: https://a.confui.com/-LsHgG00I
[2]: https://github.com/technomancy/leiningen
[3]: http://garajeando.blogspot.com.au/2015/05/exercism-crypto-square-in-clojure.html
[4]: https://github.com/semperos/clj-webdriver
[5]: https://sites.google.com/a/chromium.org/chromedriver/
