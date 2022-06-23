# Resolución de los ejercicios de la práctica de GIT

## ¿Qué comando utilizaste en el paso 11? ¿Por qué?

*git reset --hard HEAD~1 , añado el --hard para perder los cambios en el working copy y el HEAD~1 para volver al commit anterior.*

## ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?

*git reflog para saber el identificador del commit al que quiero ir. Despues git reset --hard + identificador para volver al commit en el que estaban los archivos modificados.*

## El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

*No, porque el archivo solo se modifico en una rama.*

## El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?

*Sí, porque las dos ramas han modificado el mismo archivo.*

## El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?

*No, porque es fast forward*

## ¿Qué comando o comandos utilizaste en el paso 25?

*git log --graph o git log --graph pretty=oneline para comprimir el gráfico*

## El merge del paso 26, ¿Podría ser fast forward? ¿Por qué? 

*Sí, porque dentro del diagrama las dos ramas formaban parte de la misma lista*

## ¿Qué comando o comandos utilizaste en el paso 27? 

*git reset HEAD~1*

## ¿Qué comando o comandos utilizaste en el paso 28? 

*git restore git-nuestro-md*

## ¿Qué comando o comandos utilizaste en el paso 29?

*git branch -D title, porque al deshacer el merge no se puede con -d porque la rama no esta totalmente 'mergeada'*

## ¿Qué comando o comandos utilizaste en el paso 30? 

*git reflog para buscar la referencia del commit y git reset --hard + referencia para ir al commit*

## ¿Qué comando o comandos usaste en el paso 32?

*git checkout + referencia del primer commit*

## ¿Qué comando o comandos usaste en el punto 33?

*git checkout + referencia del commit donde pongo el título al archivo* 
