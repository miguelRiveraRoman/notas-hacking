
### Descripción 
Do you know how to move between directories and read files in the shell? Start the container, `ssh` to it, and then `ls` once connected to begin. Login via `ssh` as `ctf-player` with the password, `a13b7f9d`

Additional details will be available after launching your challenge instance.
### Solución
Vamos a tener que estarnos moviendo entre carpetas 
	#1 Nos conectamos al puerto con *ssh* 
	#2 Revisamos el contenido de los archivos con *cat*
	#3 Nos movemos entre carpetas hasta encontrar toda la bandera
**Solucion: 
picoCTF{xxsh_0ut_0f_\/\/4t3r_71be5264}

### Notas adicionales
	*El parametro "/" en cd nos sirve para ir al directorio raíz
	*El parametro "~" nos lleva a la carpeta home
	*Con "pwd" vemos en que carpeta nos encontramos

### Referencias 

