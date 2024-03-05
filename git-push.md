# Git Push
Sube los commits locales de la rama actual al repositorio remoto asociado.
````bash
git push origin main
````

Sube los commits de la rama especificada al repositorio remoto especificado.
````bash
git push origin feature_branch
````

Fuerza la actualización remota con la rama local, sobrescribiendo el historial remoto. Debería usarse con precaución, ya que puede causar la pérdida de datos.
````bash
git push --force origin main
````
