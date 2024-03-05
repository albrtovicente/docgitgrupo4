# Git Merge
Deshace todos los commits después de <commit>, conservando los cambios en el área de trabajo.
````bash
git reset HEAD~3
````

Deshace los commits después de <commit>, pero mantiene los cambios en el área de preparación (staging), permitiéndote volver a hacer los commits con los cambios "preparados".
````bash
git reset --soft HEAD~3
````

Deshace los commits después de <commit> y también deshace los cambios en el área de preparación (staging), pero conserva los cambios en el área de trabajo, lo que te permite revisar los cambios antes de volver a prepararlos.
````bash
git reset --mixed HEAD~3
````
