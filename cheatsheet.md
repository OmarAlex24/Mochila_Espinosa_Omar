# Cheatsheet de comandos de git

## Configuracion

>git config --global user.name 
> -Ingresar tu nombre de Github

>git config --global user.email 
> -Ingresar tu corre de Github

## Creacion de repositorios

>git init  
> -Inicializa el repositorio localmente

>git clone  
> -Clona el repositorio ingresado

## Realizar cambios

>git status  
> -Muestra el estado del directorio/repositorio

>git show  
> -Muestra objetos

>git add  
> -Añade archivos al staging area

>git commit  
> -Añade los archivos del staging area a la rama actual y añade un comentario

>git diff  
> -Muestra todos los archivos con cambios

>git reset   
> -Regresa los cambios al anterior commit

## Ramas

>git branch "nombre_rama"  
> -Crea una nueva rama

>git branch -d  
> -Elimina la rama

>git branch --list  
> -Enlista las ramas

>git branch -m  
> -Renombra la rama

### Cambiar ramas

>git checkout  
> -Cambia de rama

>git checkout -b  
> -Crea una nueva rama y cambia a ella

### Fusionar ramas

>git merge  
> -Fusiona una rama con la actual


## Push y pull

>git push  
> -Transferencia de datos a el repositorio remoto

>git pull  
> -Extrae datos del repositorio remoto para integrar en el local

## Registro

>git log  
> -Mostrar todos los commits de una rama

