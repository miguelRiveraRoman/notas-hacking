
### Descripción 
There's something in the [building](https://jupiter.challenges.picoctf.org/static/011955b303f293d60c8116e6a4c5c84f/buildings.png). Can you retrieve the flag?
### Solución
Utilizamos una herramienta hecha en ruby llamada gema
	*zsteg -a buildings.png | grep picoCTF*

Solución:
	**"picoCTF{h1d1ng_1n_th3_b1t5}"**
### Notas adicionales
La **esteganografía** es la técnica de ocultar información dentro de otro medio, como imágenes, audios o videos, de manera que la existencia del mensaje secreto sea imperceptible a simple vista

también podemos utilizar una herramienta de esteganografía en la web

**zsteg** también nos proporciona las técnicas que utiliza 
### Referencias 

