========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |appveyor| |requires|
        | |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|

.. |docs| image:: https://readthedocs.org/projects/python-anhinga/badge/?style=flat
    :target: https://readthedocs.org/projects/python-anhinga
    :alt: Documentation Status


.. |travis| image:: https://travis-ci.org/Labrys/python-anhinga.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/Labrys/python-anhinga

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/Labrys/python-anhinga?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/Labrys/python-anhinga

.. |requires| image:: https://requires.io/github/Labrys/python-anhinga/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/Labrys/python-anhinga/requirements/?branch=master

.. |codecov| image:: https://codecov.io/github/Labrys/python-anhinga/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/Labrys/python-anhinga

.. |version| image:: https://img.shields.io/pypi/v/anhinga.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/anhinga

.. |commits-since| image:: https://img.shields.io/github/commits-since/Labrys/python-anhinga/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/Labrys/python-anhinga/compare/v0.0.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/anhinga.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/anhinga

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/anhinga.svg
    :alt: Supported versions
    :target: https://pypi.org/project/anhinga

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/anhinga.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/anhinga


.. end-badges

"Set your python packages free with the power of Anhinga"

* Free software: MIT license

Installation
============

::

    pip install anhinga

Documentation
=============


https://python-anhinga.readthedocs.io/


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
