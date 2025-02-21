
### Descripción 
Can you invoke help flags for a tool or binary? [This program](https://mercury.picoctf.net/static/a14be2648c73e3cda5fc8490a2f476af/warm) has extraordinarily helpful information...
### Solución
Lo dividimos por pasos
	#1 Descargamos el archivo con *wget*
	#2 le damos permisos con *chmodc +x*
	#3 Lo ejecutamos y le pasamos un parametro para ver que hace *./warm -h*
### Notas adicionales
No todos los comandos tienen parámetros extra

### Referencias 
linux

