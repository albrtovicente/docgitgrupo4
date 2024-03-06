# Git Branch -d
El comando git branch -d indica que se quiere eliminar la rama de forma segura. La rama que se intenta eliminar tiene que estar completamente fusionada con la rama actual antes de proceder con la eliminación.
````bash
git branch -d <branchname>
````
El comanado git branch -D fuerza la eliminación de la rama, incluso si no está completamente fusionada.
````bash
git branch -D <branchname>
````