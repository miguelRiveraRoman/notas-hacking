
### Descripción 
Use `srch_strings` from the sleuthkit and some terminal-fu to find a flag in this disk image: [dds1-alpine.flag.img.gz](https://mercury.picoctf.net/static/920731987787c93839776ce457d5ecd6/dds1-alpine.flag.img.gz)
### Solución
Tenemos un archivo comprimido, primero lo descomprimimos, vemos que es un archivo con extensión de imagen de disco, entonces aplicamos el comando:

	srch_strings dds1-alpine.flag.img | grep pico

Y obtenemos la bandera.

Solución: **picoCTF{f0r3ns1c4t0r_n30phyt3_564ff1a0}**
### Notas adicionales

Pistas:
	1. Have you ever used `file` to determine what a file was?
	2. Relevant terminal-fu in picoGym: https://play.picoctf.org/practice/challenge/85
	3. Mastering this terminal-fu would enable you to find the flag in a single command: https://play.picoctf.org/practice/challenge/48
	4. Using your own computer, you could use qemu to boot from this disk!

### Referencias 

