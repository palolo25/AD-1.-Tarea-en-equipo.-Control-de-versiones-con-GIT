# AD-1. Tarea en equipo. Control de versiones con GIT


## Requerimiento 1

Se pide que se cree un repositorio local y remoto y que todos los participantes trabajen con él de manera básica. Para ello se deben de hacer los siguientes pasos.

Crear un repositorio en GitHub llamado "Repo1Actividad1" y agregar a tus compañeros como colaboradores.
En dicho repositorio habrá que subir un workspace java hecho en Eclipse con un fichero “.gitignore” que, al menos, no versione los ficheros y carpetas propios de eclipse y los “.class” de java. Además, en el workspace se deberá crear un proyecto Java normal. De esta tarea solo debe encargarse uno de los participantes.
Cada uno de los participantes debe clonar el repositorio en su máquina local. Nótese que con esto también se crea el repositorio local y no hace falta que cada participante lo cree.
Cada participante debe crear una rama llamada "develop" y cambiarse a ella para hacer los cambios que se pedirán más adelante.
En la rama "develop", cada participante debe crear un nuevo paquete con su nombre y dentro de él, crear una clase de Java con su nombre. Por ejemplo, si tu nombre es Ana, debes crear una clase llamada "Ana.java" en un paquete llamado "Ana".
Cada participante debe escribir un método en su clase que imprima su nombre en la consola. Por ejemplo, el método de Ana debería imprimir "Hola, soy Ana". Dicho método será llamado dentro del método main.
Cada participante debe hacer commit de sus cambios a la rama "develop".
Uno de los participantes debe hacer un merge de la rama "develop" en la rama principal "master" y a continuación hacer un push al repositorio remoto
El resto de los participantes deben hacer pull en la rama "master" y asegurarse de que pueden ver los archivos que ha creado el participante en el paso 8.
Repetir el paso 8 y 9 para el resto de los participantes hasta que todos hayan subido los cambios al repositorio y todos tengan el código hecho por todos los participantes en la rama principal. No debería de dar problemas de conflicto, ya que todos los participantes están trabajando con distintos ficheros.
IMPORTANTE, todos los pasos de todos los participantes deben de quedar plasmados con sus resultados en el documento de entrega.

Valoración: 5 puntos sobre 10

## Requerimiento 2

Se pide que cada integrante siga desarrollando funcionalidades en su fichero y en su rama una vez que tiene todos los cambios de sus compañeros en su repositorio local.

Cada integrante debe pasar los cambios de la rama principal a la su rama “develop” para ello debe de hacer un merge de la rama principal “master” a su rama “develop”. Ahora en su rama “develop” deberá de poder ver todos los cambios que había en la rama principal ya que ambas ramas apuntan al mismo commit.
Cada integrante debe de cambiar su código para que además de imprimir su nombre, ahora también imprima 3 “hobbies” que le gustan hacer.
Uno de los participantes debe hacer un merge de la rama "develop" en la rama principal "master" y a continuación hacer un push al repositorio remoto
El resto de los participantes deben hacer pull en la rama "master" y asegurarse de que pueden ver los archivos que ha creado el participante en el paso 3.
Repetir el paso 3 y 4 para el resto de los participantes hasta que todos hayan subido los cambios al repositorio y todos tengan el código hecho por todos los participantes en la rama principal. No debería de dar problemas de conflicto, ya que todos los participantes están trabajando con distintos ficheros.
Nótese como una buena manera de trabajar con GIT y de evitar problemas es siempre con una rama diferente a la master, y solo usar la master para tener el código común del repositorio.

IMPORTANTE, todos los pasos de todos los participantes deben de quedar plasmados con sus resultados en el documento de entrega.

Valoración: 2 puntos sobre 10

## Requerimiento 3

En este apartado vamos a trabajar con los conflictos y como solucionarlos. Para ello vamos a trabajar varios integrantes con un mismo fichero, concretamente con las mismas líneas de código.

Cada integrante debe pasar los cambios de la rama principal a la su rama “develop” para ello debe de hacer un merge de la rama principal “master” a su rama “develop”. Ahora en su rama “develop” deberá de poder ver todos los cambios que había en la rama principal ya que ambas ramas apuntan al mismo commit.
Un participante deberá de hacer cambios en su fichero .java, esta vez deberá imprimir por pantalla 3 comidas favoritas. Una vez cambiado el fichero hará un commit del mismo.
Otro participante deberá de hacer cambios en el mismo fichero que su compañero de trabajo hizo en el punto 2, en este caso deberá de imprimir por pantalla sus 3 comidas favoritas y realizará el commit A continuación, hará un merge de la rama “develop” a la rama principal “master” y subiera los cambios al repositorio remoto mediante un push.
El participante propietario del archivo hará un pull en la rama “master” para bajarse los cambios de su compañero, y a continuación, hará un merge de la rama “develop” a la rama principal “master”. Git sacará conflictos que se deberán de solucionar ya que 2 personas han hecho cambios en las mismas líneas.
Los dos participantes deberán de decidir cuáles son los cambios que se van a quedar, y será el participante propietario del fichero el que se encargue de dejar los cambios finales en el fichero. También se asegurará que el código compila y funciona adecuadamente.
El participante propietario del fichero subirá los cambios al repositorio remoto mediante un push y su compañero se lo bajará para verlos en su repositorio local mediante un pull.
El resto de los participantes deben de repetir los pasos del 2 al 7 con otros compañeros.
Todos los participantes hacen un pull para tener todos los cambios del equipo en su repositorio local.
 

IMPORTANTE, todos los pasos de todos los participantes deben de quedar plasmados con sus resultados en el documento de entrega.

Valoración: 2 puntos sobre 10

## Requerimiento 4

Plasmar en el documento las conclusiones grupales sobre la experiencia de trabajar con Git, con fortalezas y/o debilidades.

Valoración: 1 puntos sobre 10
