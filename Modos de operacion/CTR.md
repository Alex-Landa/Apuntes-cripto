El ***"Counter"*** es un modo de operación por *[[Flujo]]* o *"sincrono"*, es el más rápido de estos algoritmos
![[CTR.png]]
$$
c_i= E_k(Cont_i) \oplus m_i
$$
Donde:
	"Cont" es una cadena pseudo aleatoria de tamaño que *"E"* usa e incrementa como *"Cont++"*
	"m" es un subconjunto de "M"	
**Debilidades**
	1) *"Cont"* puede ser descubierto por **fuerza bruta** 