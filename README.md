# Perfect Blog Mustache Example

[![Perfect logo](http://www.perfect.org/github/Perfect_GH_header_854.jpg)](http://perfect.org/get-involved.html)

[![Perfect logo](http://www.perfect.org/github/Perfect_GH_button_1_Star.jpg)](https://github.com/PerfectlySoft/Perfect)
[![Perfect logo](http://www.perfect.org/github/Perfect_GH_button_2_Git.jpg)](https://gitter.im/PerfectlySoft/Perfect)
[![Perfect logo](http://www.perfect.org/github/Perfect_GH_button_3_twit.jpg)](https://twitter.com/perfectlysoft)
[![Perfect logo](http://www.perfect.org/github/Perfect_GH_button_4_slack.jpg)](http://perfect.ly)


[![Swift 3.0](https://img.shields.io/badge/Swift-3.0-orange.svg?style=flat)](https://developer.apple.com/swift/)
[![Platforms OS X | Linux](https://img.shields.io/badge/Platforms-OS%20X%20%7C%20Linux%20-lightgray.svg?style=flat)](https://developer.apple.com/swift/)
[![License Apache](https://img.shields.io/badge/License-Apache-lightgrey.svg?style=flat)](http://perfect.org/licensing.html)
[![Twitter](https://img.shields.io/badge/Twitter-@PerfectlySoft-blue.svg?style=flat)](http://twitter.com/PerfectlySoft)
[![Join the chat at https://gitter.im/PerfectlySoft/Perfect](https://img.shields.io/badge/Gitter-Join%20Chat-brightgreen.svg)](https://gitter.im/PerfectlySoft/Perfect?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![Slack Status](http://perfect.ly/badge.svg)](http://perfect.ly) [![GitHub version](https://badge.fury.io/gh/PerfectlySoft%2FPerfect-CURL.svg)](https://badge.fury.io/gh/PerfectlySoft%2FPerfect-CURL)

An Example Blog & Mustache Template System for Perfect

This project demonstrates the following:

* Mustache templating
* URL routing and handlers
* URL Variables
* Static file serving
* SQLite3 database setup, and search.

This package builds with Swift Package Manager and is part of the [Perfect](https://github.com/PerfectlySoft/Perfect) project.

Ensure you have installed Xcode 8.0 or later.

## Setup - Xcode 8

* Check out or download the project;
* In terminal, navigate to the directory and execute

```
swift package generate-xcodeproj
```

* Open `Perfect-Blog-Mustache.xcodeproj`

Due to the complexity of running static file serving from Xcode, we suggest running this project from Terminal.

## Setup - Terminal

* Check out or download the project;
* In terminal, navigate to the directory 
* Execute `swift build`
* Once the project has compiled, execute `./.build/debug/Perfect-Blog-Mustache`

```
[INFO] Starting HTTP server on 0.0.0.0:8181 with document root ./webroot
```

## Routes

* [http://localhost:8181](http://localhost:8181) - Generates the list of blog posts
* http://localhost:8181/story/{storyid} - Linked to from the blog list, this displays the detail of the blog post.

## Issues

We are transitioning to using JIRA for all bugs and support related issues, therefore the GitHub issues has been disabled.

If you find a mistake, bug, or any other helpful suggestion you'd like to make on the docs please head over to [http://jira.perfect.org:8080/servicedesk/customer/portal/1](http://jira.perfect.org:8080/servicedesk/customer/portal/1) and raise it.

A comprehensive list of open issues can be found at [http://jira.perfect.org:8080/projects/ISS/issues](http://jira.perfect.org:8080/projects/ISS/issues)


## Further Information
For more information on the Perfect project, please visit [perfect.org](http://perfect.org).