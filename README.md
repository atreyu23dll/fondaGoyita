Este es un tutorial de como hacer actualizaciones del proyecto

1. Actualizar tu repositorio local (siempre antes de empezar):

git pull origin main


2. Crear una rama nueva para cada funcionalidad

git checkout -b nombre-de-la-nueva-funcionalidad

3. Desarrollar tu código:
Edita/crea los archivos necesarios
Guarda los cambios

5. Agregar los cambios al área de staging:

# Para agregar todos los archivos modificados:
git add .

# O para agregar archivos específicos:
git add nombre-archivo.js

6. Hacer commit de los cambios:

git commit -m "Descripción clara y concisa de los cambios"

7. Subir los cambios a GitHub:

# Si estás en una rama nueva:
git push -u origin nombre-de-la-nueva-funcionalidad

# Si estás en la rama main:
git push origin main

####### comandos utiles #############

# Ver el historial de commits
git log

# Ver cambios específicos de un archivo
git diff nombre-archivo

# Descartar cambios en un archivo (antes de hacer add)
git checkout -- nombre-archivo

# Ver las ramas disponibles
git branch

# Cambiar entre ramas
git checkout nombre-rama

# Actualizar tu rama local con los últimos cambios de GitHub
git fetch origin
git merge origin/main
