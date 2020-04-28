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
.. |docs| image:: https://readthedocs.org/projects/symmetrical-chainsaw/badge/?style=flat
    :target: https://readthedocs.org/projects/symmetrical-chainsaw
    :alt: Documentation Status

.. |travis| image:: https://api.travis-ci.org/yang/symmetrical-chainsaw.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/yang/symmetrical-chainsaw

.. |version| image:: https://img.shields.io/pypi/v/symmetrical-chainsaw.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/symmetrical-chainsaw

.. |wheel| image:: https://img.shields.io/pypi/wheel/symmetrical-chainsaw.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/symmetrical-chainsaw

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/symmetrical-chainsaw.svg
    :alt: Supported versions
    :target: https://pypi.org/project/symmetrical-chainsaw

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/symmetrical-chainsaw.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/symmetrical-chainsaw

.. |commits-since| image:: https://img.shields.io/github/commits-since/yang/symmetrical-chainsaw/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/yang/symmetrical-chainsaw/compare/v0.0.0...master



.. end-badges

Travis playground.

* Free software: BSD 2-Clause License

Installation
============

::

    pip install symmetrical-chainsaw

You can also install the in-development version with::

    pip install https://github.com/yang/symmetrical-chainsaw/archive/master.zip


Documentation
=============


https://symmetrical-chainsaw.readthedocs.io/


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
