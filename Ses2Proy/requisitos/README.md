# Desafíos del segundo tema
La fecha de entrega se publica en el foro de *sea* cuando termine la del desafío pasado.
---
## 2.1 Organizar el menú
Ahora que el proyecto crecerá, cambia el menú de tal forma que tenga las siguientes opciones:
```javascript
0. Saludo
1. Sesion 1
2. Sesion 2
s. salir
```
Al seleccionar una opción de una sesión se abre otro menú con los desafíos que le corresponden. Ejemplo:
```javascript
1. Desafio 1.2 Arboles
2. Ejemplo(yeyecoa)
r. regresar
```
De esta forma es facil navegar entre las funcionalidades del proyecto
## 2.2 Valores máximos
Crea un struct con los tipos básicos (float,int,etc...) como elementos (agrégales *s* al inicio: sfloat, sint, ...) los 
cuales al ser llamados desde el menú imprimirán el maximo valor que pueden representar. *Pista: varios lenguajes tienen 
librerías que definen estos valores o los calculan, puedes investigarlas o crear la tuya.*
Aprovecha la forma de un struct para imprimir estos valores sobre cada elemento que contiene.
*Si el lenguaje no soporta structs, simula su forma con algo similar, como una clase (en forma sencilla).*
## 2.3 Valores mínimos  
Aprovecha el struct ya creado para con otra función dar los valores más bajos que pueden almacenar, estos serán **negativos**
en varios casos.
