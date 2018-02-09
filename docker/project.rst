.. project

A Project Starter
=================


An example Django project

::

	project/
	├── Dockerfile
	├── Dockerfile.local
	├── Makefile
	├── README.rst
	├── app
	│   ├── bootstrap.sh
	│   ├── features
	│   │   ├── example.feature
	│   │   └── steps
	│   │       └── example.py
	│   ├── manage.py
	│   ├── requirements
	│   │   ├── base.txt
	│   │   └── local.txt
	│   ├── setup.cfg
	│   ├── static
	│   ├── tests
	│   │   ├── __init__.py
	│   │   └── example_tests.py
	│   ├── udjango
	│   │   ├── __init__.py
	│   │   ├── settings.py
	│   │   ├── urls.py
	│   │   └── wsgi.py
	│   └── uwsgi.ini
	├── docker-compose.yml
	└── docs


The directory structure above details the layout of a typical Django project you might work on, adapted for use with a Dockerised workflow. In this chapter we will explore this and take a deep dive into the various parts of it.

This example project is also available on GitHub_ at XXX


.. _github: https://github.com
