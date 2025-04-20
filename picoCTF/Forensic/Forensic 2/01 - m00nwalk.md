
### Descripción 
Decode this [message](https://jupiter.challenges.picoctf.org/static/14393e18d98fedbaedbc28896d7ef31a/message.wav) from the moon.
### Solución
Viendo el formato con el que se enviaron las imágenes de la luna a la tierra, encontramos una herramienta para ese formato concreto en github, la instalamos y la usamos para decodificar el audio en una imagen, teniendo la imagen la bandera se encuentra en ella

Solución: **picoCTF{beep_boop_im_in_space}**

![[Pasted image 20250420121502.png]]
### Notas adicionales
Las imagenes de la luna a la tierra se enviaron con un formato llamado sstv de 10 frames por segundo 

Pistas: 
	1. How did pictures from the moon landing get sent back to Earth?
	2. What is the CMU mascot?, that might help select a RX option




### Referencias 
https://github.com/colaclanth/sstv

https://www.youtube.com/watch?v=UyLTEpAz6eE&list=PLDo9DMLZyP6kTZ8Td37-LdbAx4-yNfHBl&index=19
