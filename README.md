Reto numero 3
=============

A continuacion los algoritmos correspondientes, junto con sus diagramas de flujo y pseudocodigos

Pseudocodigo numeros primos
-------------

    [variables]
     n : entero
     i : entero
     z : entero
     q : entero
     r : entero
     inicio
	i := 2
	z := 3
        q := 5
        r := 7
        n ≠ i, z, q, r
        Mientras ( 2 < n )
        Mientras ( n > i, z, q, r )
          Si modulo( n,i ) == 0 entonces
	    escribir( “n no es primo’’ )
          sino
	  Si modulo( n,z ) == 0 entonces
	    escribir( “n no es primo” )
          sino
          Si modulo( n,q ) == 0 entonces
	    escribir( “n no es primo” )
	  sino
          Si modulo( n,r ) == 0 entonces
	    escribir( “n no es primo” )
	Fin mientras
       fin
       
Diagrama  de flujo numeros primos
-------------
