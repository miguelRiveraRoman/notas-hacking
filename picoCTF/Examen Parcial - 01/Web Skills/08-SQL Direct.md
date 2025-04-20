
### Descripción 
Connect to this PostgreSQL server and find the flag!`psql -h saturn.picoctf.net -p 49928 -U postgres pico`Password is `postgres`
### Solución
Nos conectamos al servidor y revisamos el contenido de la base de datos con \l, luego seleccionamos la tabla pico con \c, posteriormente hacemos un select * from flags, para obtener la bandera.

Solución: **picoCTF{L3arN_S0m3_5qL_t0d4Y_21c94904}**
### Notas adicionales


### Referencias 

