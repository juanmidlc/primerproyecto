git clone "url repo" - obtiene una copia exacta del proyecto indicando la url donde se obtendrá 

git status - nos dice la información acerca del estado de los archivos (modificados, eliminados, nuevos) si están incluidos, no incluidos y en que rama estamos colocados

git add - añadir un archivo para pasarlo de la etapa de unstage a stage, para estar listo para hacer un commit

git rm - remueve un archivo de la etapa de stage y la regresa a unstage

git commit - al ya tener archivos incluidos, se hará la confirmación de estos siempre todo en el repo local

git fetch - mira que cambios hay nuevos que se hayan obtenido desde el repo remoto, a una rama no permanente 

git pull - obtiene los cambios de la rama determinada y actualiza de una vez el repo local

git push - publica los archivos confirmados en el repo local al repo remoto

git checkout -b "nombre de la rama" -  creando una nueva rama local

git push -u "nombre de remoto" "nombre de rama" - se publica la nueva rama en el repo remoto, con una nueva rama remota del mismo nombre y en qué repo remoto estará, en conjunto con el parámetro "-u" que es del upstream, el cual también añadira el mismo de la rama local al del repo remoto.

git init - se inicializa el repositorio de GIT en la ruta que se desea manejar el repo local

git flow init - parte al inicio de la creación de un repo nuevo que nos pide información acerca del repo (ramas, repos remotos)

git feature start "nombre" - crea inmediatamente una rama dando como parámetros el nombre de la rama 

git branch -D "nombre de la rama" - borra la determinada rama indicada en el parámetro 

git rebase - Cambia de nodo o commit padre con el fin de tener siempre actualizado los cambios de otras ramas con la mía

git checkout -  me cambia de rama a la que yo indique

git push -f -  se fuerza un push determinado siempre y cunado sepamos que es lo que estamos haciendo

git stash -  cuando se tienen archivos en la etapa de staged sin haberlos confirmado pero que aun no se confirmarán, se utiliza para meterlo a una pila, para jalar  los cambios que yo necesite  o cambiarme de rama  para luego ya regresar a la rama en la que trabajaba

git stash pop - sacará siempre el contenido que esté más arriba del stash, en la rama que se esté posicionado.