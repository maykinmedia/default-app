{% comment %}
===============
Getting started
===============

Below you'll find the steps to create a 3rd-party Django app from scratch,
using the Maykin Media starting template. The ``<project_root>`` is typically
placed in your home directory.

.. code-block:: bash

    mkdir <project_root>
    cd <project_root>

Create the virtual environment that holds your copy of Python and relevant
libraries:

.. code-block:: bash

    virtualenv env or virtualenv --python=/usr/bin/python3.10 env
    source env/bin/activate
    pip install django~=4.2.0

Start a new Django project, named ``<project_name>``, using the template. This
will be your Python import path.

.. code-block:: bash

    django-admin startproject \
        --template=https://github.com/maykinmedia/default-app/archive/main.zip \
        --extension=py-tpl,rst,gitignore,in,ini,cfg,toml,yml,yaml \
        -x .github \
        --name LICENSE \
        <project_name> .

And then set up the Github actions workflows:

.. code-block:: bash

    mv dotgithub .github

{% endcomment %}

Welcome to {{ project_name }}'s documentation!
=================================================

:Version: 0.1.0
:Source: https://github.com/maykinmedia/{{ project_name }}
:Keywords: ``<keywords>``
:PythonVersion: 3.10

|build-status| |code-quality| |ruff| |coverage| |docs|

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

    pip install -e .[tests,coverage,docs,release]

When running management commands via ``django-admin``, make sure to add the root
directory to the python path (or use ``python -m django <command>``):

.. code-block:: bash

    export PYTHONPATH=. DJANGO_SETTINGS_MODULE=testapp.settings
    django-admin check
    # or other commands like:
    # django-admin makemessages -l nl


.. |build-status| image:: https://github.com/maykinmedia/{{ project_name }}/workflows/Run%20CI/badge.svg
    :alt: Build status
    :target: https://github.com/maykinmedia/{{ project_name }}/actions?query=workflow%3A%22Run+CI%22

.. |code-quality| image:: https://github.com/maykinmedia/{{ project_name }}/workflows/Code%20quality%20checks/badge.svg
     :alt: Code quality checks
     :target: https://github.com/maykinmedia/{{ project_name }}/actions?query=workflow%3A%22Code+quality+checks%22

.. |ruff| image:: https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/ruff/main/assets/badge/v2.json
    :target: https://github.com/astral-sh/ruff
    :alt: Ruff

.. |coverage| image:: https://codecov.io/gh/maykinmedia/{{ project_name }}/branch/main/graph/badge.svg
    :target: https://codecov.io/gh/maykinmedia/{{ project_name }}
    :alt: Coverage status

.. |docs| image:: https://readthedocs.org/projects/{{ project_name }}/badge/?version=latest
    :target: https://{{ project_name }}.readthedocs.io/en/latest/?badge=latest
    :alt: Documentation Status

.. |python-versions| image:: https://img.shields.io/pypi/pyversions/{{ project_name }}.svg

.. |django-versions| image:: https://img.shields.io/pypi/djversions/{{ project_name }}.svg

.. |pypi-version| image:: https://img.shields.io/pypi/v/{{ project_name }}.svg
    :target: https://pypi.org/project/{{ project_name }}/
