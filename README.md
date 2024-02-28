Reto numero 3
=============

A continuacion el reto numero tres, teniendo en cuenta los pseudocodigos y flujo gramas correspondientes (hallar numeros primos y raices cuadradas).

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
         Mientras (2 < n)
         Mientras (n > i, z, q, r)
           Si modulo(n,i) == 0 entonces
             escribir(“n no es primo")
           sino
           Si modulo( n,z ) == 0 entonces
             escribir(“n no es primo”)
           sino
           Si modulo(n,q) == 0 entonces
             escribir(“n no es primo”)
           sino
           Si modulo(n,r) == 0 entonces
             escribir(“n no es primo”)
         Fin mientras
        fin
       
Diagrama  de flujo numeros primos
-------------

<a href='https://postimg.cc/94qg8MxB' target='_blank'><img src='https://i.postimg.cc/yNfqN3c2/Diagrama-numeros-primos.png' border='0' alt='Diagrama-numeros-primos'/></a>   

Pseudocodigo para hallar raices cuadradas
-------------

    [variables]
	  n : entero positivo
	  i : entero
	  z : entero
	  q : entero
	  r : entero
	  inicio
           i := 2
           z := 3
           q := 5
           r := 7
	     Mientras (2 <= n) 
	       Si (descomposicion de n entre i, z, q o r da lugar a una cantidad par de numeros) entonces
	          Formar grupos con los numeros primos usados en la descomposicion teniendo en cada grupo los mismos numeros
	       Si (productos de cada grupo de numero son equivalemtes) entonces
	          escribir(n tiene raiz cuadrada)
	       sino
		 escribir(n no tiene raíz cuadrada)
       Fin mientras
     fin
