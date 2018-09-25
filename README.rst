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

    $ virtualenv env or virtualenv --python=/usr/bin/python3.6 env
    $ source env/bin/activate
    $ pip install django

Start a new Django project, named ``<project_name>``, using the template. This
will be your Python import path.

.. code-block:: bash

    $ django-admin startproject --template=https://github.com/maykinmedia/default-app/archive/master.zip --extension=py-tpl,rst,html,gitignore,json,in,ini,sh,cfg,yml,LICENSE <project_name> .

{% endcomment %}

.. {{ project_name }} documentation master file, created by startproject.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to {{ project_name }}'s documentation!
=================================================

:Version: 0.1.0
:Source: https://github.com/maykinmedia/{{ project_name }}
:Keywords: ``<keywords>``
:PythonVersion: 3.6

|build-status| |requirements| |coverage|

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

* Python 3.6 or above
* setuptools 30.3.0 or above
* Django 1.11 or above


Install
-------

.. code-block:: bash

    pip install {{ project_name }}


Usage
=====

<document or refer to docs>



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
