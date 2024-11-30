El nacimiento del mundo asimétrico se da a partir de la publicación del *paper* de [[diffie-helman.pdf]] en 1976. esto viene a romper todos los paradigmas que se tenían desde antes ya que las propuestas y los retos prácticamente rompen con las practicas del [[Mundo Simétrico]]

**Propuestas de Diffie-Hellman**
- Nuevo tipo de criptografía
- Problema de la llave
- firma digital

**Retos de Diffie-Hellman**
- **Fácil**: 
	- Fácil generar la pareja de llaves ($K_{\text{priv}} , K_{\text{pub}}$) para A y B
	- fácil para A, calcular C a partir de M y $K^{\text{pub}}_B$
	- fácil para B, recuperar M a partir de C y $K^{\text{priv}}_B$
- **Difícil**:
	- Difícil para B saber $K_{\text{priv}}$ a partir de $K_{\text{pub}}$
	- Difícil recuperar M a partir de C y $K_{\text{pub}}$
- **Opcional** :
	- Es que cifrado y descifrado puedan aplicarse en cualquier orden (RSA cumple con esa característica)

**Servicios que provee el mundo**
- [[Autenticación]] Fuerte
- Confidencialidad
- No Repudio
