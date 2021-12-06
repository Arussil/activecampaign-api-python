========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - tests
      - |
        |
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|

.. |version| image:: https://img.shields.io/pypi/v/activecampaign-api-python.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/activecampaign-api-python

.. |wheel| image:: https://img.shields.io/pypi/wheel/activecampaign-api-python.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/activecampaign-api-python

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/activecampaign-api-python.svg
    :alt: Supported versions
    :target: https://pypi.org/project/activecampaign-api-python

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/activecampaign-api-python.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/activecampaign-api-python

.. |commits-since| image:: https://img.shields.io/github/commits-since/Arussil/activecampaign-api-python/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/Arussil/activecampaign-api-python/compare/v0.0.0...main

.. |black| image:: https://img.shields.io/badge/code%20style-black-000000.svg
    :alt: Black
    :target: https://github.com/psf/black


.. end-badges

Unofficial Python wrapper for the ActiveCampaign API

* Free software: BSD 3-Clause License

Installation
============

::

    pip install activecampaign-api-python

You can also install the in-development version with::

    pip install https://github.com/Arussil/activecampaign-api-python/archive/main.zip


Documentation
=============


To use the project:

.. code-block:: python

    import activecampaign_api


Development
===========

To run all the tests run::

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
