# Git Commit
El comando git commit se utiliza para registrar los cambios realizados en el área de preparación (staging area) en el historial de versiones de Git.
````bash
git commit -m "Mensaje del commit"
````

-a o --all: Agrega todos los cambios modificados y eliminados al área de preparación antes de realizar el commit. Esto evita la necesidad de utilizar git add para cada archivo modificado.
````bash
git commit -m "Mensaje del commit"
````
--amend: Modifica el commit más reciente. Esto te permite agregar cambios olvidados al commit anterior o editar el mensaje del commit.
````bash
git commit -m "Mensaje del commit"
````