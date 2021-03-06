# Change Log

## 1.0.0
#### 2016-08-23
* Added the RSpec Gem for writing unit tests.
* Added the WebMock Gem to stub HTTP requests to Oanda API when writing unit tests.
* Raises a NoMethodError exception when the method does not exist. Previously nil was returned.
* Raises an OandaApiV20::RequestError exception when the status code is not 2xx.
* Fixed an issue where the requests to Oanda API was limited to 30 requests per minute instead of 30 requests per second. Whoops!
* Fixed a bug where the response body would sometimes be nil and cause the client to crash.

## 0.0.6
#### 2016-08-18
* HTTP exception handling added.

## 0.0.5
#### 2016-08-16
* Added the Gemfile to allow the 'bundle install' command to work.

## 0.0.4
#### 2016-08-16
* Limit Oanda API requests to 30 per second.

## 0.0.3
#### 2016-08-14
* Persistent HTTP connections using the persistent_httparty Gem.

## 0.0.2
#### 2016-08-12
* README Documentation added.

## 0.0.1
#### 2016-08-09
* Functions to map to the Oanda API endpoints.
* Setting up gemspec file.
* Added gitignore.
* Added LICENSE.
* Added README.md.

## 0.0.0
#### 2016-06-16
* Initial commit.
