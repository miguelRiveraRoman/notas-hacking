
### Descripción 
Can you look at the data in this binary: [static](https://mercury.picoctf.net/static/ec4dbd8898ade34e1d60d5b70c1b8c8c/static)? This [BASH script](https://mercury.picoctf.net/static/ec4dbd8898ade34e1d60d5b70c1b8c8c/ltdis.sh) might help!
### Solución
Los dividimos por pasos
	#1 obtenemos los archivos con *wget*
	#2 cedemos permisos con *chmod +x*
	#3 Ejecutamos el script con *bash* 
	#4 obtenemos la bandera con un *cat* para ver el contenido y un *grep* para filtrar

### Notas adicionales
	*Todos los archivos que terminan en sh son archivos de bash o ejecutables en shell

	*nano nos sirve para abrir algo con el editor
	
	*objdump desensambla el contenido de un binario

	*Con cat vemos el contenido de un archivo 
### Referencias 


