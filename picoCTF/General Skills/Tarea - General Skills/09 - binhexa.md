
### Descripción 
How well can you perfom basic binary operations?

Start searching for the flag here `nc titan.picoctf.net 61472`
### Solución
Tenemos que hacer diferentes operaciones con numero binarios, desde suma, hasta recorrer bits, de izquierda a derecha, o comparar. 
Al ultimo tenemos que tranformar de binario a hexadecimal 

	Solución: picoCTF{b1tw^3se_0p3eR@tI0n_su33essFuL_d6f8047e}
### Notas adicionales
El operador *&* compara y regresa un 1 donde haya dos 1, el operador *|* nos regresa 1 con que aparezca en un valor, no necesariamente en ambos.

### Referencias 
https://cyberchef.org/#recipe=From_Hex('None'/disabled)From_Hex('None')&input=MDExMDExMTE