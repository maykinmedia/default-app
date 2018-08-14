.. {{ project_name }} documentation master file, created by startproject.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to {{ project_name }}'s documentation!
=================================================

|build-status| |requirements| |coverage|

|python-versions| |django-versions| |pypi-version|

<One liner describing the project>

Features
========

* ...
* ...

.. toctree::
   :maxdepth: 2
   :caption: Contents:

   quickstart



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

.. |build-status| image:: https://travis-ci.org/maykinmedia/{{ project_name }}.svg?branch=develop
    :target: https://travis-ci.org/maykinmedia/{{ project_name }}

.. |requirements| image:: https://requires.io/github/maykinmedia/{{ project_name }}/requirements.svg?branch=develop
    :target: https://requires.io/github/maykinmedia/{{ project_name }}/requirements/?branch=develop
    :alt: Requirements status

.. |coverage| image:: https://codecov.io/gh/maykinmedia/{{ project_name }}/branch/develop/graph/badge.svg
    :target: https://codecov.io/gh/maykinmedia/{{ project_name }}
    :alt: Coverage status

.. |python-versions| image:: https://img.shields.io/pypi/pyversions/{{ project_name }}.svg

.. |django-versions| image:: https://img.shields.io/pypi/djversions/{{ project_name }}.svg

.. |pypi-version| image:: https://img.shields.io/pypi/v/{{ project_name }}.svg
    :target: https://pypi.org/project/{{ project_name }}/
