###############################################################################
                             TASK TRACKER SERVICE
###############################################################################

This project is done in addition to the `Python training course`_.
It demonstrates the abilities of the `Django`_ web framework.

.. _Django: https://djangoproject.com/
.. _Python training course: https://github.com/shorodilov/python-course/

Getting started
===============

#. Download the code repository to your local machine
#. Install all dependencies required by this project
#. Set up environment variables required by this project``
#. Run the project

The dependencies are listed in formats suitable for `pip`_ and `poetry`_
package managers.

.. _pip: https://pip.pypa.io/
.. _poetry: https://python-poetry.org/

Installing dependencies
-----------------------

To install the dependencies using pip do:

.. code-block::

    pip install -r requirements.txt

To do the same via poetry do:

.. code-block::

    poetry install

Setting up environment
----------------------

To set an environment variable use commands:

.. code-block::

    export VARIABLE=value  # Linux and MacOS
    set VARIABLE=value     # Windows

+-----------------------+-----------------------------------------------------+
| Variable name         | Description                                         |
+=======================+=====================================================+
| ``DJANGO_SECRET_KEY`` | The secret key is required by Django security       |
|                       | middleware. For the security reasons this can not   |
|                       | be shared across the internet, and should be setup  |
|                       | for each project individual instance separately.    |
|                       | Here is a good service to get it:                   |
|                       | https://djecrety.ir/                                |
+-----------------------+-----------------------------------------------------+

Project structure
=================

.. todo: to be described
