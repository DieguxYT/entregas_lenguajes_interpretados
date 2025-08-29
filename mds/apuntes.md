# Apuntes de la materia

Comandos Básicos de Terminal

pwd - Imprime la ruta del directorio actual (print working directory)
ls - lista los directorios y archivos del directorio donde esta la terminal
ls - l lista detalles de los directorios y archicos
ls -a lista todo tipo de directorio y archivos (incluye los ocultos)
ls -la combinación de ambas flags
clear - limpiar la panralla del terminal
cd: para cambiarnos de directorio
  . desde la ubicación donde estoy
  .. desde la ubicación donde estoy sube un nivel
  ~ es un comodín que nos ubica en la carpeta del home del usuario de la sesión actual
  / es un comodín que nos ubica en la carpeta raíz (root) del equipo de computo
mkdir - crea un directorio
touch archivo.txt - crea un archivo del tipo que le indiquemos
rm - eliminar archivos
rm -r - eliminar directorios
cp ruta-actual ruta-nueva - copiar archivos
mv ruta-actual ruta-nueva - mover archivos

Atajos de VS Code

ctrl + j - Abre la terminal en el editor

alt + shift + ⬆︎ o ⬇︎ - duplica líneas de código

alt + shift + a - comentarios en VS Code


# Encabezado nivel 1

## Encabezado nivel 2

### Encabezado nivel 3

#### Encabezado nivel 4

##### Encabezado nivel 5

###### Encabezado nivel 6


Para poner **negrita** debes encerrar el texto entre doble asterísco

Para poner _cursiva_ debes encerrar el texto entre guines bajos

Para poner _**cursiva y negrita**_ debes encerrar el texto entre guines bajos


Estos comandos los vas a ejecutar una sola vez, después de que hayas instalado _**git**_ en tu computadora.

```bash
git --version
git config --global user.name "Jonathan MirCha"
git config --global user.email jonmircha@gmail.com
git config --global user.ui true
git config --global init.defaultBranch main
git config --list
# asignando visual studio code como editor de configuración de git
git config --global core.editor "code --wait"
git config --global -e
# para estandarizar los saltos de línea en windows
git config --global core.autocrlf true
# para estandarizar los saltos de línea en linux/mac
git config --global core.autocrlf input
# ver todas las opciones de la configuración en la terminal
git config -h
# ver todas las opciones de la configuración en el navegador
git help config
```