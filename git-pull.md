# Git Pull
Descarga los cambios de la rama remota especificada y los fusiona automáticamente en la rama local actual.
````bash
git pull origin main
````

Descarga los cambios de la rama remota especificada y aplica tus cambios locales encima de ellos mediante un rebase en lugar de una fusión.
````bash
git pull --rebase origin main
````

Realiza un pull solo si es posible hacerlo mediante un avance rápido (fast-forward), de lo contrario, arrojará un error.
````bash
git pull --ff-only origin main
````
