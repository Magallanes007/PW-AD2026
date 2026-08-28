git clone
Descripción: Descarga e instala una copia local de un repositorio remoto existente alojado en GitHub.
Ejemplo de uso: git clone [https://github.com/usuario/proyecto.git](https://github.com/usuario/proyecto.git)

git status
Descripción: Muestra el estado del directorio de trabajo y del área de preparación (staging area), listando archivos modificados, agregados o no rastreados.
Ejemplo de uso: git status

git add
Descripción: Agrega archivos modificados o nuevos al área de preparación (staging area) para incluir sus cambios en el próximo commit.
Ejemplo de uso: git add index.html (o git add . para incluir todos los archivos)

git commit
Descripción: Guarda permanentemente los cambios cargados en el área de preparación dentro del historial local del repositorio junto a un mensaje descriptivo.
Ejemplo de uso: git commit -m "Añade la barra de navegación principal"

git branch
Descripción: Permite listar, crear o eliminar ramas dentro del repositorio local.
Ejemplo de uso: git branch nueva-funcionalidad

git checkout
Descripción: Alterna entre distintas ramas del proyecto o recupera archivos del historial.
Ejemplo de uso: git checkout main (o git checkout -b nueva-rama para crearla y cambiar a ella de inmediato)

git switch
Descripción: Comando dedicado específicamente a cambiar de rama dentro del repositorio.
Ejemplo de uso: git switch desarrollo

git merge
Descripción: Une el historial de cambios y las confirmaciones de una rama específica dentro de la rama activa actual.
Ejemplo de uso: git merge nueva-funcionalidad

git remote
Descripción: Administra la vinculación entre el repositorio local y el repositorio alojado en la nube en GitHub.
Ejemplo de uso: git remote add origin [https://github.com/usuario/proyecto.git](https://github.com/usuario/proyecto.git)

git push
Descripción: Envía los commits y cambios locales guardados a la rama correspondiente en el repositorio remoto de GitHub.
Ejemplo de uso: git push origin main

git pull
Descripción: Descarga e integra automáticamente los cambios más recientes del repositorio remoto en la rama local donde te encuentras.
Ejemplo de uso: git pull origin main

git fetch
Descripción: Descarga las referencias, cambios y ramas del repositorio remoto en GitHub sin fusionarlos automáticamente con el código local.
Ejemplo de uso: git fetch origin

git log
Descripción: Muestra una lista cronológica con el historial de commits realizados en la rama activa.
Ejemplo de uso: git log --oneline

git diff
Descripción: Muestra la comparación directa de las líneas modificadas entre archivos, áreas de trabajo, commits o ramas.
Ejemplo de uso: git diff

git stash
Descripción: Guarda temporalmente las modificaciones locales no confirmadas en una pila, dejando el área de trabajo limpia para cambiar de tarea sin perder avances.
Ejemplo de uso: git stash (para recuperar: git stash pop)

git reset
Descripción: Revierte el estado del repositorio o despesa archivos del área de preparación a un estado anterior.
Ejemplo de uso: git reset --hard HEAD~1

gh auth login
Descripción: Autentica tu cuenta de GitHub dentro de la terminal mediante GitHub CLI.
Ejemplo de uso: gh auth login

gh repo create
Descripción: Crea un repositorio público o privado directamente en tu cuenta de GitHub utilizando la terminal sin necesidad de abrir el navegador.
Ejemplo de uso: gh repo create mi-nuevo-proyecto --public

gh pr create
Descripción: Crea una solicitud de extracción (Pull Request) en GitHub desde la línea de comandos para proponer cambios a la rama principal.
Ejemplo de uso: gh pr create --title "Corrige error de inicio de sesión" --body "Resuelve la falla al ingresar la contraseña."

git rebase
Descripción: Reorganiza el historial de confirmaciones (commits) de la rama actual aplicándolos uno a uno sobre el estado final de otra rama, creando un historial de trabajo lineal.
Ejemplo de uso: git rebase main
