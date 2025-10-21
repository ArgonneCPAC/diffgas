diffgas
============

Installation
------------
To install diffgas into your environment from the source code::

    $ cd /path/to/root/diffgas
    $ pip install .

Testing
-------
To run the suite of unit tests::

    $ cd /path/to/root/diffgas
    $ pytest

To build html of test coverage::

    $ pytest -v --cov --cov-report html
    $ open htmlcov/index.html

