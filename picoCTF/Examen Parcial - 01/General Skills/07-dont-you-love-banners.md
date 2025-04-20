
### Descripción 
Can you abuse the banner?The server has been leaking some crucial information on `tethys.picoctf.net 65498`. Use the leaked information to get to the server.To connect to the running application use `nc tethys.picoctf.net 50368`. From the above information abuse the machine and find the flag in the /root directory.

### Solución
Tenemos que conectarnos a dos puertos, el primero nos proporciona la contraseña del segundo, en el segundo se realizan una preguntas. 

Estando en el segundo puerto, verificamos los archivos, vemos un banner y creamos un acceso directo hacía él, nos desconectamos del puerto y al volver a entrar nos saldrá la bandera.

Solución: **picoCTF{b4nn3r_gr4bb1n9_su((3sfu11y_a0e119d4}**
### Notas adicionales
	Enlace simbolico:  es un archivo que apunta a otro archivo o carpeta, parecido a un acceso directo

### Referencias 

