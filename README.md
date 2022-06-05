<!-- La siguiente estructura te permite añadir una imagen en tu documentación-->
<picture>
  <img alt="Shows an illustration of git and github ." src="https://res.cloudinary.com/practicaldev/image/fetch/s--08RY4_Yg--/c_imagga_scale,f_auto,fl_progressive,h_420,q_auto,w_1000/https://dev-to-uploads.s3.amazonaws.com/i/1o8inq8110mxvqyls276.png">
</picture>


# Aprendiendo git | Comandos básicos

```
git --verision
```
El comando `git --version` sirve para conocer la versión de git que tenemos instalada en nuestro sistema operativo MacOS/Windows/Linux

```
git init
```
El comando `git init` nos permite crear un nuevo repositorio de Git. Puede utilizarse para convertir un proyecto existente y sin versión en un repositorio de Git, o para inicializar un nuevo repositorio vacío. La mayoría de los demás comandos de Git no se encuentran disponibles fuera de un repositorio inicializado, por lo que este suele ser el primer comando que se ejecuta en un proyecto nuevo.

```
git status
```
El comando `git status` muestra el estado actual del directorio de trabajo (**working directory**) y el área de preparacion (**staging area**) de git

```
git add <NombreDelArchivo>
```
El comando `git add <FileNames>` ayuda a seleccionar los archivos que desea mover al area de preparacion (**staging area**), marcandolos para que sean incluidos en el proximo commit. Puedes seleccionar todos los archivos, carpetas y archivos especificos.

```
git commit -m "Mi primer commit usando GIT"
```

"Comprometer los archivos", el comando `git commit -m` es como crear un snapshot (**una copia de como se encuentran los archivos en ese momento**) del repositorio. 
Los snapshots son una copia de tu repositiorio en tiempos especificos.
Como recomendación se deben realizar commits a menudo,  para concer el historial de tus cambios.
la opción `-m` te permite añadir un mensaje a tu commit

```
git commit -am "Mi primer commit usando GIT "
```
En adición de incluir un comentario al ejecutar el commit, la opción `-a` te permite omitir la **staging area** e incluirá automaticamente todos los archivos que se encuentren dentro de tu directorio.


#

En la siguiente imagen se observan los tres bloques centrales de Git
- Working directory
- Staging area
- Repository

<picture>
  <img alt="Working directory, Staging area and Repository ." src="https://miro.medium.com/max/1372/1*diRLm1S5hkVoh5qeArND0Q.png">
</picture>

#

```
git log
```
Buscar e inspeccionar la evolución de los archivos del proyecto.
