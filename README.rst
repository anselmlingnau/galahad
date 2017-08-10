========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |requires|
        | |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|

.. |docs| image:: https://readthedocs.org/projects/galahad/badge/?style=flat
    :target: https://readthedocs.org/projects/galahad
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/anselmlingnau/galahad.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/anselmlingnau/galahad

.. |requires| image:: https://requires.io/github/anselmlingnau/galahad/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/anselmlingnau/galahad/requirements/?branch=master

.. |codecov| image:: https://codecov.io/github/anselmlingnau/galahad/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/anselmlingnau/galahad

.. |version| image:: https://img.shields.io/pypi/v/galahad.svg
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/galahad

.. |commits-since| image:: https://img.shields.io/github/commits-since/anselmlingnau/galahad/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/anselmlingnau/galahad/compare/v0.1.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/galahad.svg
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/galahad

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/galahad.svg
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/galahad

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/galahad.svg
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/galahad


.. end-badges

A simple (but powerful) mailing list manager

* Free software: BSD license

Installation
============

::

    pip install galahad

Documentation
=============

https://galahad.readthedocs.io/

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
