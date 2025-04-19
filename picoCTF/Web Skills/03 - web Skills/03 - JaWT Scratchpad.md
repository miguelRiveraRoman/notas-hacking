
### Descripción 

Internal server errors can be intentionally returned by this challenge. If you experience one, try clearing your cookies.

Check the admin scratchpad! `https://jupiter.challenges.picoctf.org/problem/61864/` or http://jupiter.challenges.picoctf.org:61864

### Solución
_Accedemos al sitio, ponemos nuestro nombre, después con la extensión de cookie editor, buscamos la cookie jwt y copiamos el token, lo decodificamos en jwt.io, le cambiamos el nombre por "admin" y donde esta "secret" le pondremos ilovepico, al darnos una nueva cookie, la copiamos y pegamos, guardamos, recargamos y da la bandera.

Solución:**picoCTF{jawt_was_just_what_you_thought_1ca14548}

### Notas adicionales
	JSON: JavaScript Object Notation, 

	JWT: Define una forma compacta y autocontenida para transmitir de manera segura informacion entre partes usando JSON, un token json se conforma de tres partes, encabezado, payload y una firma

	Realizamos un ataque de diccionarios 

### Referencias 
https://www.youtube.com/watch?v=iaKbvrbcSko&list=PLDo9DMLZyP6kTZ8Td37-LdbAx4-yNfHBl&index=10
