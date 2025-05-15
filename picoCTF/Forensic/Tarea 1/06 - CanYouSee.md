
### Descripción 
How about some hide and seek?Download this file [here](https://artifacts.picoctf.net/c_titan/131/unknown.zip).
### Solución
Descomprimimos el archivo, luego utilizamos el comando:
	****exiftool***
luego  extraemos los datos que parecen estar en base 64 , usamos el comando:
	**echo "cGljb0NURntNRTc0RDQ3QV9ISUREM05fZDhjMzgxZmR9Cg="| base64 -d*
	
Solución: **picoCTF{ME74D47A_HIDD3N_d8c381fd}**
### Notas adicionales
`ExifTool` es una herramienta de línea de comandos que ==permite leer, escribir y modificar metadatos de diversos formatos de archivos, incluyendo imágenes, audio, vídeo y PDF==. Básicamente, `ExifTool` te permite acceder a la información "oculta" dentro de estos archivos, como la fecha de creación, las coordenadas GPS, el modelo de cámara, etc.

`echo` simplemente toma una cadena de caracteres como entrada y la muestra en la terminal.

Pistas: 
	1. How can you view the information about the picture?
	2. If something isn't in the expected form, maybe it deserves attention?
### Referencias 

