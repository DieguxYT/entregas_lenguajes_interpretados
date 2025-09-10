# Examen Primer Parcial
#### ¿QUE ES Y PARA QUE SIRVE VISUAL STUDIO CODE?
es un editor de codigo sirve para generar codigo fuente.
#### ¿Qué es y para qué sirve la Terminal de Comandos?
es una herramienta para usar la computadora atravez de texto
#### ¿Qué es y para qué sirve Markdown?
es un lenguaje para dar forma a los textos
#### ¿Qué es y para qué sirve Git?
sirve para hacer los cambios de archivos desde su terminal
#### ¿Qué es y para qué sirve GitHub?
es una pagina que sirve para administrar y editar proyectos solo o con un equipo
#### ¿Para qué sirven los siguientes comandos: pwd, whoami, touch, mkdir, cp, mv, ls, clear, cd y rm?
```bash
pwd Enseña la ruta del directorio o carpeta
whoami muestra informacion del usuario
toch crea un archivo en una carpeta
mkdir crea un directorio o carpeta
cp copia archivos
mv mueve archivos y carpetas
ls lista los archivos y las carpetas
clear borra todo de tu terminal
cd cambia de directorio o carpeta
rm elimina archivos y carpetas
```

#### ¿Qué significan los siguiente caracteres en la terminal de Comandos: ./, ../, /, y ~?
```bash
./ ejecuta un archivo
../ mueve la carpeta principal
/ indica la raiz del sistema
~ representa la carpeta o el usuario
```
#### ¿Cómo se inicializa un repositorio en Git?
```bash
git init
```
#### ¿Cómo creas un repositorio en GitHub?
vas a la pagina de github, creas un nombre para el repositorio, y le das en crear repositorio
#### ¿Cómo vinculas un repositorio local de Git con uno remoto en GitHub?
```bash
git init
git add .
git commit -m "Primer commit"
git branch -M main
git remote add origin https://github.com/usuario/repositorio.git
git push -u origin main
```
#### ¿Cuál es el flujo básico de trabajo en Git y GitHub?, explicalo indicando la secuencia de comandos.
```bash
git add .
git commit -m "crenado commit"
git push
```
#### ¿Para qué sirve el archivo .gitignore?
sirve para igorar o no mostrar los archivos que quieras 
#### ¿Cuál es el propósito de una rama?
es editar la rama principal sin perder la info de la rama principal
#### ¿Qué es una fusión?
es la comvinacion de todas las ramas en la rama main
#### Explica los diferentes tipos de fusión que existen.
Fast-Forward: es cuando la fision se hace automatica
Manual Merge: es cuando la fusion debes hacerla de manera manual
#### ¿Cómo puedes ver el historial de tu repositorio?
```bash
git log
```
#### ¿Cuál es el propósito de una etiqueta?
poner la version del actualizacion del repositorio
