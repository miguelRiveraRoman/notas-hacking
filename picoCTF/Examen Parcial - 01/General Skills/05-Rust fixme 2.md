
### Descripción 
The Rust saga continues? I ask you, can I borrow that, pleeeeeaaaasseeeee?Download the Rust code [here](https://challenge-files.picoctf.net/c_verbal_sleep/babfbee79718a6363826ba86300173ffde6d81577e9dd07d4130c53a7eecf6c3/fixme2.tar.gz).
### Solución
Al igual que en fixme 1, descomprimimos el tar, revisamos los errores con **cargo build**, corregimos los errores, que son causado por la mutabilidad de una variable, luego lo ejecutamos y obtenemos la bandera 

Solución: **picoCTF{4r3_y0u_h4v1n5_fun_y31?}**
### Notas adicionales

	Cargo es el gestor de paquetes de rust, util para ver errores 

	En Rust, **las variables y referencias son inmutables por defecto**. Esto significa que no puedes cambiarlas a menos que lo digas explícitamente con la palabra clave `mut`
### Referencias 
https://doc.rust-lang.org/book/ch04-02-references-and-borrowing.html
