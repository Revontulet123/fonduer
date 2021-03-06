Testing
=======

Code Style
----------

We are using flake8_ to enforce general code style standards. This style check
is part of our Travis-CI tests which is required before merging. You can check
this on your local machine by installing flake8::

    $ pip install flake8
    $ make check 

We use pytest_ to run our tests. Our tests are all located in the ``tests``
directory in the repo, and are meant to be run *after* installing_ Fonduer
locally.::

    $ make test

.. _flake8: https://flake8.pycqa.org/en/latest/ 
.. _pytest: https://docs.pytest.org/en/latest/
.. _installing: install.html
