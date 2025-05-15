
### Descripción 
I've gotten bored of handing out flags as text. Wouldn't it be cool if they were an image instead?You can download the challenge files here:

- [challenge.zip](https://artifacts.picoctf.net/c_atlas/1/challenge.zip)

The same files are accessible via SSH here:`ssh -p 53841 ctf-player@atlas.picoctf.net`Using the password `83dcefb7`. Accept the fingerprint with `yes`, and `ls` once connected to begin. Remember, in a shell, passwords are hidden!
### Solución
unicamente tenemos que escanear un codigo qr

Solución: **picoCTF{p33k_@_b00_3f7cf1ae}**
### Notas adicionales
Los codigos qr son codigos de barras bidimensionales. 

Pistas: 
	1. QR codes are a way of encoding data. While they're most known for storing URLs, they can store other things too.
	2. Mobile phones have included native QR code scanners in their cameras since version 8 (Oreo) and iOS 11
	3. If you don't have access to a phone, you can also use zbar-tools to convert an image to text

### Referencias 

