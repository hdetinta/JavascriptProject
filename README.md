1.Crear un repositorio en local:
Empezando por crear una carpeta con el nombre del repositorio y dentro de la carpeta ejecutamos desde el terminal "git init"

2.Subir el repositorio a GitHub
Creamos el repositorio en GitHub y con la url para vincular el repositorio a local, utilizamos " git remote add origin https://github.com/hdetinta/JavascriptProject.git "
Confirmamos que ha funcionado utilizando el comando " git remote -v" desde el terminal.

3.Hacer un commit y un push
Creamos: Archivo1.md y lo añadimos al staging usando "git add ." (ya que no hay nada que no deba añadirse) 
Una vez añadido ejecutamos 'git commit -m "Creación de fichero readme" '
Subimos los cambios a GitHub utilizando ' git push '

4.Crear una rama
Creamos una rama utilizando ' git branch -m "development"'
Cambiamos a la rama utilizando ' git checkout "development"'
Modificamos el fichero añadiendo líneas de texto para generar cambios. 
Ejecutamos 'git add .' y después 'git commit -m "Cambios en el fichero con descripción del paso 4"'
Y terminamos con 'git push' para registrar los cambios en GitHub

5.Hacer un merge
Cambio desde la rama development a la rama main utilizando el icono para ello en Visual Studio Code (también podría usar 'git checkout "main"' pero me gusta más el botón)
Para fusionar la rama development en la rama main ejecuto ' git merge "development" "main"'
Como no hubo conflictos lo sincronizamso con GitHub con ' git push'