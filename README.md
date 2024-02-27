# Segundo-reto: Pseudocodigos

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
      Escribir( “n no es primo’’ )
    Si no
      Si modulo( n,z ) == 0 entonces
      Escribir( “n no es primo” )
    Si no
      Si modulo( n,q ) == 0 entonces
      Escribir( “n no es primo” )
    Si no
      Si modulo( n,r ) == 0 entonces
      Escribir( “n no es primo” )
 Fin mientras
fin
