CircuitPython Kernel
====================

.. image:: https://cdn-learn.adafruit.com/guides/images/000/002/051/medium310/Untitled-3.png?1528919538


.. image:: https://readthedocs.org/projects/circuitpython-kernel/badge/?version=latest
    :target: https://circuitpython-kernel.readthedocs.io/en/latest/?badge=latest
    :alt: Documentation


.. image:: https://img.shields.io/discord/327254708534116352.svg
    :target: https://adafru.it/discord
    :alt: Discord


.. image:: https://img.shields.io/travis/adafruit/circuitpython_kernel.svg
    :target: https://travis-ci.org/adafruit/circuitpython_kernel
    :alt: Build Status


The CircuitPython Kernel is a `Jupyter Kernel <https://jupyter.org/>`_ designed to interact with Adafruit boards
running `CircuitPython <https://github.com/adafruit/circuitpython>`_ from within a Jupyter Notebook.


Status
------

This project's status is experimental. It has been tested with CircuitPython 3.x in (SAMD) boards and
Feather HUZZAH (ESP8266).
With CircuitPython 6.x in Raspberry Pi Pico

It may break, and if it does, please file an
`issue on this repository <https://circuitpython-kernel.readthedocs.io/en/latest/contributing.html>`__.


Compatible Boards
-----------------

Designed for CircuitPython (SAMD21 and SAMD51)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

-  `Adafruit CircuitPlayground Express <https://www.adafruit.com/product/3333>`__
-  `Adafruit Feather M0 Express <https://www.adafruit.com/product/3403>`__
-  `Adafruit Metro M0 Express <https://www.adafruit.com/product/3505>`_
-  `Adafruit Metro M4 Express <https://www.adafruit.com/product/3382>`_
-  `Adafruit Trinket M0 <https://www.adafruit.com/product/3500>`__
-  `Adafruit Gemma M0 <https://www.adafruit.com/product/3501>`__
-  `Adafruit Trinket M0 <https://www.adafruit.com/product/3500>`__
-  `Adafruit ItsyBitsy M0 Express <https://www.adafruit.com/product/3727>`_
-  `Adafruit ItsyBitsy M4 Express <https://www.adafruit.com/product/3800>`__



Other Adafruit Boards
~~~~~~~~~~~~~~~~~~~~~

-  `Adafruit Feather HUZZAH ESP8266 <https://www.adafruit.com/products/2821>`__

Other Boards
~~~~~~~~~~~~~~~~~~~~~
-  `Raspberry Pi Pico <https://www.adafruit.com/products/4864>`__
-  `PJRC Teensy 4.1 <https://www.adafruit.com/products/4622> __

Download
--------

Official .zip files are available through the
`latest GitHub releases <https://github.com/adafruit/circuitpython_kernel/releases>`__.


Install
-------

Jupyter::

    pip3 install --upgrade pip
    pip3 install jupyter

Optional::

    pip3 install jupyterlab

CircuitPython kernel::

    cd circuitpython_kernel/
    python3 setup.py install; 
    
    new install:
    --------
    
    pip install git+https://github.com/K-Class/circuitpython_jupyter_kernel.git
    python -m circuitpython_kernel.install

Then run with one of::

    jupyter notebook
    jupyter lab

and choose the CircuitPython kernel.

Documentation
-------------

This kernel is fully documented on the Adafruit Learning System Guide:
`CircuitPython with Jupyter Notebooks <https://learn.adafruit.com/circuitpython-with-jupyter-notebooks/overview?preview_token=v7Eay4tLlhN50xPJiQFSow>`__.

A line containing exactly the word::

    %softreset

will reset the board and release all resources.

There's also documentation for this kernel listed on
`ReadTheDocs <https://circuitpython-kernel.readthedocs.io/en/latest/>`__.
