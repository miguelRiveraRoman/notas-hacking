
### Descripción 
BookShelf Pico, my premium online book-reading service.I believe that my website is super secure. I challenge you to prove me wrong by reading the 'Flag' book!Here are the credentials to get you started:

- Username: "user"
- Password: "user"

Source code can be downloaded [here](https://artifacts.picoctf.net/c/479/bookshelf-pico.zip).Website can be accessed [here!](http://saturn.picoctf.net:49592/).
### Solución
Tenemos que modificar el token del libro que solo está accesible para el usuario, nos vamos al storage y en el almacenamiento local esta la firma. Aquí la clave es modificar tanto el token cifrado como el token de abajo, en ugar de user free, colocamos el admin.

Solución: picoCTF{w34k_jwt_n0t_g00d_d7c2e335}
### Notas adicionales
Para este reto si batallé un montón, hice de todo

Se puede utilizar burp Suite

### Referencias 

