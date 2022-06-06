2.c - Se ha realizado un git init sobre el directorio para iniciar el repositorio git, luego se ha añadido el directorio de capturas al área de intercambio con un git add capturas_LorenzoMarti y por último se ha mostrado el estadod del repositorio con git status, vemos cómo los demás directorios no han sido añadidos al área de intercambio.
3.c - Se ha realizado un git add -A (la opción -A añade todos los ficheros al área de intercambio), al hacer el git status vemos cómo no hay ficheros sin seguimiento.
4 - Utilizando el editor de texto nano, he añadido Izan.md al fichero .gitignore, el cual sirve para indicar qué ficheros han de ser ignorados.
5 - Mismo procedimiento que para el apartado anterior.
6 - Se utiliza el comando git commit -m "copia" para crear una nueva instantánea del repositorio, y le especificamos como título "copia" (ignorad el -a, pensaba que al añadir esta opción se añadiría el .gitignore al commit, pero esta opción solo sirve para ficheros que ya han sido guardados anteriormente y se desea actualizar).
7 - He creado el nuevo fichero con el editor nano.
8 - Esta vez he optado por añadir primero todos los ficheros al área de intercambio antes de hacer el commit y comprobar primero con un git status las modificaciones pendientes de confirmar.
9 - 
