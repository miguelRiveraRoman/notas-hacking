
### Descripción 
I stopped using YellowPages and moved onto WhitePages... but [the page they gave me](https://jupiter.challenges.picoctf.org/static/74274b96fe966126a1953c80762af80d/whitepages.txt) is all blank!
### Solución
Nos dan un archivo en blanco, sin palabras pero con 2900 y cacho caracteres, es unicode con un acodificacion utf-8

Mostramos en hexadecimal los valores con el comando 

	xxd nombreArchivo | head

Abrimos el archivo en formato binario, para eso instalamos una libreria de python llamada **pwntools**, creamos un script para leer el archivo y pasarlo a binario y lo ejecutamos 

	from pwn import *
	
	file = open('whitepages.txt','rb')
	data = bytearray(file.read())
	
	data = data.replace(b'\xe2\x80\x83',b'0')
	data = data.replace(b'\x20',b'1')
	
	
	data = data.decode('ascii')
	
	data = unbits(data)
	
	print(data)

Solución:**picoCTF{not_all_spaces_are_created_equal_c54f27cd05c2189f8147cc6f5deb2e56}**
### Notas adicionales
	UNICODE es un estandar para una codificacion y manejo consistente de texto expresado. 
	UTF es un esquema de codificacion de caracteres de longitud varibale y ocupa de 1 a 4 bytes
### Referencias 
https://www.youtube.com/watch?v=427HDV7tzow&list=PLDo9DMLZyP6kTZ8Td37-LdbAx4-yNfHBl&index=20
