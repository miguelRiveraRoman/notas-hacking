
### Descripción 
Have you heard of Rust? Fix the syntax errors in this Rust file to print the flag!Download the Rust code [here](https://challenge-files.picoctf.net/c_verbal_sleep/3f0e13f541928f420d9c8c96b06d4dbf7b2fa18b15adbd457108e8c80a1f5883/fixme1.tar.gz).
### Solución
Primero descomprimimos el archivo tar

	tar -xvzf

Luego de una instalación de paquetes y configurar la version de cargo, utilizamos **cargo build** para ver los errores del código, nos marca 3 errores, los arreglamos y luego corremos el codigo 

	sudo apt install cargo
	sudo apt install rustup
	rustup default stable
	cargo build
	nano main.rs
	 cargo run

Los errores eran solo cosas de sintaxis.

Solución: **picoCTF{4r3_y0u_4_ru$t4c30n_n0w?}**
### Notas adicionales
	Cargo es el gestor de paquetes de rust, util para ver errores 


### Referencias 
https://doc.rust-lang.org/book/ch01-03-hello-cargo.html

https://doc.rust-lang.org/std/macro.println.html