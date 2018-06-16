#¿Qué comando utilizaste en el paso 11? ¿Por qué? 
```Git reset –hard HEAD~1```, indicando –hard borra todos los cambios realizados en el working copy, no hacerlo mantiene los cambios pero igualmente deshace el último commit
#¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué? 
Primero ```git reflog``` para ver el histórico de actuaciones realizadas sobre git.
Buscamos el identificador del commit que publicamos anteriormente y ejecutamos ```git reset –hard  2f7719e``` 
#El merge del paso 13, ¿Causó algún conflicto? ¿Por qué? 
No, porque estamos en la rama “styled” y esta ya contenía todos los commits de la rama que absorbe.
#El merge del paso 19, ¿Causó algún conflicto? ¿Por qué? 
Si, porque ambos tenían commits diferentes sobre el mismo fichero el cual fue modificado en ambas ramas.
#El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?, 
No, porque  master no sufrío ningun cambio en su  working copy y todos sus commits estaban contenidos en la rama styled.
#¿Qué comando o comandos utilizaste en el paso 25? 
```git log --graph --decorate --pretty=oneline```
#El merge del paso 26, ¿Podría ser fast forward? ¿Por qué? 
Si, por que la lista de  commits de las rama styled contenían toda la lista de commits de la rama master.
#¿Qué comando o comandos utilizaste en el paso 27? 
```git reset HEAD~1```
#¿Qué comando o comandos utilizaste en el paso 28?
```git checkout -- git-nuestro.md````
#¿Qué comando o comandos utilizaste en el paso 29? 
```git branch -D title```
#¿Qué comando o comandos utilizaste en el paso 30?  
```git reflog 
git reset --hard 2cb5757```
#¿Qué comando o comandos usaste en el paso 32? 
```git reflog 
git checkout c7068d0```
#¿Qué comando o comandos usaste en el punto 33? 
```git reflog 
git reset --hard 2cb5757```

