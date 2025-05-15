
### Descripción 
Files can always be changed in a secret way. Can you find the flag? [cat.jpg](https://mercury.picoctf.net/static/d1375e383810d8d957c04eef9e345732/cat.jpg)

### Solución
Tenemos que revisar los detalles del archivo con:
	exitfool cat.png 

Luego usamos cyberchef para decodificar la bandera, que estaba en License 

Solución: **picoCTF{the_m3tadata_1s_modified}**
### Notas adicionales
Pistas: 
	1. Look at the details of the file
	2. Make sure to submit the flag as picoCTF{XXXXX}

### Referencias 
https://cyberchef.org/#recipe=From_Base64('A-Za-z0-9%2B/%3D',true,false)
