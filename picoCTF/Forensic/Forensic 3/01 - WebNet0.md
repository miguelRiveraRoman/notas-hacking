
### Descripción 
We found this [packet capture](https://jupiter.challenges.picoctf.org/static/0c84d3636dd088d9fe4efd5d0d869a06/capture.pcap) and [key](https://jupiter.challenges.picoctf.org/static/0c84d3636dd088d9fe4efd5d0d869a06/picopico.key). Recover the flag.
### Solución
El reto nos proporciona una serie de paquetes y una llave para desencriptarlos, utilizamos la herramienta wireshark para ver el flujo de paquetes, solo que ajustamos las preferencias para incluir la llave del desencriptado, posteriormente solo realizamos una búsqueda del String.

Solución: **picoCTF{nongshim.shrimp.crackers}**

### Notas adicionales
	TLS es un protocolo criptográfico diseñado para proveer comunicaciones seguras 

	También se puede resolver utilizando la herramienta ssldump

	Pistas:
	1. Try using a tool like Wireshark.
	2. How can you decrypt the TLS stream?
### Referencias 
https://www.youtube.com/watch?v=9uflLPoETOc&list=PLDo9DMLZyP6kTZ8Td37-LdbAx4-yNfHBl&index=24
