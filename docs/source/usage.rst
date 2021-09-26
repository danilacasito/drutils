   Usage
=====

.. note:
   Remember that this package is in Alpha status

.. _installation:

Installation
------------

To use Dr Utilities, first install it using pip:

.. code-block:: console

   (.venv) $ pip install danilacasito-drutils

Parser Module
----------------

The parser module haves at this moment only 1 parser, the Argument Parser, Util for commands, and even discord.py bots that use discord.Client

you can only use ``parser.argparse("'Hello World' 'How are you'")`` that returns ``["Hello World", "How are you"]``

>>> from danilacasito_drutils import parser
>>> parser.argparse("'Hello World' 'How are you'")
['Hello World', 'How are you']

Network Module
---------------

The Network module haves only 1 function,

The function checks if network is available

Example of available network: ``network.checkNetwork()`` that would return ``True``

Not connected on a network: ``network.checkNetwork()`` that would return ``False``