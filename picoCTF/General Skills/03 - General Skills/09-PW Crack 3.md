
### Descripción 
Can you crack the password to get the flag?Download the password checker [here](https://artifacts.picoctf.net/c/17/level3.py) and you'll need the encrypted [flag](https://artifacts.picoctf.net/c/17/level3.flag.txt.enc) and the [hash](https://artifacts.picoctf.net/c/17/level3.hash.bin) in the same directory too.There are 7 potential passwords with 1 being correct. You can find these by examining the password checker script.
### Solución
Por pasos
	#1 Obtenemos el script con *wget*
	#2 Le cedemos permisos con *chmod +x* 
	#3 Ya sea con *cat* o con *nano* revisamos el código para 
	#4 Revisamos el hash
	#5 Creamos un script para comparar el hash con el hash de la contraseña 
	![[Pasted image 20250223114400.png]]
### Notas adicionales
	*To view the level3.hash.bin file in the webshell, do: `$ bvi level3.hash.bin`

### Referencias 
https://cyberchef.org/

https://colab.research.google.com/drive/1KBBPLWUbEd_h476OO2VpnPg7wKgnrj8r#scrollTo=owl2yMeS4hbh
