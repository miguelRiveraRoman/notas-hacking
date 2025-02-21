
## Reto

### Descripción 
Sometimes you need to handle process data outside of a file. Can you find a way to keep the output from this program and search for the flag? Connect to `jupiter.challenges.picoctf.org 4427`.
### Solución
	*nc jupiter.challenges.picoctf.org 4427 | grep pico

La navaja suiza de las redes "netcat" nos sirve para conectarnos al puerto
. Luego filtramos palabras con grep filtramos pico


### Notas adicionales
	*grep: global regular expression print
	*c no jala en windows
	*dsds
	*nc: netcat

### Referencias 
https://cyberchef.org/

