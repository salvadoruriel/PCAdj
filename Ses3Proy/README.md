# Sesión 3: Memoria y apuntadores.
Al crear proyectos es fácil implementar demasiados elementos que puedan saturar el programa,
asi como operaciones que pueden saturar la memoria del sistema lo cual le resta calidad.

## Código en producción
Ya después de programar todo que se quiere entregar el proyecto a un cliente, por ejemplo
en la forma de un archivo ejecutable, puede resultar que el ejecutable sea demasiado pesado.
Esto sucede por toda la cantidad de elementos que se incluyen, de los cuales varios pueden
ser optimizados por la computadora al generar el producto en **modo producción**.

Adicionalmente se suele mantener a veces una versión lo más simplificada posible, donde
inclusive los comentarios son omitidos, pero **siempre se debe mantener una documentación
del código**, ya sea **interna** (en comentarios) o **externa** (en formas de wikis que hablan
sobre las funciones en específico).

Como recomendaciones generales para sus programas pueden:
1.  Mantener una separación clara entre definición y declaración.
    * Por lo general se dejan las declaraciones en los archivos .h o de referencia.
    * Las definiciones suelen ir en los archivos .c o de implementación.
    * Esta separación, aunque minúscula, ayuda al compilador a generar mejores referencias,
  código más óptimo y programas menos pesados, así como también ventajas de velocidad y desempeño.
2. Mantener una versión de prueba, y una versión final que no incluya pruebas.
    * O mejor aún buscar si las herramientas usadas o el lenguaje permiten pruebas automáticas.
3. Comparar el desempeño de los programas finales generados con cada versión.
    * Puede suceder que la versión de producción no sea la mejor, y en el peor de los casos
    tenga problemas que implican una revisión más tranquila y detallada.
    
## Cuestiones de memoria
Los apuntadores son una herramienta más poderosa de lo que parecen, al permitir
accesar directamente a espacios de memoria, se podría tomar estas operaciones como
ambiguas con respecto al resto de las ya vistas, esto es porque con definiciones o
implementaciones incorrectas se pueden generar desde problemas de memoria, hasta formas
de vulnerar sistemas tanto por el dueño del sistema como por un atacante.

En si se recomienda esto al lidiar con memoria y apuntadores:
1. Ten cuidado con los apuntadores, especialmente cuando los compartes como información.
2. Si pasas a usar apuntadores de apuntadores, es recomendable hacer un esquema que
te permite interpretar como los estas manejando (o mantener buenos comentarios).
3. Toma en cuenta los tamaños de memoria al lidiar con apuntadores, de esto sale la
importancia de definir apuntadores para cada tipo, ya que mezclarlos puede causar errores.

## Conocimientos hasta esta sesión
Esta tematica si bien es más teorica, tiene su importancia en la calidad y la seguridad de los 
programas, aunque en general varia segun el lenguaje y el *framework* en el que se elabora todo.
Dada la definicion directa de apuntadores en **C**, **se recomienda usar este lenguaje** para resolver los 
desafios.
    
