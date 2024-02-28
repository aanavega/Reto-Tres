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

[![](https://mermaid.ink/img/pako:eNpdktFO4kAUhl_l5FxpMiDtFCuNuFEBJSw1u3pFy8WkHddJ7AwM07gUeADfwmfzSXZKqStt2sz55_z9_kl7NpiolGOAz6_qLXlh2sDTIJZgr-uTsRSJUKexvIZW6woGUZhnXCuQ81gO9ls30U-xMgxSDi5cgoS1fa5AkIIsiZ5XoJvSOoskfL5_NFq3kei7BIo-JbDsdwnovg91z751t_nNVyLNVZkgzwTwFST2CD92lefOerah2sIwGkvDpWEaEiWttThQhtZxf0wpmpT7mjL-T5Fny_m37qPYjg6RcNAwikJVohZaZOpgHtvm5Dhu2Yyb1HHT73H1J5l84Ss9tTo8JuomMayJD9Hw-Dxhg_Zg9a-qHJXlyUjI00rPrL6tyliWKxK0vztjIrXzsSl3YjQvPOMxBrZM-TPLX02MsdxZK8uNelzLBAOjc04wX6TM8IFgfzTL6k2eCqP0tBq5_eQRXDA5U-rLYiUGG_yLAfWctuNcdGnH9alH_S7BNQYt16PtnuPYu-N0fM91dwSLPcBp-5S6fo_Sc7dHO-fU2_0DlgvaUQ?type=png)](https://mermaid.live/edit#pako:eNpdktFO4kAUhl_l5FxpMiDtFCuNuFEBJSw1u3pFy8WkHddJ7AwM07gUeADfwmfzSXZKqStt2sz55_z9_kl7NpiolGOAz6_qLXlh2sDTIJZgr-uTsRSJUKexvIZW6woGUZhnXCuQ81gO9ls30U-xMgxSDi5cgoS1fa5AkIIsiZ5XoJvSOoskfL5_NFq3kei7BIo-JbDsdwnovg91z751t_nNVyLNVZkgzwTwFST2CD92lefOerah2sIwGkvDpWEaEiWttThQhtZxf0wpmpT7mjL-T5Fny_m37qPYjg6RcNAwikJVohZaZOpgHtvm5Dhu2Yyb1HHT73H1J5l84Ss9tTo8JuomMayJD9Hw-Dxhg_Zg9a-qHJXlyUjI00rPrL6tyliWKxK0vztjIrXzsSl3YjQvPOMxBrZM-TPLX02MsdxZK8uNelzLBAOjc04wX6TM8IFgfzTL6k2eCqP0tBq5_eQRXDA5U-rLYiUGG_yLAfWctuNcdGnH9alH_S7BNQYt16PtnuPYu-N0fM91dwSLPcBp-5S6fo_Sc7dHO-fU2_0DlgvaUQ) 

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

Diagrama  de flujo raices cuadradas
-------------

[![](https://mermaid.ink/img/pako:eNqNUsFO4zAQ_ZWRTyClqDRJSyMVBFSlK0EkBKcmHEa2KZYaOzj27tK0_76TuOz2sgJf7Hl-7808yy3jRkiWsdeN-cXf0Dp4npcaaF2f_NCKK3Na6msYDC5hXuS-ktaAfin1vIduinvVOAQhQcPlDEYvQXvT3a4KNRtFsJ3FEbzP0gjsbHK4vy3msuGmqk3TtdDBQGpnJSiSkAAMWPikk9td-z2JwKDZ-DVaQPAagaN2SqCAmqBO1-dorvaBekf2uye1g0WxMLYiztp66gOc2mxoP_ADu7aqIsw3KGiTxOjyH48WeE5qJbUwHYWjwGDa-1Wqqf7ZHkIuaIple094bY3w3NGJZj2SNjSOfPfqJ24otzzME56gUVcAx3lys4O8yA04mkKCRbUF7lFY8hMYei4PwR-L5_-THon0cLJQ-rQv864MfZZf9SGDwFwR8zYcA8QiRtkrVIL-XtshJXNvspIly-go5Cv6jStZqfdERe_M04fmLHPWy4j5WqCTc4Vri9UnKIVyxj6E79z_6ojVqFfG_KVQybKW_WbZIDmLk_F4mE5oJcNkcpFG7IPw82E8Oku7-jwdj9J9xLa9QUxgfDEdj5JpHMfTZJLs_wCaTgVM?type=png)](http://https://mermaid.ink/img/pako:eNqNUsFO4zAQ_ZWRTyClqDRJSyMVBFSlK0EkBKcmHEa2KZYaOzj27tK0_76TuOz2sgJf7Hl-7808yy3jRkiWsdeN-cXf0Dp4npcaaF2f_NCKK3Na6msYDC5hXuS-ktaAfin1vIduinvVOAQhQcPlDEYvQXvT3a4KNRtFsJ3FEbzP0gjsbHK4vy3msuGmqk3TtdDBQGpnJSiSkAAMWPikk9td-z2JwKDZ-DVaQPAagaN2SqCAmqBO1-dorvaBekf2uye1g0WxMLYiztp66gOc2mxoP_ADu7aqIsw3KGiTxOjyH48WeE5qJbUwHYWjwGDa-1Wqqf7ZHkIuaIple094bY3w3NGJZj2SNjSOfPfqJ24otzzME56gUVcAx3lys4O8yA04mkKCRbUF7lFY8hMYei4PwR-L5_-THon0cLJQ-rQv864MfZZf9SGDwFwR8zYcA8QiRtkrVIL-XtshJXNvspIly-go5Cv6jStZqfdERe_M04fmLHPWy4j5WqCTc4Vri9UnKIVyxj6E79z_6ojVqFfG_KVQybKW_WbZIDmLk_F4mE5oJcNkcpFG7IPw82E8Oku7-jwdj9J9xLa9QUxgfDEdj5JpHMfTZJLs_wCaTgVM?type=png) 

