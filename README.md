                             _       _ _            
                          __| |_ __ | (_)_ __   ___ 
                         / _` | '_ \| | | '_ \ / _ \
                        | (_| | |_) | | | | | |  __/
                         \__,_| .__/|_|_|_| |_|\___|
                              |_|                   


About
-----

Simple tool to remove duplicate lines from text file.


Installation
------------

    $ tar xvf dpline-<version>.tar.gz
    $ cd dpline-<version>
    $ python setup.py install


    or via pip:

    $ pip install dpline --upgrade

    uninstall:

    $ pip uninstall dpline


Command Line Tool Usage
-----------------------

    Usage: dpline [OPTION] <file> [--ignore-blank, [--case-ins]]

    dpline is tool to remove duplicate lines from file

    Optional arguments:
      -h, --help          Print this help message and exit
      -v, --version       Print program version and exit
      -d, --display       Display removed lines
      -p, --preview       Preview duplicate lines before removal
      --ignore-blank      Ignore blank lines from remove
      --case-ins          Matching upper- and lowercase letters


Copyleft 
---------

- Copyleft © Dimitris Zlatanidis

