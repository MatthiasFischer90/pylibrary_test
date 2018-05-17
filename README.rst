========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis|
        | |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|

.. |docs| image:: https://readthedocs.org/projects/python-pylibrary_test/badge/?style=flat
    :target: https://readthedocs.org/projects/python-pylibrary_test
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/MatthiasFischer90/python-pylibrary_test.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/MatthiasFischer90/python-pylibrary_test

.. |codecov| image:: https://codecov.io/github/MatthiasFischer90/python-pylibrary_test/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/MatthiasFischer90/python-pylibrary_test

.. |version| image:: https://img.shields.io/pypi/v/pylibrary-test.svg
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/pylibrary-test

.. |commits-since| image:: https://img.shields.io/github/commits-since/MatthiasFischer90/python-pylibrary_test/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/MatthiasFischer90/python-pylibrary_test/compare/v0.1.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/pylibrary-test.svg
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/pylibrary-test

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/pylibrary-test.svg
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/pylibrary-test

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/pylibrary-test.svg
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/pylibrary-test


.. end-badges

Just a test for the pylibrary template

* Free software: BSD 2-Clause License

Installation
============

::

    pip install pylibrary-test

Documentation
=============

https://python-pylibrary_test.readthedocs.io/

Development
===========

To run the all tests run::

    tox

Note, to combine the coverage data from all the tox environments run:

.. list-table::
    :widths: 10 90
    :stub-columns: 1

    - - Windows
      - ::

            set PYTEST_ADDOPTS=--cov-append
            tox

    - - Other
      - ::

            PYTEST_ADDOPTS=--cov-append tox
