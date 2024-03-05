# Git Clone
El comando git clone se utiliza para crear una copia local de un repositorio Git existente. Esto es útil cuando deseas trabajar en un proyecto que ya está siendo gestionado con Git y deseas obtener una copia del repositorio en tu propio sistema local.
````bash
git clone <URL_del_repositorio_remoto>
````
--depth permite clonar un repositorio con un historial de commits limitado a la cantidad de profundidad especificada. Por ejemplo, --depth 1 clonaría solo el commit más reciente, lo que sería útil si solo necesitas la versión más reciente del proyecto.
````bash
git clone depth <profundidad>
````
--branch permite clonar una rama específica del repositorio en lugar de la rama predeterminada. Por ejemplo, --branch develop clonaría la rama llamada "develop".
````bash
git clone --branch <nombre_rama>
````
--single-branch se utiliza junto con --branch para clonar solo la rama especificada en lugar de todas las ramas del repositorio.
````bash
git clone --single-branch
````