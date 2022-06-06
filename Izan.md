2.c - Se ha realizado un git init sobre el directorio para iniciar el repositorio git, luego se ha añadido el directorio de capturas al área de intercambio con un git add capturas_LorenzoMarti y por último se ha mostrado el estadod del repositorio con git status, vemos cómo los demás directorios no han sido añadidos al área de intercambio.
3.c - Se ha realizado un git add -A (la opción -A añade todos los ficheros al área de intercambio), al hacer el git status vemos cómo no hay ficheros sin seguimiento.
4 - Utilizando el editor de texto nano, he añadido Izan.md al fichero .gitignore, el cual sirve para indicar qué ficheros han de ser ignorados.
5 - Mismo procedimiento que para el apartado anterior.
6 - Se utiliza el comando git commit -m "copia" para crear una nueva instantánea del repositorio, y le especificamos como título "copia" (ignorad el -a, pensaba que al añadir esta opción se añadiría el .gitignore al commit, pero esta opción solo sirve para ficheros que ya han sido guardados anteriormente y se desea actualizar).
7 - He creado el nuevo fichero con el editor nano.
8 - Esta vez he optado por añadir primero todos los ficheros al área de intercambio antes de hacer el commit y comprobar primero con un git status las modificaciones pendientes de confirmar.
9 - Fichero modificado con éxito gracias a nano.
10 - Repetir apartado 8 (¿Soy yo o el fichero Izan.md está siendo guardado en el commit a pesar de que este está guardado en el .gitignore?, no entiendo por qué ocurre esto pero supongamos que no está en seguimiento a pesar de todo).
11 - Con un git log --oneline se muestran las diferentes versiones de nuestro repositorio, con el comando git restore podemos volver a una versión anterior de un fichero indicando en --source el código de la versión que deseamos recuperar.
12 - @see: apartados 8 y 9; ahora mismo el texto del fichero es idéntico al de la versión de HEAD antes de hacer el commit.
13 - repetimos la explicación para los apartados 8 y 9; esta vez las dos últimas líneas del fichero son distintas a su versión anterior.
14 - Lo más importante a destacar es que hemos creado la nueva rama y nos hemos situado en ella en un solo paso gracias a la opción -b de git checkout, la cual permite exáctamente esto.
15 - Para poder hacer la fusión sobre la rama principal (para este repositorio tiene como nombre master) primero necesitamos hacer un checkout, y luego fusionarlos con un merge.
16 - Repetimos el apartado 14 (por favor, ignorad que en un primer momento he confundido el orden de las opciones -a y -m).
17 - En la información mostrada en el git log podemos ver que el HEAD apunta al último commit de la rama rama_Marti, las ramas rama_Lorenzo y master están situadas en el commit que he tenido que realizar para hacer el checkout a main.
18 - 
