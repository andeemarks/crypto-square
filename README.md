# crypto-square

A minimal Compojure web-app built for a presentation at [Yow West 2015][1], and providing a basic UI for the Crypto Square solution found [here][3].

## Prerequisites

You will need [Leiningen][2] 1.7.0 or above installed.

## Running

To start a web server for the application, run:

    ./up.sh

## Browser Tests

To test the app using [clj-webdriver][4] on port 5744, run:

    lein test

Note: this assumes you have the [Chrome Driver][5] installed at ~/bin/chromedriver

## License

Copyright © 2015

[1]: https://a.confui.com/-LsHgG00I
[2]: https://github.com/technomancy/leiningen
[3]: http://garajeando.blogspot.com.au/2015/05/exercism-crypto-square-in-clojure.html
[4]: https://github.com/semperos/clj-webdriver
[5]: https://sites.google.com/a/chromium.org/chromedriver/
