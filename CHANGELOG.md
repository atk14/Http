# Change Log
All notable changes to this project will be documented in this file.

## [Unreleased]

## [0.5.2] - 2020-11-01

- HTTPRequest::sslActive() fixed

## [0.5.1] - 2020-11-01

- HTTPRequest::sslActive() fixed

## [0.5] - 2020-10-31

- Added support for samesite option for cookies
- Added static method HTTPCookie::DefaultOptions()

## [0.4] - 2020-10-31

- Added method HTTPRequest::setSslActive()
- Project is being tested in PHP8

## [0.3.1] - 2020-02-12

- Content-Length header is being checked in HTTPXFile::GetInstance()

## [0.3] - 2019-10-22

### Added
- Added method HTTPResponse::setHeaders() for bulk HTTP header assignment
- Added methods HTTPRequest::getScheme() and getServerUrl()

### Fixed
- HTTPRequest::isServerOnStandardPort() fixed for usage in the shell
- method isServerOnStandardPort() tuned

## [0.2] - 2019-03-15

### Methods added
- HTTPRequest::setRequestAddress()
- HTTPRequest::getRemoteHostname()
- HTTPRequest::getQueryString()
- HTTPRequest::isServerOnStandardPort()

### Changed
- HTTPUploadedFile::moveToTemp() returns the new temporary filename

## [0.1] - 2017-11-30

