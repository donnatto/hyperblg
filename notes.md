# Git y Github

- git add: Agrega archivos al staging area
- git rm: Los remueve del staging area
- git checkout: Trae cambios del commit especifico a carpeta

- git rebase: Pega los cambios en la rama que indiquemos haciendo de cuenta que sigue una historia lineal. (Mala practica)

- git stash: Guarda los cambios en un stash y vuelve al commit anterior
- git stash list: Lista los WIP de los stashs.
- git stash pop: Nos trae los cambios del stash.
- git stash branch \<branchname\>: Trae los cambios a un branch nuevo y nos mueve a dicho branch.

- git clean: Limpia el proyecto de archivos no deseados.

- git cherry-pick: \<commit\> Trae un commit especificado al head de un branch. (Mala practica)

- git commit --amend: Cambios al commit anterior sin crear un commit nuevo.

- git reflog: Referencia los logs.

- git reset --soft \<commit\>: Devuelve al commit indicado sin eliminar los cambios.
- git reset --hard \<commit\>: Devuelve al commit indicado eliminando todos los cambios.

- git grep: buscar contenido dentro de nuestro repositorio

- git shortlog: commits por persona.
<!-- parametros -sn --all --no-merges -->

- git blame: informacion de los cambios linea por linea.
- git branch -a: lista todos nuestros branches sean locales o remotos.
