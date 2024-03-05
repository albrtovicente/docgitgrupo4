# Git Merge
Se utiliza para combinar cambios de una rama a otra.


Incorpora cambios de las confirmaciones nombradas (desde el momento en que sus historiales divergieron de la rama actual) en la rama actual.
````bash
git merge --abort:
````

Combina los cambios de la rama especificada (<branch>) en la rama actual.
````bash
git merge feature_branch
````

Realiza una fusión no fast-forward, creando un nuevo commit incluso si no hay conflicto, para mantener un historial de fusión más claro.
````bash
git merge --no-ff feature_branch
````
