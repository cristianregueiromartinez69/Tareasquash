#Pasos para hacer el merge con el squash

**Tareas del lider**

1. El líder crea un repositorio en git hub al cual mandara sus commits
2. Hace 2 commits en la main y hace el push
3. pone a su compañero desarrollador de colaborador
4. hace una nueva clase con un nombre descriptivo
5. crea y hace checkout a una nueva rama
6. hace unos commits en la nueva clase creada pero sin hacer el push

**tareas del colaborador**

1. Clona el repositorio en el que es colaborador
2. hace una clase con un nombre descriptivo 
3. hace una nueva rama y checkout a la rama
4. hace 3 o los commits que quiera en la nueva clase
5. hace el push al repositorio remoto

**tareas del lider**

7. hace el fetch una vez que el colaborador hizo su push

***Momento del squash***

1. hace el merge squash de la rama del colaborador 
2. commit para confirmar los cambios
3. hace un squash de la rama lider
4. commit para confirmar los cambios
5. Una vez está todo hecho, hacemos un push y tendremos todos los cambios en el repositorio remoto

***finalidad del squash***

La finalidad del merge squash es que la rama main esté lo más libre posible y con el menor numero de commits
