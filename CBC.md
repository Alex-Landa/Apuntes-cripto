El *"Cipher Block Chain"*  es la evolución del [[ECB]], este es de modo *"por bloques"*  o *"asíncrono"*
![[CBCpng.png]]

$$
C_0=IV
$$ 
$$
E_k([C_{i-1} \oplus m])=C_i
$$
**Fortalezas**
	1)Elimina las redundancias

**Debilidades**
	1)Es *"lento"*
	2) No es paralelizable