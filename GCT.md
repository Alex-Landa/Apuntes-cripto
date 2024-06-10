El ***"Galois Counter"***  es la evolución del modo de operación de [[CTR]], este implementa los servicios "[[MAC]]"  
![[GCM.png]]
$$VI -> 1 \leq VI < b \space |\space [b=input\space E_k]$$
$$ c_i= m_i \oplus E_k(VI|Cont_i)\space |\space Cont \neq 0 $$
$$L= len(M)$$
$$H=E_k(0)$$
$$S=E_k(VI|0)$$
$$ g_0=c {\otimes} H $$$$g_i=(g_{i-1}\oplus c_i)\otimes H$$
$$T=[(L\oplus g_i)\otimes H]\oplus S$$
ss