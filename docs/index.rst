.. Scout documentation master file, created by
   sphinx-quickstart on Sat Mar 28 11:51:29 2015.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

.. image:: http://media.charlesleifer.com/blog/photos/scout-logo.png

Scout is a RESTful search server written in Python. The search is powered by `SQLite's full-text search extension <http://sqlite.org/fts3.html>`_, and the web application utilizes the `Flask <http://flask.pocoo.org>`_ framework.

Features:

* Multiple search indexes present in a single database.
* RESTful design for easy indexing and searching.
* Simple key-based authentication (optional).
* Lightweight, low resource utilization, minimal setup required.
* Store search content and arbitrary metadata.
* Attach files or BLOBs to indexed documents.
* Multiple result ranking algorithms, porter stemmer.
* Besides full-text search, perform complex filtering based on metadata values.
* Comprehensive unit-tests.
* Supports SQLite `FTS4 <http://sqlite.org/fts3.html>`_ and the brand-new `FTS5 <http://sqlite.org/fts5.html>`_.

Contents:

.. toctree::
   :maxdepth: 2
   :glob:

   installation
   server
   client
   deployment
   hacks


Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

