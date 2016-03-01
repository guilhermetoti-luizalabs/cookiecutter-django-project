{{cookiecutter.repo_name}}
==========================

Installation
------------

Create a virtualenv (use ``virtualenvwrapper``): ::

    mkvirtualenv {{cookiecutter.repo_name}}


Install requirements via ``pip``: ::

    pip install django/requirements/development.txt


Create database tables: ::

    make syncdb


Run the project: ::

    make start


Tests
-----

To run the test suite, execute: ::

    make test


To show coverage details (in HTML), use: ::

    make test html
