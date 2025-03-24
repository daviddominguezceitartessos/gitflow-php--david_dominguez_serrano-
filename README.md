# gitflow-php--david_dominguez_serrano-

#1 
#He creado el repositorio en GitHub con mi nombre
#git clone https://github.com/daviddominguezceitartessos/gitflow-php-david_dominguez.git
#cd gitflow-php-david_dominguez
#git flow init
#git checkout -b develop
#git push -u origin develop
#git branch -a

#2
#git flow feature start crear-mi-archivo
#// Archivo: alumnos/tu_nombre.php
#echo "Hola, soy [David Domínguez] y estoy aprendiendo Git Flow!";
#git add alumnos/david_dominguez.php
#git commit -m "Añadido archivo PHP con mensaje de presentación"
#git push origin feature/crear-mi-archivo
#git flow feature finish crear-mi-archivo
#git push origin develop
#git log --oneline --graph

#3
#git flow feature start modificar-index
#<?php
#include "alumnos/tu_nombre.php";
#?>
#git diff
#git add index.php
#git commit -m "Incluido archivo PHP en index.php"
#git push origin feature/modificar-index
#git flow feature finish modificar-index
#git push origin develop

#4
#git merge develop
#git status
#Editar manualmente index.php para resolver el conflicto.
#git add index.php
#git commit -m "Resuelto conflicto en index.php"
#git push origin develop


#5
#git flow feature start borrar-mi-archivo
#git rm -f alumnos/david_dominguez.php
#git add .
#git commit -m "Eliminado archivo PHP de alumnos/"
#git push origin feature/borrar-mi-archivo
#git flow feature finish borrar-mi-archivo
#git push origin develop

#6
#git flow release start v1.0
#git flow release finish v1.0
#git push origin main
#git push origin develop
#git tag -a v1.0 -m "Versión 1.0 estable"
#git push origin v1.0


