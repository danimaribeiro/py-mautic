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
        | |coveralls|
        | |scrutinizer| |codeclimate|
    * - package
      - |version| |downloads| |wheel| |supported-versions| |supported-implementations|

.. |docs| image:: https://readthedocs.org/projects/py-mautic/badge/?style=flat
    :target: https://readthedocs.org/projects/py-mautic
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/danimaribeiro/py-mautic.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/danimaribeiro/py-mautic

.. |coveralls| image:: https://coveralls.io/repos/danimaribeiro/py-mautic/badge.svg?branch=master&service=github
    :alt: Coverage Status
    :target: https://coveralls.io/r/danimaribeiro/py-mautic

.. |codeclimate| image:: https://codeclimate.com/github/danimaribeiro/py-mautic/badges/gpa.svg
   :target: https://codeclimate.com/github/danimaribeiro/py-mautic
   :alt: CodeClimate Quality Status

.. |version| image:: https://img.shields.io/pypi/v/pymautic.svg?style=flat
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/pymautic

.. |downloads| image:: https://img.shields.io/pypi/dm/pymautic.svg?style=flat
    :alt: PyPI Package monthly downloads
    :target: https://pypi.python.org/pypi/pymautic

.. |wheel| image:: https://img.shields.io/pypi/wheel/pymautic.svg?style=flat
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/pymautic

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/pymautic.svg?style=flat
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/pymautic

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/pymautic.svg?style=flat
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/pymautic

.. |scrutinizer| image:: https://img.shields.io/scrutinizer/g/danimaribeiro/py-mautic/master.svg?style=flat
    :alt: Scrutinizer Status
    :target: https://scrutinizer-ci.com/g/danimaribeiro/py-mautic/


.. end-badges

Python API to connect with Mautic Martketin Automation Tool

* Free software: BSD license

Installation
============

::

    pip install pymautic

Documentation
=============

https://py-mautic.readthedocs.org/

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
