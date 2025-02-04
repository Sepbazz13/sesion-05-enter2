# Sesion 6

## ¿Qué hacen los siguientes comandos?
pwd: Muestra la ruta del directorio de trabajo actual.

ls: Lista los archivos y directorios en el directorio actual.

cd: Cambia el directorio de trabajo actual a otro directorio.

mkdir: Crea un nuevo directorio.

touch: Crea un nuevo archivo vacío o actualiza la fecha de modificación de un archivo existente.


## ¿Puedes explicar qué sucede en el siguiente escenario si ingresas estos comandos y argumentos en la línea de comandos? (Los argumentos son instrucciones adicionales dadas a un comando).
cd projects: Cambia al directorio llamado "projects".

mkdir new-project: Crea un nuevo directorio llamado "new-project" dentro de "projects".

touch new-project/newfile.md: Crea un nuevo archivo vacío llamado "newfile.md" dentro de "new-project".

cd ..: Retrocede un nivel en la jerarquía de directorios (vuelve al directorio padre de "projects").

ls projects/new-project: Lista los archivos y directorios dentro de "new-project". Deberías ver "newfile.md".

## ¿Qué comando usarías en la terminal para listar todos los archivos, incluidos los archivos ocultos, en un directorio de Linux o macOS? Explica qué significan los parámetros utilizados en el comando.
-a: Lista todos los archivos, incluidos los archivos ocultos (aquellos cuyo nombre comienza con un punto .).

Esta opción permite ver archivos que normalmente están ocultos en el sistema de archivos, como archivos de configuración y directorios importantes. Por ejemplo, archivos como .bashrc, .gitignore y otros que no aparecen con un simple ls.