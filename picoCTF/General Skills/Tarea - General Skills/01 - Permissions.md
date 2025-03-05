
### Descripción 
Can you read files in the root file?The system admin has provisioned an account for you on the main server:`ssh -p 60069 picoplayer@saturn.picoctf.net`Password: `j4ks-9nxB-`Can you login and read the root file?
### Solución
Se requiere ingresar a una carpeta a la cual solo el admi tiene permisos, entonces vamos por pasos:
	# 1 Ejecutamos el comando *sudo -l*  para ver las opciones que tenemos como admi
	# 2 Con el comando *sudo vi* abrimos un editor de tezto poderoso
	# 3 Ejecutamos *:!bash* para abrir un nuevo terminal pero con privilegios
	# 4 Cambiamos a la carpeta de root y revisamos la bandera 
	
	Solución: picoCTF{uS1ng_v1m_3dit0r_021d10ab}
### Notas adicionales
	Se necesitaba entrar a la raiz, que era root, pero nos ayudamos con un script hecho en vi

### Referencias 

