
### Descripción 
Welcome to the challenge! In this challenge, you will explore a web application and find an endpoint that exposes a file containing a hidden flag.The application is a simple blog website where you can read articles about various topics, including an article about API Documentation. Your goal is to explore the application and find the endpoint that generates files holding the server’s memory, where a secret flag is hidden.The website is running [picoCTF News](http://verbal-sleep.picoctf.net:50767/).
### Solución
Entramos a la pagina, uno de los hastags en un hipervinculo, entramos en él y hasta abajo aparece la api headdump, que es la que nos interesa, descargamos el archivos y luego simplemente buscamos la bandera en el utilizando **grep**

Solución: **picoCTF{Pat!3nt_15_Th3_K3y_13d135dd}**
### Notas adicionales


### Referencias 

