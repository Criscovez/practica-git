# practica-git
Práctica Git &amp; GitHub

- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
- git reset --hard HEAD~1 // git reset mueve la rama un commit antes del HEAD dejando afuera el ultimo commit, --hard carga el comit en el working copy
- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
- git reset --hard 250bb3c // git reset para volver la rama al commit usando el numero de referencia de reflog
- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
- no, porque la rama styled ya contiene los cambios de main 
- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
- sí, porque tanto htmlify como styled tienen cambios del commit inicial
- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
- No hubieron conflictos, solo se agregó un commit con cambios de styled a main 
- ¿Qué comando o comandos utilizaste en el paso 25?
- git log --graph
- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
- sí, porque no se necesita generar un commit extra
- ¿Qué comando o comandos utilizaste en el paso 27?
- git reset HEAD~1 
- ¿Qué comando o comandos utilizaste en el paso 28?
-  git restore git-nuestro.md
- ¿Qué comando o comandos utilizaste en el paso 29?
- git branch -D title
- ¿Qué comando o comandos utilizaste en el paso 30?
- git reset --hard 4312c54
- ¿Qué comando o comandos usaste en el paso 32?
- git checkout 84aecab    
- ¿Qué comando o comandos usaste en el punto 33?
- git checkout main
