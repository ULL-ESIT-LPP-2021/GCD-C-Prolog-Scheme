# README.md

Para comprobar el funcionamiento del máximo común divisor escrito en Prolog
hay que usar el intérprete.

```
$ swipl -s gcd.pl
Welcome to SWI-Prolog (threaded, 64 bits, version 7.6.4)
SWI-Prolog comes with ABSOLUTELY NO WARRANTY. This is free software.
Please run ?- license. for legal details.

For online help and background, visit http://www.swi-prolog.org
For built-in help, use ?- help(Topic). or ?- apropos(Word).

| ?- gcd(5,7,1).

true ? 

yes
| ?- gcd(5,7,2).

no
| ?- halt.

```




El "gprolog" no funciona bien.

```
$ gprolog
GNU Prolog 1.3.0
By Daniel Diaz
Copyright (C) 1999-2007 Daniel Diaz
| ?- consult('gcd.pl').
compiling /home/ubuntu/workspace/tema1/Prolog/gcd.pl for byte code...
/home/ubuntu/workspace/tema1/Prolog/gcd.pl compiled, 2 lines read - 1286 bytes written, 10 ms

yes
| ?- gcd(5,7,1).

true ? 

yes
| ?- gcd(5,7,2).

no
| ?- halt.

```

El manual de GNU Prolog lo podemos encontrar en:

http://www.gprolog.org/manual/gprolog.html#The-GNU-Prolog-compiler

Sin embargo no funciona bien en la actualización.

Se ha usado SWI-Prolog y su manual está en:

https://wwu-pi.github.io/tutorials/lectures/lsp/010_install_swi_prolog.html

Un libro de Prolog:

https://books.google.es/books?id=S-u9BAAAQBAJ&pg=PA2&lpg=PA2&dq=output+prolog+hello+world&source=bl&ots=gr9w1XEcX6&sig=jvl_ULVFUVtVTWPT9e2xJvi8mJk&hl=es&sa=X&ved=0CEIQ6AEwBGoVChMI16Hg2pKIyAIVxH0aCh0MsQcI#v=onepage&q=output%20prolog%20hello%20world&f=false

Título	Logic Programming with Prolog
SpringerLink : Bücher
Autor	Max Bramer
Edición	ilustrada
Editor	Springer Science & Business Media, 2013
ISBN	1447154878, 9781447154877
N.º de páginas	266 páginas
