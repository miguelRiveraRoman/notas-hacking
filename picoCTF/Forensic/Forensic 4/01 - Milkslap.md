
### Descripción 
[🥛](http://mercury.picoctf.net:48319/)
### Solución
Nos lleva a un video, inspeccionamos el código fuente y vemos que en la pagina de estilos hay una imagen cargada, copiamos el nombre de la página y lo pegamos al final de la url,  nos lleva a una imagen y la descargamos, utilizamos el comando:

	zsteg -a concat_v.png
Nos marca un error en la pila, la aumentamos con el comando:

	export RUBY_THREAD_VM_STACK_SIZE=500000000

Volvemos a utilizar el comando anterior y nos da la pila 
Solución: **picoCTF{imag3_m4n1pul4t10n_sl4p5}**
### Notas adicionales

El error ocurre cuando rebasamos el stack y la imagen es muy grande.
Pistas: 
	Look at the problem category
### Referencias 

