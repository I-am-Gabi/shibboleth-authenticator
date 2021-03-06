..
   This file is part of the shibboleth-authenticator module for Invenio.
   Copyright (C) 2017  Helmholtz-Zentrum Dresden-Rossendorf

   This program is free software: you can redistribute it and/or modify
   it under the terms of the GNU General Public License as published by
   the Free Software Foundation, either version 3 of the License, or
   (at your option) any later version.

   This program is distributed in the hope that it will be useful,
   but WITHOUT ANY WARRANTY; without even the implied warranty of
   MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
   GNU General Public License for more details.

   You should have received a copy of the GNU General Public License
   along with this program.  If not, see <http://www.gnu.org/licenses/>.
..

.. image:: https://img.shields.io/travis/tobiasfrust/shibboleth-authenticator/master.svg
        :target: https://travis-ci.org/tobiasfrust/shibboleth-authenticator

.. image:: https://img.shields.io/coveralls/tobiasfrust/shibboleth-authenticator/master.svg
        :target: https://coveralls.io/github/tobiasfrust/shibboleth-authenticator

.. image:: https://img.shields.io/github/tag/tobiasfrust/shibboleth-authenticator.svg
        :target: https://github.com/tobiasfrust/shibboleth-authenticator/releases

.. image:: https://img.shields.io/github/license/tobiasfrust/shibboleth-authenticator.svg
        :target: https://github.com/tobiasfrust/shibboleth-authenticator/blob/master/LICENSE

Shibboleth Authenticator
========================

Module for Invenio that provides authentication via shibboleth.

Installation
============

Requirements
------------

The python3-saml module uses ``xmlsec``, which offers Python bindings for the
XML Security Library. ``xmlsec`` depends on ``libxml2-dev`` and
``libxmlsec1-dev``. These libraries can be installed via the package manager of
your distribution. For Ubuntu use:

.. code-block:: bash

  $ sudo apt install libxml2-dev libxmlsec1-dev

Shibboleth-Authenticator
------------------------

Shibboleth-Authenticator module can be installed via PyPI:

.. code-block:: console

  $ pip install shibboleth-authenticator

Or the latest development branch directly from GitHub:

.. code-block:: console

  $ pip install git+git://github.com/tobiasfrust/shibboleth-authenticator@master

Developer documentation
=======================
See `https://tobiasfrust.github.io/shibboleth-authenticator <https://tobiasfrust.github.io/shibboleth-authenticator/index.html>`_.

