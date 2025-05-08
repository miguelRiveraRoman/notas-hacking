
### Descripción 
Download this disk image, find the key and log into the remote machine.Note: if you are using the webshell, download and extract the disk image into `/tmp` not your home directory.

- [Download disk image](https://artifacts.picoctf.net/c/71/disk.img.gz)
- Remote machine: `ssh -i key_file -p 49444 ctf-player@saturn.picoctf.net`
### Solución

Descomprimimos el archivo, vemos el numero de particiones y memoria, utilizamos el comando: 

	fls disk.img -o 206848

Luego revisamos la carpeta de root: 

	fls disk.img -o 206848 470

Revisamos la llave ssh 

	fls disk.img -o 206848 3916

Guardamos el archivo :
	
	icat disk.img -o 206848 2345 > key_file
	
Modificamos los permisos 

	chmod 600 key_file

Luego nos conectamos al servidor y simplemente realizamos un cat al unico archivo que existe, luego simplemente aplicamos un cat 

Solución: **picoCTF{k3y_5l3u7h_af277f77}**
### Notas adicionales

Pistas: 
	Look at the problem category
### Referencias 

