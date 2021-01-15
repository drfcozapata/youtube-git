# Comandos útiles de GIT

1. git init: inicializa el repositorio
2. git add .: preparar los archivos para el commit
3. git reset .: revierte lo que hizo git add .
4. git commit: hace el commit
5. git checkout -- .: permite recuperar el archivo con los últimos cambios hechos al hacer el commit e incluso recuperar el archivo si se borrara.
6. git log: muestra un listado de los commit
7. git commit --amend: permite corregir el mensaje escrito en el último commit
8. git checkout -b rama-heroes: sale del master, crear una nueva rama (branch; llamada "rama-heroes", en este caso) y se lleva toda la información guardada en el último commit a ésta
9. git branch: muestra las ramas del git
10. git checkout master: me lleva nuevamente al master y desaparece del directorio los archivos de la rama donde estaba trabajando
11. git merge rama-heroes: hace merge del contenido de la rama héroes (o de la rama que se indique)con el master
12. git branch -d rama-heroes: borra (delete) la rama una vez que hemos terminado de trabajar con ella y decidimos que no la vamos a usar más
13. git push: subo las correcciones hechas en local a github
14. git commit -am: me evita tener que escribir por separado los comandos 1 y 2



Con q salgo de la terminal cuando espera un comando.
Con Esc + :wq! termino la edición, guardo y salgo de inmediato.