Contributing
============

Getting the Source
~~~~~~~~~~~~~~~~~~

You will first want to clone the source repository locally with ``git``:

.. code-block:: console

    $ git clone git@github.com:justinmayer/django-elevate.git


Setting Up the Environment
~~~~~~~~~~~~~~~~~~~~~~~~~~

I would recommend using `virtualenv <https://pypi.python.org/pypi/virtualenv>`_ to set up a dev
environment. After creating an environment, install all development dependencies with:

.. code-block:: console

    $ pip install -r dev-requirements.txt

Running Tests
~~~~~~~~~~~~~

Tests are run using `pytest <https://pypi.python.org/pypi/pytest>`_ and can be found inside
``tests/*``.

Tests can simply be run using:

.. code-block:: console

    $ pytest

This will discover and run the test suite using your default Python interpreter. To run tests
for all supported platforms, we use `tox <https://pypi.python.org/pypi/tox>`_.

.. code-block:: console

    $ tox

Submitting Patches
~~~~~~~~~~~~~~~~~~

Patches are accepted via `Pull Requests <https://github.com/justinmayer/django-elevate/pulls>`_ on
GitHub.

.. note::

    If you are submitting a security patch, please see our :doc:`/security/index` page for special
    instructions.

Tests
-----

All new code and changed code must come with **100%** test coverage to be considered for acceptance.
