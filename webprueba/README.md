# GIT
## Convertir tu proyecto en un proyecto controlado por **git**
---
git init
---
## Configurar git *correctamente*
---
git config --global user.email "eloisetej@gmail.com"
git config --global user.name "eloisete"
---
## Prepara los cambios para ser añadidos al repositorio
---
 git add .
---
 ## Guarda los cambios en el repositorio
---
 git commit -m "creo la pagina web inicial"
---


## Conecta el repositorio local con el repositorio remoto
---

git remote add origin https://github.com/eloisete/webpruebacebem.git
---

## Sube los cambios que tienes en local a el repositorio remoto
---
Git push -u origin master