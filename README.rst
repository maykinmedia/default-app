{% comment %}
===============
Getting started
===============

Below you'll find the steps to create a 3rd-party Django app from scratch,
using the Maykin Media starting template. The ``<project_root>`` is typically
placed in your home directory.

.. code-block:: bash

    $ mkdir <project_root>
    $ cd <project_root>

Create the virtual environment that holds your copy of Python and relevant
libraries:

.. code-block:: bash

    $ virtualenv env or virtualenv --python=/usr/bin/python3.10 env
    $ source env/bin/activate
    $ pip install django~=4.2.0

Start a new Django project, named ``<project_name>``, using the template. This
will be your Python import path.

.. code-block:: bash

    $ django-admin startproject --template=https://github.com/maykinmedia/default-app/archive/master.zip --extension=py-tpl,rst,gitignore,in,ini,cfg,toml,yml -x .github --name LICENSE <project_name> .

{% endcomment %}

Welcome to {{ project_name }}'s documentation!
=================================================

:Version: 0.1.0
:Source: https://github.com/maykinmedia/{{ project_name }}
:Keywords: ``<keywords>``
:PythonVersion: 3.10

|build-status| |code-quality| |black| |coverage| |docs|

|python-versions| |django-versions| |pypi-version|

<One liner describing the project>

.. contents::

.. section-numbering::

Features
========

* ...
* ...

Installation
============

Requirements
------------

* Python 3.10 or above
* Django 4.2 or newer


Install
-------

.. code-block:: bash

    pip install {{ project_name }}


Usage
=====

<document or refer to docs>

Local development
=================

To install and develop the library locally, use::

.. code-block:: bash

    pip install -e --no-build-isolation .[tests,coverage,docs,release]


.. |build-status| image:: https://github.com/maykinmedia/{{ project_name }}/workflows/Run%20CI/badge.svg
    :alt: Build status
    :target: https://github.com/maykinmedia/{{ project_name }}/actions?query=workflow%3A%22Run+CI%22

.. |code-quality| image:: https://github.com/maykinmedia/{{ project_name }}/workflows/Code%20quality%20checks/badge.svg
     :alt: Code quality checks
     :target: https://github.com/maykinmedia/{{ project_name }}/actions?query=workflow%3A%22Code+quality+checks%22

.. |black| image:: https://img.shields.io/badge/code%20style-black-000000.svg
    :target: https://github.com/psf/black

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
