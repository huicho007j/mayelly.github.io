# Acordeón Git

### $ git init
  * Inicializa un nuev repositorio.
 
### $ git status
        -Muestra el estado actual de nuestro repositorio, nos permite saber si el repositorio contiene archivos de seguimiento, o si estan listos para estar registrados.

### $ git touch
   crear nuevo archivo
### $ git add
  Este comando empieza a seguir a uno o más archivos generando un nuevo estado de nuestro proyecteo
 la bandera -A agrega a todos los arhivos del repsitorio

### $ git add <archivo> | -A
 - prepara un arcivos para nuevas etapas.
 
### $ git commit (-m "descripcion)
  -Este comando registra nuestro nuevo estado y lo registra en la historia de nuestro repositorio.
Por lo general este comando s eusa con la bandera -m  y un pequeño texto que describa lo q hicimos.

## $ git log (--oneline <archivo>)
- Este comando nos muesta el historial de comits que hemos hecho en nuestro proyecto.
        - La bandera --oneline muestra cada entrada en una sola línea.
        - También es posible ver historia de un solo archivo, pasando como argumento el nombre de éste.
        
-Muestra el historial completo de commits del repo, o de un archivo si se especifica.

###  .gitignore
- Este archivo nos permite ignorar archivos o directorios los cuales no queramos que entren en el seguimiento de nuestro repositorio.
        - nombres de archivos o carpetas
        - Wildcards * (extensiones)

### $ git checkout
-Este comando nos permite movernos entre commits o incluso ramas de nuestro repositorio.
        -Lleva como argumento el id del commit o parte de.
        
### $ git revert
-Este comando nos revierte un cambio ya registrado, creando un nuevo comit.
        -Lleva como argumento el id del commit a revertir.
## $ git resert

-Regresa al último estado guardado, borrando permanentemente cualquier cambio en el área de pruebas
    -lleva la bandera --hard
## $ git clean 
-Borra permanentemente los archivos no seguidos.
    -lleva la bandera  -f
    
        