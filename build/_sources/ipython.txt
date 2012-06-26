.. alcuni trucchetti con ipython



Uso di Ipython
===============


Funzioni magiche
------------------

::

	lsmagic
	magic


Salvare un pezzo di sessione
--------------------------------

::

	logstart dizionario -o
	magic
	logstart -o dizionario


Pythonpath e import
-----------------------

Fonte: <http://www.johnny-lin.com/cdat_tips/tips_pylang/path.html> ::

	import sys
	sys.path.append("/home/me/mypy")
