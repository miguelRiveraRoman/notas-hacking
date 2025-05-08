
### Descripción 
Download this disk image and find the flag.Note: if you are using the webshell, download and extract the disk image into `/tmp` not your home directory.

- [Download compressed disk image](https://artifacts.picoctf.net/c/212/disk.flag.img.gz)
### Solución
Descomprimimos el archivo, vemos el numero de particiones y memoria, utilizamos el comando: 

	fls disk.flag.img  -o 411648

Luego revisamos la carpeta de root: 

	fls disk.flag.img  -o 411648 472

Revisamos el archivo txt encriptado 

	icat disk.flag.img -o 411648 1782

Guardamos el archivo :
	
	icat disk.flag.img -o 411648 1782 > flag.txt.enc
	
Vemos el historial de comandos

	icat disk.flag.img -o 411648 1875

Revisando el historial de comandos podemos utilizar ingeniería inversa para ver como ha encriptado el archivo. 

	openssl aes256 -salt -d -in flag.txt.enc -out flag.txt -k unbreakablepassword12

Luego simplemente aplicamos un cat 

Solución: **picoCTF{h4un71ng_p457_0a710765}**
### Notas adicionales


### Referencias 

