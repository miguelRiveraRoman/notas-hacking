
### Descripción 
The Multiverse is within your grasp! Unfortunately, the server that contains the secrets of the multiverse is in a universe where keyboards only have numbers and (most) symbols.`ssh -p 52677 ctf-player@mimas.picoctf.net`Use password: `6abf4a82`
### Solución
Utilizamos wildCards para encontrar la bandera
el * lo usamos para directorios y el ? para comandos, con el siguiente comando abrimos el archivo con base 64

Luego solamente usamos cyberchef para convertir la base 64 y obtener la bandera 

	/*/???[!_]64 ~/*/????.???
	
Solución:**picoCTF{7h15_mu171v3r53_15_m4dn355_8b3d83ad}**
### Notas adicionales
	En Linux, los caracteres comodín (wildcards) son ==símbolos especiales que se utilizan para representar uno o más caracteres en nombres de archivos o rutas==. Facilitan la búsqueda, manipulación y procesamiento de archivos y directorios.

### Referencias 
https://cyberchef.org/#recipe=From_Base64('A-Za-z0-9%2B/%3D',true,false)
