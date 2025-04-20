
### Descripción 
We found this [file](https://jupiter.challenges.picoctf.org/static/ab30fcb7d47364b4190a7d3d40edb551/mystery). Recover the flag.
### Solución
Es una imagen dañada, entonces con el heditor hexadecimal modificamos los chunks hasta dejarlos arreglados, para eso nos apoyamos de una herramienta llamada pngcheck


	Hexeditor mystery
	pngcheck -v mystery
	
Solución:**picoCTF{c0rrupt10n_1847995}**
### Notas adicionales
	Despues del encabezado vienen los chunks, se conforman de cuatro partes, la longitud, el tipo de chunk, los datos del chunk y los bytes de redundancia ciclica.

	Los chunks guardan información de la imagen

Pistas:
	1.Try fixing the file header
### Referencias 
https://www.youtube.com/watch?v=7zY4VkiWbBI&list=PLDo9DMLZyP6kTZ8Td37-LdbAx4-yNfHBl&index=21



