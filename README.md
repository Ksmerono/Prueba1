# Prueba1
## Aqui encontrareis comandos de como funciona git
-CONFIGURAR GIT:
~~~
git config --global user.email correoelectronico
~~~
-CREAR NUEVO REPOSITORIO:
~~~
git init
~~~
-AGREGAR ARCHIVOS A STAGING AREA:
~~~
git add temp.txt
~~~
-CREAR COPIA LOCAL:
~~~
git clone url
~~~
-AGREGAR A LOCAL REPOSITORY:
~~~
git commit –m “mensaje”
~~~
-VER LISTA DE ARCHIVOS CAMBIADOS Y AÑADIDOS:
~~~
git status
~~~
-ENVIAR CAMBIOS DE RAMA PRINCIPAL DE LOS REPERTORIOS REMOTOS:
~~~
git push origin nombrerama
~~~
-CAMBIAR ENTRE RAMAS O CREARLAS:
~~~
git checkout nombrerama
~~~
-CONECTARSE A REPOSITORIO REMOTO:
~~~
git remote add origin <dirección>
~~~
-MUESTRA EL REPOSITORIO REMOTO EN EL QUE SE ESTA CONECTADO:
~~~
git remote -v
~~~
-LISTAR, CREAR O BORRAR RAMAS:
~~~
git branch
git Branch -d nombrerama
~~~
-FUSIONAR CAMBIOS REALIZADOS EN EL REPOSITORIO LOCAL:
~~~
git pull
~~~
-FUSIONAR RAMA CON OTRA RAMA ACTIVA:
~~~
git merge <nombrerama>
~~~
-VER CONFLICTOS EN RAMAS:
~~~
git diff
~~~
-HACER ETIQUETAS TAG PARA MARCAR UN COMMIT EN UNA RAMA 
~~~
git tag <idtag>  <commit ID>
~~~
-LISTAR LOS COMMIT GENERADOS DE UNA RAMA
~~~
git log
~~~
-RESETEAR INDEX Y EL DIRECTORIO AL ULTIMO ESTADO
~~~
Git reset - -hard HEAD
~~~
-MOSTRAR INFORMACIÓN DE UN OBJETO GIT
~~~
git show
~~~
-PERMITE BUSCAR OBJETOS DE UN REPOSITORIO REMOTO QUE NO ESTA EN LOCAL
~~~
git fetch origin
~~~
-DESCARGAR RAMA DEL REMOTO
~~~
git checkout -b nombre_del_branch origin/nombre_del_branch
git pull origin nombre_del_branch
~~~
-PARA REVERTIR
~~~
git revert origin nombrerama
git revert HEAD lo hace para revertir el commit
~~~
-PARA ELIMINAR UN ARCHIVO QUE NO QUIERO SUBIR
~~~
git reset HEAD nombre.extensiongit
~~~
-PARA CREAR UN STASH CUANDO TENEMOS ARCHIVO A MEDIAS
~~~
git stash
~~~
-LISTAR STASH
~~~
git stash list
~~~
-RECUPERAR DATOS DE STASH
~~~
git stash show -p stash@{0}
~~~