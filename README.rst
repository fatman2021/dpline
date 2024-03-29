.. image:: https://img.shields.io/github/release/dslackw/dpline.svg
    :target: https://github.com/dslackw/dpline/releases
.. image:: https://travis-ci.org/dslackw/dpline.svg?branch=master
    :target: https://travis-ci.org/dslackw/dpline
.. image:: https://landscape.io/github/dslackw/dpline/master/landscape.png
    :target: https://landscape.io/github/dslackw/dpline/master
.. image:: https://img.shields.io/codacy/242f2dae7daa46b09121df3374bc5dd2.svg
    :target: https://www.codacy.com/public/dzlatanidis/dpline/dashboard
.. image:: https://img.shields.io/pypi/dm/dpline.svg
    :target: https://pypi.python.org/pypi/dpline
.. image:: https://img.shields.io/badge/license-GPLv3-blue.svg
    :target: https://github.com/dslackw/dpline
.. image:: https://img.shields.io/github/stars/dslackw/dpline.svg
    :target: https://github.com/dslackw/dpline
.. image:: https://img.shields.io/github/forks/dslackw/dpline.svg
    :target: https://github.com/dslackw/dpline
.. image:: https://img.shields.io/github/issues/dslackw/dpline.svg
    :target: https://github.com/dslackw/dpline/issues
 

.. code-block:: bash

         _       _ _            
      __| |____ | (_)____   ___ 
     / _  |  _ \| | |  _ \ / _ \
    | (_| | |_) | | | | | |  __/
     \____|  __/|_|_|_| |_|\___|
          |_|                   
     ___________________________ 
     ___________________________

About
-----

CLI tool to remove duplicate lines from text file.


Installation
------------

.. code-block:: bash

    $ tar xvf dpline-<version>.tar.gz
    $ cd dpline-<version>
    $ python setup.py install


    or via pip:

    $ pip install dpline --upgrade

    uninstall:

    $ pip uninstall dpline


Command Line Tool Usage
-----------------------

.. code-block:: bash

    Usage: dpline [OPTION] <file> [--ignore-blank, [--case-ins]]

    dpline is tool to remove duplicate lines from file

    Optional arguments:
      -h, --help          Print this help message and exit
      -v, --version       Print program version and exit
      -d, --display       Display removed lines
      -p, --preview       Preview duplicate lines before removal
      --ignore-blank      Ignore blank lines from remove
      --case-ins          Matching upper- and lowercase letters
