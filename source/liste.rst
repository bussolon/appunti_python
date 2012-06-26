.. Liste, dizionari, insiemi


Liste, dizionari, insiemi
==========================

Dizionari
-------------

Esempio di iniziazione di un dizionario::

	dizionario = {}
	help(dizionario)
	dizionario['uno']= 1
	dizionario[2]= 'due'
	dizionario
	#[Out]# {2: 'due', 'uno': 1}
	dizionario.keys()
	#[Out]# [2, 'uno']
	dizionario.values()
	#[Out]# ['due', 1]
	dizionario.has_key('uno')
	#[Out]# True

Cancella un elemento dal dizionario::

	del dizionario[2]

Meglio::

	if dizionario.has_key(2):
		del dizionario[2]

