Usado para la [[huella digital]], [[HMAC]], y verificación de integridad, no requiere de ninguna llave (secreto),este trabaja con los bits del mensaje a **Transformar**.

**Propiedades Del HASH**
	1) trabaja con los bits del mensaje
	2) No requiere de secretos
	3) tiene una salida fija sin importar la entrada
	4) La *"avalancha"* es que con cambiar un bit, se modifica gran parte de la salida

**Debilidades**
	1) si se encuentra una colisión, el algoritmo de transformación ya no sirve  