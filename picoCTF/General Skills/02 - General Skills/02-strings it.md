
### Descripción 
Can you find the flag in [file](https://jupiter.challenges.picoctf.org/static/94d00153b0057d37da225ee79a846c62/strings) without running it?
### Solución
Lo dividimos por pasos
	#1 Con *wget* y la dirección del archivo lo descargamos
	#2 Utilizamos *Strings* para extraer las cadenas de una archivo binario
	#3 Filtramos con *grep* la palabra pico
	
### Notas adicionales
	#2 Con *file* vemos que tipo de archivo es
	#3 Con *ls -la* vemos los permisos del archivo
	#3 Con chmod +x "NombreArchivo" le cedemos permisos de ejecución

### Referencias 

