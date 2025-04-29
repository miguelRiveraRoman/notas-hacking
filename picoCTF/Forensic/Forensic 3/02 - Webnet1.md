
### Descripción 
We found this [packet capture](https://jupiter.challenges.picoctf.org/static/fbf98e695555a2a48fe42c9a245de376/capture.pcap) and [key](https://jupiter.challenges.picoctf.org/static/fbf98e695555a2a48fe42c9a245de376/picopico.key). Recover the flag.
### Solución
El reto nos proporciona una serie de paquetes y una llave para desencriptarlos, utilizamos la herramienta wireshark para ver el flujo de paquetes, solo que ajustamos las preferencias para incluir la llave del desencriptado, notamos que hay una imagen descargandose, así que la guardamos y luego le aplicamos un string, filtrando con pico encontramos la bandera.

Solución: **picoCTF{honey.roasted.peanuts}**
### Notas adicionales
	TLS es un protocolo criptográfico diseñado para proveer comunicaciones seguras.

	También se puede resolver directamente en wireshark, buscando en el detalle de los paquetes revisamos el contenido de la imagen. 

	También se puede resolver con ssldump 

	Pistas:
	1. Try using a tool like Wireshark.
	2. How can you decrypt the TLS stream?

### Referencias 
https://www.youtube.com/watch?v=Ym3i79nEHjw&list=PLDo9DMLZyP6kTZ8Td37-LdbAx4-yNfHBl&index=25
