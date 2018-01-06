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
        |
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|

.. |docs| image:: https://readthedocs.org/projects/autoschema/badge/?style=flat
    :target: https://readthedocs.org/projects/autoschema
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/fractaloop/autoschema.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/fractaloop/autoschema

.. |version| image:: https://img.shields.io/pypi/v/autoschema.svg
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/autoschema

.. |commits-since| image:: https://img.shields.io/github/commits-since/fractaloop/autoschema/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/fractaloop/autoschema/compare/v0.1.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/autoschema.svg
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/autoschema

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/autoschema.svg
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/autoschema

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/autoschema.svg
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/autoschema


.. end-badges

Automatically generate JSON schemas from sample documents.

* Free software: MIT license

Installation
============

::

    pip install autoschema

Documentation
=============

https://autoschema.readthedocs.io/

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
