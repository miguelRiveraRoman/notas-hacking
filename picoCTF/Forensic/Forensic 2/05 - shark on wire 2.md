
### Descripción 
We found this [packet capture](https://jupiter.challenges.picoctf.org/static/b506393b6f9d53b94011df000c534759/capture.pcap). Recover the flag that was pilfered from the network.
### Solución
Utilizando wireshark vemos el contenido de los paquetes, nos centramos en los UDP, notamos que el numero de puerto de salida - 5000 nos da un numero hexa que representa la bandera, por lo tanto sólo tenemos que crear un script que nos obtenga dicho numero, para eso utilizamos un paquete llamado scapy, que nos ayuda a manejar la información de los paquetes.

En el script realizamos las operaciones antes mencionadas, validando que se centre en los puertos superiores a 5000 y de destino 22

	from scapy.all import *
	
	packets  = rdpcap('capture.pcap')
	
	flag = ''
	
	for p in packets:
	        if UDP in p and p[UDP].dport == 22:
	                if p[UDP].sport > 5000:
	                        flag += chr(p[UDP].sport - 5000)
	
	print(flag)


Solución: **picoCTF{p1LLf3r3d_data_v1a_st3g0}**
### Notas adicionales

### Referencias 
https://www.youtube.com/watch?v=WcMl1SvQ6hI&list=PLDo9DMLZyP6kTZ8Td37-LdbAx4-yNfHBl&index=23
