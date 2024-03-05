# Git Status
El comando git status muestra el estado del árbol de trabajo

Para proporcioanr el resultado en formato corto.
````bash
git status -s 
git status --short
````
Muestra la sucursal y la información de seguimiento incluso en formato breve.
````bash
git status -b 
git status --branch
````
Muestra el número de entradas actualmente guardadas.
````bash
git status --show-stash
````
Proporcione el resultado en un formato fácil de analizar para scripts. Esto es similar al resultado breve, pero permanecerá estable en todas las versiones de Git e independientemente de la configuración del usuario.
````bash
git status --porcelain[=<version>]
````
Proporcione el resultado en formato largo. Este es el valor predeterminado.
````bash
git status --long
````
Además de los nombres de los archivos que se han modificado, también muestra los cambios textuales que están preparados para confirmarse (es decir, como la salida de git diff --cached). Si -vse especifica dos veces, también muestra los cambios en el árbol de trabajo que aún no se han preparado (es decir, como la salida de git diff).
````bash
git status -v
git status --verbose
````
El parámetro de modo se utiliza para especificar el manejo de archivos sin seguimiento.
````bash
git status -u[<mode>]
git status --untracked-files[=<mode>]
````
Ignore los cambios en los submódulos cuando busque cambios. <cuando> puede ser "ninguno", "sin seguimiento", "sucio" o "todos", que es el valor predeterminado. El uso de "ninguno" considerará modificado el submódulo cuando contenga archivos modificados o sin seguimiento o su HEAD difiera de la confirmación registrada en el superproyecto y se puede usar para anular cualquier configuración de la opción ignorar en git-config[1] o gitmodules[ 5] 
````bash
git status --ignore-submodules[=<cuando>]
````