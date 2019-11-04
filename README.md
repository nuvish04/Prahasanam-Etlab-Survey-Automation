# Prahasanam-Etlab-Survey-Automation

Etlab Survey-Full Browser Automation Using Selenium and Python

Introduction
============

Python language bindings for Selenium WebDriver.

The `selenium` package is used to automate web browser interaction from Python.

+-----------+--------------------------------------------------------------------------------------+
| **Home**: | http://www.seleniumhq.org                                                            |
+-----------+--------------------------------------------------------------------------------------+
| **Docs**: | `selenium package API <https://seleniumhq.github.io/selenium/docs/api/py/api.html>`_ |
+-----------+--------------------------------------------------------------------------------------+
| **Dev**:  | https://github.com/SeleniumHQ/Selenium                                               |
+-----------+--------------------------------------------------------------------------------------+
| **PyPI**: | https://pypi.org/project/selenium/                                                   |
+-----------+--------------------------------------------------------------------------------------+
| **IRC**:  | **#selenium** channel on freenode                                                    |
+-----------+--------------------------------------------------------------------------------------+

Several browsers/drivers are supported (Firefox, Chrome, Internet Explorer), as well as the Remote protocol.

Supported Python Versions
=========================

* Python 2.7, 3.4+

Installing
==========

If you have `pip <https://pip.pypa.io/>`_ on your system, you can simply install or upgrade the Python bindings::

    pip install -U selenium

Alternately, you can download the source distribution from `PyPI <https://pypi.org/project/selenium/#files>`_ (e.g. selenium-4.0.0a3.tar.gz), unarchive it, and run::

    python setup.py install

Note: You may want to consider using `virtualenv <http://www.virtualenv.org/>`_ to create isolated Python environments.

Drivers
=======

Selenium requires a driver to interface with the chosen browser. Firefox,
for example, requires `geckodriver <https://github.com/mozilla/geckodriver/releases>`_, which needs to be installed before the below examples can be run. Make sure it's in your `PATH`, e. g., place it in `/usr/bin` or `/usr/local/bin`.

Failure to observe this step will give you an error `selenium.common.exceptions.WebDriverException: Message: 'geckodriver' executable needs to be in PATH.`

Other supported browsers will have their own drivers available. Links to some of the more popular browser drivers follow.

+--------------+-----------------------------------------------------------------------+
| **Chrome**:  | https://chromedriver.chromium.org/downloads                           |
+--------------+-----------------------------------------------------------------------+
| **Edge**:    | https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/ |
+--------------+-----------------------------------------------------------------------+
| **Firefox**: | https://github.com/mozilla/geckodriver/releases                       |
+--------------+-----------------------------------------------------------------------+
| **Safari**:  | https://webkit.org/blog/6900/webdriver-support-in-safari-10/          |
+--------------+-----------------------------------------------------------------------+
