# Configurar GIT

## git config 
> Creamos Usuario y Email para configurar el Github tambien

    git config --global user.name "w3schools-test"
    git config --global user.email "test@w3schools.com"

## git init: inicia y crear el Git
> Creamos el .git 
>> Una vez creado la carpeta en donde se guardara los archivos de forma local creamos el .git

    git init 


# Guardar el primer archivo en GIT

> Primero debemos crear nuestro archivo 
>>Por ejemplo:
    index.html

## git status: Verificar estado de los cambios si se cambiaron
> Para verificar si el archivo se guardo o no usamos el git status

    git status

>> Si marca los archivos en rojo significa que no se guardo en el repositorio

## Git Add: Preparando tus Cambios para Guardarlos

>Le dices al Git qué cambios quieres llevar contigo utilizando git add. Es como decir "Estos cambios son importantes, así que quiero llevarlos".

    git add .    ---> Esto lleva todo o usando git --all
    git add index.html   ---> O puedes seleccionar el archivo que quieres llevar

## Git commit: 
>Desde que terminamos nuestro trabajo, estamos listos para pasar de stage a commit para nuestro repositorio.
>Agregar confirmaciones realiza un seguimiento de nuestro progreso y cambios a medida que trabajamos. Git considera cada punto de cambio de confirmación o "punto de guardado". Es un punto del proyecto al que puedes volver si encuentras un error o quieres hacer un cambio.

    git commit -m "Mi primer commit"

>> Un atajo que puedes guardar de forma rapida es usando el '-a' para no tener que escribir el ' git add ' pero solo funciona con los archivos que fueron creados al principio, si creo un nuevo archivo, este comando no sirve ya que no selecciona los archivos nuevos 

    git commit -a -m "Updated index.html with a new line"

>>> Listo! una vez creado el commit ya tenes tu "primera" versión de codigo
>>> Recordar que antes de usar el commit tienes que usar el git add .

## Git branch:
>Este comando crea las nuevas ramas 
    git branch nombre_de_la_rama

>> Si escribimos "git branch" solo, nos muestra todas las ramas disponibles o creadas

    git branch
    *main
    master

