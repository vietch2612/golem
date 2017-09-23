Golem - Test Automation Framework 
[![Build Status](https://travis-ci.org/lucianopuccio/golem.svg?branch=master)](https://travis-ci.org/lucianopuccio/golem)
[![Documentation Status](http://readthedocs.org/projects/golem-framework/badge/?version=latest)](http://golem-framework.readthedocs.io/en/latest/?badge=latest)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
==================================================


Intro
--------------------------------------

>Automate end to end tests in minutes, not hours.


Golem is a complete test automation tool and framework for end-to-end testing. It creates powerful, robust and maintainable test suites , yet, it is easy to pick up and learn even without a lot of programming knowledge. It is based on Selenium Webdriver and it can be extended using Python.

**It can:**
* Use the Page Object pattern
* Write tests with multi data sets (data-driven)
* Run tests in parallel.
* Test APIs
* Run tests remotely (Selenium Grid or a cloud testing provider)
* It can be executed from Jenkins or any other CI tool 


**It has:**
* A complete GUI module (a web application) to write and execute tests
* A reporting engine and a web reports module
* An interactive console


***

## Contents

* [Pre-requisites](#pre-requisites)
* [Installation](#installation)
* [Quick Start](#quick-start)
* [Documentation](#documentation)
* [Roadmap](#roadmap)
* [License](#license)


Pre-requisites
--------------------------------------

Basic knowledge of Selenium Webdriver is required. Check out [this docs](golem-framework.readthedocs.io/en/latest/installation.html) first.


Installation
--------------------------------------

Golem works with Python 3.4+

```
pip install golem-framework
```

Read the full installation guide here: [http://golem-framework.readthedocs.io/en/latest/installation.html](golem-framework.readthedocs.io/en/latest/installation.html)

Quick Start
--------------------------------------

Create a test directory anywhere in your machine:

```
golem-admin createdirectory <directory_name>
```

Start the Web Module:

```
cd <directory_name>
python golem.py gui
```

The Web Module can be accessed at http://localhost:5000/

By default, the following user is available: username: *admin* / password: *admin*


Documentation
--------------------------------------

Read the full documentation here: [http://golem-framework.readthedocs.io/](http://golem-framework.readthedocs.io/)


Roadmap
--------------------------------------

Integrate with Appium for mobile testing


License
--------------------------------------

[MIT](https://tldrlegal.com/license/mit-license)