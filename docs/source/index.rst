Bottle Utils documentation
==========================

Bottle Utils is a collection of packages that address typical problems
developing web sites and applications using `Bottle framework`_. This package
is created based on code we use at Outernet_ for various user-facing interfaces
as well as our own sites.

Bottle Utils are compatible with Python 2.7, and 3.4. Compatibility with other
versions of Python is possible, but not tested. It targets latest stable
release of Bottle.

Bottle Utils Ajax as a Bottle Utils package that addresses AJAX problems

Installation
============

Install using ``pip`` or ``easy_install``::

    pip install bottle-utils-common

To install the latest development version, install using the master zipball
URL::

    pip install https://github.com/Outernet-Project/bottle-utils-common/archive/master.zip

Source code
===========

The complete source code is licensed under BSD license (see ``LICENSE`` file in
the source package), and available `on GitHub`_.

Bottle Utils Common
===================

The ``bottle_utils.common`` module contains functions and constants that are
used in other modules.

This module also contains a few constants and variables that improve code that
targets both Python 2.x and Python 3.x. Note, though, that this mostly works in
the context of Bottle Utils and hasn't been tested in too many different
versions of Python. If you want a more comprehensive solution, you should look
at six_.

``bottle_utils.common.PY2`` is a constant that is set to ``True`` if Python
version is 2.x. Conversely, ``bottle_utils.common.PY3`` is used to detect if
Python version is 3.x.

This module also contains names ``unicode`` and ``basestring``, which work as
expected in both Python 2.x and Python 3.x.

Functions
---------

.. automodule:: bottle_utils.common
   :members:
   :exclude-members: unicode, basestring

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

.. _Bottle framework: http://bottlepy.org/
.. _Outernet: https://www.outernet.is/
.. _on GitHub: https://github.com/Outernet-Project/bottle-utils-common
.. _six: https://pypi.python.org/pypi/six
