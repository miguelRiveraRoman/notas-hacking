
### Descripción 
Help us test the form by submiting the username as `test` and password as `test!`The website running [here](http://saturn.picoctf.net:61739/).
### Solución
Entramos a la pagina que nos da, accedemos con los datos que se nos brindad, aquí la clave está en fijarse el las redirecciones, nos brindan 2, el id de cada una está en base 64, lo decodificamos con cyberchef y ese será la bandera

Solución: **picoCTF{proxies_all_the_way_df44c94c}
### Notas adicionales


### Referencias 
https://cyberchef.org/#recipe=From_Base64('A-Za-z0-9-_',true,false)&input=YkY5MGFHVmZkMkY1WDJSbU5EUmpPVFJqZlE
