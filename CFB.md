El ***"Cipher Feed Back"*** es un modo de operación por *[[flujo]]* o *"sincrono"*

![[CFB.png]]

$$
G_1=E_k(VI)
$$
$$
G_n=E_k(C)
$$
$$
C=m \oplus G_n
$$
Donde ***VI*** que es el vector de inicialización es una cadena pseudo-aleatoria del tamaño de entrada de ***"E"***
***"m"*** es una parte del mensaje que puede ser de 
$$1 \leq m \leq G_i $$
**"Fortalezas"**
	1) Mayor seguridad que [[OFB]]
	2) Más rápido que [[CBC]]
**"Debilidades"**
	1) 