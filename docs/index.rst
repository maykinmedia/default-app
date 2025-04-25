.. {{ project_name }} documentation master file, created by startproject.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to {{ project_name }}'s documentation!
=================================================

|build-status| |code-quality| |ruff| |coverage| |docs|

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


.. |build-status| image:: https://github.com/maykinmedia/{{ project_name }}/workflows/Run%20CI/badge.svg
    :alt: Build status
    :target: https://github.com/maykinmedia/{{ project_name }}/actions?query=workflow%3A%22Run+CI%22

.. |code-quality| image:: https://github.com/maykinmedia/{{ project_name }}/workflows/Code%20quality%20checks/badge.svg
     :alt: Code quality checks
     :target: https://github.com/maykinmedia/{{ project_name }}/actions?query=workflow%3A%22Code+quality+checks%22

.. |ruff| image:: https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/ruff/main/assets/badge/v2.json
    :target: https://github.com/astral-sh/ruff
    :alt: Ruff

.. |coverage| image:: https://codecov.io/gh/maykinmedia/{{ project_name }}/branch/master/graph/badge.svg
    :target: https://codecov.io/gh/maykinmedia/{{ project_name }}
    :alt: Coverage status

.. |docs| image:: https://readthedocs.org/projects/{{ project_name }}/badge/?version=latest
    :target: https://{{ project_name }}.readthedocs.io/en/latest/?badge=latest
    :alt: Documentation Status

.. |python-versions| image:: https://img.shields.io/pypi/pyversions/{{ project_name }}.svg

.. |django-versions| image:: https://img.shields.io/pypi/djversions/{{ project_name }}.svg

.. |pypi-version| image:: https://img.shields.io/pypi/v/{{ project_name }}.svg
    :target: https://pypi.org/project/{{ project_name }}/
