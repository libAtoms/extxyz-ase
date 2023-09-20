========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |github-actions|
        | |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|


.. |github-actions| image:: https://github.com/libAtoms/extxyz-ase/actions/workflows/github-actions.yml/badge.svg
    :alt: GitHub Actions Build Status
    :target: https://github.com/libAtoms/extxyz-ase/actions

.. |codecov| image:: https://codecov.io/gh/libAtoms/extxyz-ase/branch/main/graphs/badge.svg?branch=main
    :alt: Coverage Status
    :target: https://app.codecov.io/github/libAtoms/extxyz-ase

.. |version| image:: https://img.shields.io/pypi/v/extxyz-ase.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/extxyz-ase

.. |wheel| image:: https://img.shields.io/pypi/wheel/extxyz-ase.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/extxyz-ase

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/extxyz-ase.svg
    :alt: Supported versions
    :target: https://pypi.org/project/extxyz-ase

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/extxyz-ase.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/extxyz-ase

.. |commits-since| image:: https://img.shields.io/github/commits-since/libAtoms/extxyz-ase/v0.0.1.svg
    :alt: Commits since latest release
    :target: https://github.com/libAtoms/extxyz-ase/compare/v0.0.1...main



.. end-badges

Extended XYZ I/O Plugin for use with the Atomic Simulation Environment (ASE)

* Free software: MIT license

Installation
============

::

    pip install extxyz-ase

You can also install the in-development version with::

    pip install https://github.com/libAtoms/extxyz-ase/archive/main.zip


Documentation
=============


https://libatoms.github.io/extxyz-ase


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
