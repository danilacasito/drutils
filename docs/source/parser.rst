Parser Module
=================
..info:
	This package could have errors if you use in some bad methods

ArgParser function
--------------------

This function gets a string and parses it into a list of command and arguments

Example

>>> from danilacasito_drutils import parse
>>> parse.argparser('"Hello World" "Proto Pe3" "Protf"')
["Hello World", "Proto Pe3", "Protf"]
