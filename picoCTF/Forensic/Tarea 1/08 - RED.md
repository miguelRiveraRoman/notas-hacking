
### Descripción 
RED, RED, RED, REDDownload the image: [red.png](https://challenge-files.picoctf.net/c_verbal_sleep/831307718b34193b288dde31e557484876fb84978b5818e2627e453a54aa9ba6/red.png)
### Solución
Usamos el comando **zsteg**, vemos que hay datos que parecen estar en base 64, simplemente los convertimso y obtenemos la bandera 
	echo cGljb0NURntyM2RfMXNfdGgzX3VsdDFtNHQzX2N1cjNfZjByXzU0ZG4zNTVffQ==cGljb0NURntyM2RfMXNfdGgzX3VsdDFtNHQzX2N1cjNfZjByXzU0ZG4zNTVffQ=cGljb0NURntyM2RfMXNfdGgzX3VsdDFtNHQzX2N1cjNfZjByXzU0ZG4zNTVffQ==cGljb0NURntyM2RfMXNfdGgzX3VsdDFtNHQzX2N1cjNfZjByXzU0ZG4zNTVffQ==" | base64 -d

Solución: **picoCTF{r3d_1s_th3_ult1m4t3_cur3_f0r_54dn355_}}**
### Notas adicionales
**zsteg** es_ una herramienta de la linea de _comandos_ para detectar datos ocultos en imÃ¡genes PNG y BMP. Funciona analizando diversas propiedades de la imagen 

Pistas:
	1. The picture seems pure, but is it though?
	2. Red?Ged?Bed?Aed?
	3. Check whatever Facebook is called now.

### Referencias 

