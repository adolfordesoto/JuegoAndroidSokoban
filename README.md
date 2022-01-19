# JuegoAndroidSokoban

El alumno deberá desarrollar una aplicación android que permita jugar al usuario a un juego basado en el rompecabezas [Sokoban](https://es.wikipedia.org/wiki/Sokoban).

El rompecabezas consiste en mover unas cajas a sus posiciones finales mediante un robot que únicamente puede empujar las cajas. El juego permitirá al usuario manejar al robot indicándo mediante el interfaz de usuario sus movimientos con el objetivo de resolver el rompecabezas. 

El juego se desarrolla en un almacén que vendrá descrito en modo texto por los siguientes caracteres:
- Un carácter blanco ' ' define un espacio vacío,
- la almohadilla '#' representa un muro que el robot no puede atravesar,
- el dólar '$' es una caja,
- el punto '.' es un objetivo,
- la arroba '@' es el robot,
- el más '+' es el robot sobre un objetivo,
- y el asterísco '\*' es una caja sobre un objetivo.

Se pueden ver ejemplos de aplicaciones del juego en la página web http://www.rodoval.com/heureka/sokoban/sokoban.html, incluso existe una aplicación Android (¡¡no vale plagiar!!).

El desarrollo de la aplicación se realizará creando varios prototipos acumulativos. La funcionalidad que deben cubrir cada uno de ellos será la siguiente:
1. **Primer Prototipo.** La aplicación es capaz de visualizar la pantalla del juego mediante el uso de imágenes adecuadas a partir de la definición de un almacén dada como una cadena de texto. La aplicación mantiene una buena visión de esa pantalla en diferentes dispositivos y tiene un comportamiento de ciclo de vida adecuado.
2. **Segundo Prototipo.**  La aplicación permite al usuario jugar, es decir mover al robot mediante el interfaz gráfico reflejando adecuadamente todos los movimientos posibles del robot, identificando cuando el usuario ha resuelto el juego. Optativamente la aplicación permitirá deshacer-rehacer movimientos.
3. **Tercer Prototipo.** La aplicación permite jugar a varios niveles de forma que el usuario tiene que ir superando un nivel para pasar al siguiente. Cada nivel vendrá definido  internamente en la aplicación.
4. **Cuarto Prototipo.** La aplicación permite crear habitaciones y almacenarlas en ficheros de texto en el almacenamiento interno de la app o en una base de datos.
5. **Quinto Prototipo.** La aplicación permite descargar de un servidor web niveles del juego y jugar a ellos.

El alumno comunicará al profesor cuando ha completado cada uno de los prototipos.
