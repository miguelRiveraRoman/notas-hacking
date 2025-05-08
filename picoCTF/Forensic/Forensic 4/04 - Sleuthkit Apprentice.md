
### Descripción 
Download this disk image and find the flag.Note: if you are using the webshell, download and extract the disk image into `/tmp` not your home directory.

- [Download compressed disk image](https://artifacts.picoctf.net/c/138/disk.flag.img.gz)
### Solución
Descomprimimos el archivo, vemos el numero de particiones y memoria, utilizamos el comando: 

	fls disk.flag.img -o 360448 -r | grep flag

para ver los archivos y directorios en la imagen de disco y buscamos con grep. Encontramos un archivo que indica tener la bandera y utilizamos el comando 

	icat disk.flag.img -o 360448 2371

Con icat vemos el contenido del archivo txt, indicando la dirección de memoria y la direccion del archivo 

Solución: **picoCTF{by73_5urf3r_2f22df38}**
### Notas adicionales


### Referencias 

