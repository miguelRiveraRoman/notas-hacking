
### Descripción 
Can you crack the password to get the flag?Download the password checker [here](https://artifacts.picoctf.net/c/15/level2.py) and you'll need the encrypted [flag](https://artifacts.picoctf.net/c/15/level2.flag.txt.enc) in the same directory too
### Solución
Por pasos
	#1 Obtenemos el script con *wget*
	#2 Le cedemos permisos con *chmod +x* 
	#3 Ya sea con *cat* o con *nano* revisamos el código para ver la respuesta
	#4 Convertimos de hexadecimal a unicode
	![[Pasted image 20250222142033.png]]
	#5 ejecutamos con *python*  e ingresamos la contraseña
	
	Solución: picoCTF{tr45h_51ng1ng_502ec42e}
### Notas adicionales
Se puede usar cyberchef para convertir de hexadecimal a unicode

### Referencias 
https://cyberchef.org/

https://colab.research.google.com/drive/1KBBPLWUbEd_h476OO2VpnPg7wKgnrj8r#scrollTo=53hgYDzvS2q1
