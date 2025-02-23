
### Descripción 
Run the Python script and convert the given number from decimal to binary to get the flag.[Download Python script](https://artifacts.picoctf.net/c/22/convertme.py)
### Solución
Por pasos
	#1 con *wget* obtenemos el script 
	#2 con *chmod +x* le cedemos permisos
	#3 con *python* lo ejecutamos
	# Transformamos de entero a binario

![[Pasted image 20250222133247.png]]

	Solución: 
	picoCTF{4ll_y0ur_b4535_762f748e}
### Notas adicionales
se aumenta el valor a la izquierda, partiendo de la derecha como 1, representado cada 0 o 1 la multiplicación por 2 del digito anterior
8 4 2 1
0 0 0 0


### Referencias 
https://colab.research.google.com/drive/1KBBPLWUbEd_h476OO2VpnPg7wKgnrj8r#scrollTo=FwS3RzmUI3pg

