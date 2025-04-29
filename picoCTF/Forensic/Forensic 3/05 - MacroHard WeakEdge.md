
### Descripción 
I've hidden a flag in this file. Can you find it? [Forensics is fun.pptm](https://mercury.picoctf.net/static/2e739f9e0dc9f4c1556ea6b033c3ec8e/Forensics%20is%20fun.pptm)
### Solución
Descargamos el archivo y descomprimimos, buscamos en las carpeta y notamos que hay un archivo llamado "hidden", lo abrimos y tomamos la serie de caracteres, que parecen estar en base 64, solamente tenemos que convertirlos y obtenemos la cadena

	echo "Z m x h Z z o g c G l j b 0 N U R n t E M W R f d V 9 r b j B 3 X 3 B w d H N f c l 9 6 M X A 1 f Q" | tr -d " " | base64 -d

Solución: **picoCTF{D1d_u_kn0w_ppts_r_z1p5}**
### Notas adicionales
Un archivo pptm es un archivo de powerpoint con las macros habilitadas.
### Referencias 
https://www.youtube.com/watch?v=CsCeOp9PFGs&list=PLDo9DMLZyP6kTZ8Td37-LdbAx4-yNfHBl&index=28
