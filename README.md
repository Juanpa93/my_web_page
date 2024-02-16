git init: Inicializa un nuevo repositorio Git en un directorio local.
git add .: Agrega todos los archivos modificados y nuevos al área de preparación (staging area) de Git.
git commit -m 'mensaje commit': Guarda los cambios confirmados en el repositorio local con un mensaje descriptivo.
git push: Lleva los cambios confirmados al repositorio remoto.
git checkout -b new_features: Crea una nueva rama llamada new_features y se mueve a ella.
git checkout main: Se mueve a la rama principal del repositorio.
git merge new_features: Fusiona los cambios de la rama new_features a la rama actual.
git push origin main: Lleva los cambios de la rama principal al repositorio remoto.
git reset --soft 'hash': Mueve la rama actual y la cabecera al commit especificado, manteniendo los cambios en el área de preparación.
git status: Muestra el estado actual del repositorio, incluidos los cambios pendientes, los archivos sin seguimiento y más.
