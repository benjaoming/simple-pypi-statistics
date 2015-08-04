===============================
simple-pypi-statistics
===============================

.. image:: https://img.shields.io/travis/benjaoming/simple_pypi_statistics.svg
        :target: https://travis-ci.org/benjaoming/simple_pypi_statistics

.. image:: https://img.shields.io/pypi/v/simple_pypi_statistics.svg
        :target: https://pypi.python.org/pypi/simple_pypi_statistics


API and commandline for fetching simple statistics from PyPi's API

* Free software: BSD license
* Documentation: https://simple_pypi_statistics.readthedocs.org.

Usage
-----

Run ``simple-pypi-statistics`` to show usage::

    simple-pypi-statistics
    
    Usage:
      simple-pypi-statistics [options] [verbose|json] <pypi-package>...
      simple-pypi-statistics (-h | --help)
      simple-pypi-statistics --version
    
    Options:
      --no-honeypot   Do not use honeypot for correcting bot/mirror pollution
                      [default: False]
      -h --help       Show this screen.
      --version       Show version.
    
    Examples:
      simple-pypi-statistics docopt  # Outputs everything about docopt
      simple-pypi-statistics docopt==0.1  # Outputs a specific version
      simple-pypi-statistics json docopt==0.1  # In JSON!
    
    Credits:
      Benjamin Bach -- updated script with honey pot corrections
      Alex Clark -- for making vanity, which this script is based on


Features
--------

* TODO
