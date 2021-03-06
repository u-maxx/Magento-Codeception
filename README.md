# Magento Codeception Tests

## Implemented Tests

* One Page Checkout

## Prerequisites

* Granted [HomeBrew](http://homebrew.sh) and [homebrew-php](https://github.com/Homebrew/homebrew-php#installation) are installed, execute:
    `brew install codeception`
* Selenium:
    `brew install selenium-server-standalone` and optionally `brew install chromedriver` if you want to test with Google Chrome
* PhantomJS:
    `brew install phantomjs`

## Running tests

* Execute `selenium-server -p 4444` or `phantomjs --webdriver=4444 --ignore-ssl-errors=true` in a separate terminal tab
* Then execute `codecept run acceptance --steps`

See [Running Tests](http://codeception.com/docs/02-GettingStarted#Running-Tests) for detailed info

