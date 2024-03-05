# Git Add
El comando git add agrega un archivo específico al área de preparación para que sus cambios sean registrados en el próximo commit.
````bash
git add <file>
````
El comando git add . o git add --all agrega todos los archivos modificados, eliminados y nuevos al área de preparación. Esto incluye archivos en subdirectorios.
````bash
git add .
````
````bash
git add --all
````
El comando git add -u o git add --update agrega al área de preparación los cambios en archivos ya seguidos por Git (es decir, archivos que ya han sido añadidos anteriormente), pero no los nuevos archivos.
````bash
git git add -u
````
````bash
git add --update
````