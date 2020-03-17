# Desafíos del tercer tema
Intenta estos problemas con tiempo, así podras preguntar o investigar con calma.
---
## 3.1 Loto-Mac!
En la primera sesión investigaste una forma de generar números al azar, ahora
aprovecha eso para generar números al azar con los cuales llenar un *struct
sorteo* que contenga 4 valores enteros, con valores del 1 al 65.
*Para facilitar nombres puedes tener 4 enteros que sean bola1, bola2, etc...*

**\*Version 2**: Ahora pide 4 números al usuario con los cuales llenar
otra instancia del struct. Verifica que tanto los del usuario como los que
tu generas al azar no se repitan.  
*Puedes facilitar esto checando que cada número siguiente sea más grande
que el anterior y/o volviendo a generar todo el sorteo si no se cumple.*

**\* \*Yeyecoa** (*Original Spin*):  Compara los números ingresados
con los generados, y si estos no coinciden guárdalos en un arreglo y repite
hasta que coincidan o se halla iterado más de 200 veces.  
Al final imprime los primeros y últimos n juegos que te pida el usuario más
aparte en el que gano (si es que lo hizo).  
*Ejemplo:*
```javascript
Cuantos sorteos quieres ver?
-> 2
Sorteo 1: 2 5 12 34
Sorteo 2: 6 21 32 56
...
Sorteo 188: 1 18 22 56
Sorteo 189: 1 2 4 65
Ganaste en el sorteo 190! (3 13 20 21)
```
*Pista: aprovecha que los números en el struct deben ir en orden para
facilitar la comparacion. Guarda los valores en un arreglo de dos dimensiones
o en un apuntador de apuntadores.*

## 3.2 Endianness
Una aplicación de punteros es ver como organiza la información la computadora.
Aprovecha punteros de c para descubrir la endianness de tu computadora, esto es
la forma en que se organizan los bits, ya sea sí de izquierda a derecha o viceversa.
Esto se puede lograr de forma muy fácil teniendo un valor entero 1 y con conversión
tipo C pasando la dirección de memoria a otro apuntador de un tipo más chico.
Finalmente imprimes el valor del *contenido* del apuntador, y si se conserva el
valor 1 entonces es de endianness pequeña, de lo contrario es grande.  
**Conversion tipo C**:
```javascript
int a=1;
char algo = (char)a;
```
**Cuidado con el plagio**: Hay muchas formas de resolver un problema, pero
no copies el esfuerzo de alguien más, desarrolla tus habilidades. Si tienes dudas o ideas
*primero inténtalas* y pide ayuda si encuentras algún tipo de error *especifico*.
