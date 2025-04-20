
### Descripción 
Reception of Special has been cool to say the least. That's why we made an exclusive version of Special, called Secure Comprehensive Interface for Affecting Linux Empirically Rad, or just 'Specialer'. With Specialer, we really tried to remove the distractions from using a shell. Yes, we took out spell checker because of everybody's complaining. But we think you will be excited about our new, reduced feature set for keeping you focused on what needs it the most. Please start an instance to test your very own copy of Specialer.`ssh -p 62645 ctf-player@saturn.picoctf.net`. The password is `3f39b042`
### Solución
Al igual que en el anterior reto, tenemos que usar wildcards.

Primero nos conectamos a un servidor y notamos que no podemos usar ciertos comandos, entonces con el comando 

	help

Revisamos cuales si podemos usar, y mediante wildcards llegamos a la bandera, la cual esta dentro de una carpeta en un archivo txt

	echo "$(<ala/kazam.txt)"


Solución: **picoCTF{y0u_d0n7_4ppr3c1473_wh47_w3r3_d01ng_h3r3_811ae7e9}**
### Notas adicionales


### Referencias 

