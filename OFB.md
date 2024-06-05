El *"Output Feed Back"* es del modo *"[[Flujo]]"* o *"sincrónico"*, es rápido a la hora de hacer el cifrado
![[OFB.png]]
$$
G_0=E_k(VI)
$$
$$
	G_i=E_k(G_{i-1})
$$
$$c=g_i \oplus m_i$$
Donde ***VI*** que es el vector de inicialización es una cadena pseudo-aleatoria del tamaño de entrada de ***"E"***
***"m"*** es una parte del mensaje que puede ser de 
$$1 \leq m \leq G_i $$
**"Fortalezas"**
	1) Es rápido
	2) semi paralelizable

**"Debilidades**
	1)Es menos seguro que el [[CFB]]
