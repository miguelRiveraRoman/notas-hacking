
### Descripción 

To get truly 1337, you must understand different data encodings, such as hexadecimal or binary. Can you get the flag from this program to prove you are on the way to becoming 1337? Connect with `nc jupiter.challenges.picoctf.org 29221`.

### Solución
Los dividimos por pasos
	#1 Usamos netcat  para conectarnos al puerto
	![[Pasted image 20250220153651.png]]
	#2 Convertimos de binario a entero, luego de entero a hexadecimal y luego de hexadecimal a carácter
	![[Pasted image 20250220153736.png]]
	#3 Convertimos de octal a entero y el entero a un carácter
	![[Pasted image 20250220153753.png]]
	#4 Tomamos la cadena de dígitos hexadecimales y devolvemos los bytes correspondientes
	![[Pasted image 20250220153805.png]]
**Respuesta:** picoCTF{learning_about_converting_values_00a975ff}
### Notas adicionales
	*Identificamos los valores octales porque no hay ningún 8 en ellos

	*Utilizamos python pero se puede utilizar cyberchef también
### Referencias 
https://cyberchef.org/

https://colab.research.google.com/drive/1KBBPLWUbEd_h476OO2VpnPg7wKgnrj8r#scrollTo=SylLYHQoLfBS

