
### Descripción 
Download the disk image and use `mmls` on it to find the size of the Linux partition. Connect to the remote checker service to check your answer and get the flag.Note: if you are using the webshell, download and extract the disk image into `/tmp` not your home directory.[Download disk image](https://artifacts.picoctf.net/c/164/disk.img.gz)

Access checker program: `nc saturn.picoctf.net 58642`
### Solución
Descomprimimos el archivo, vemos que es una imagen de disco, utilizamos el comando *mmls* para ver el tamaño y el numero de particiones del disco, luego nos conectamos con nc y nos pide el tamaño del disco, lo colocamos y sale la bandera.

Solución: **picoCTF{mm15_f7w!}**
### Notas adicionales


### Referencias 

