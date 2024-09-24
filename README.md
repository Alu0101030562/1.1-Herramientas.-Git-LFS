# 1.1 Herramientas. Git LFS

## 1.Crea una carpeta  que incluya 2 imágenes y 3 ficheros de texto. La utilizaremos para crear un repositorio Git que se conecte a GitHub. Puedes utilizar comandos o una herramienta visual. Las imágenes deben tener seguimiento LFS. Añade una imagen adicional y un fichero adicional y actualiza el repositorio GitHub con la nueva versión del proyecto.

Lo primero que haremos sera crear el repositorio. Tenemos distintas opciones, desde el propio github, mediante comandos de git o desde la aplicación de escritorio de github, en este caso se ha utilizado la aplicación de escritorio.

![repositorio1](https://github.com/Alu0101030562/Screenshots/blob/main/Screenshots/1.1GitLfs/creacionRepositorio1.1.PNG)

Una vez creado el repositorio, ya podremos añadir las dos imágenes y los tres ficheros de texto solicitados y, tras haberlos añadido, podremos hacer un **commit** y un **push** del repositorio para actualizar los cambios realizados.

![commit1](https://github.com/Alu0101030562/Screenshots/blob/main/Screenshots/1.1GitLfs/primerCommit.PNG)

Tras haber realizado los cambios, instalaremos Git LFS para hacer un seguimiento de los archivos con extension ``.jpg`` mediante linea de comando en una terminal de git.

```
git lfs install
```
```
git lfs track "*.jpg"
```
```
git lfs track
```

![gitlfs1](https://github.com/Alu0101030562/Screenshots/blob/main/Screenshots/1.1GitLfs/gitLfsInstall.PNG)

Tras hacer el seguimiento de Git LFS, añadiremos otra imagen y otro fichero de texto y guardaremos los cambios con un **commit** y haremos un **push** para actualizar el repositorio con los cambios realizados.

![commit2](https://github.com/Alu0101030562/Screenshots/blob/main/Screenshots/1.1GitLfs/ficherosAdicionales.PNG)

## 2. Crea un repositorio Git LFS para el proyecto Unity de la tarea 1.2. Configura el fichero .gitattribute adecuado. Una segunda versión del fichero debe incluir una textura y un segundo script que muestre el mensaje en consola "Script tarea 1.2". Obtener capturas de pantalla del proceso para realizar la entrega de la práctica.

Ahora, haremos lo mismo que en el punto anterior, crearemos un repositorio para la tarea 1.2 con un fichero ``.gitignore'' de Unity y una vez creado, añadiremos el proyecto hecho en Unity.

![repositorio2](https://github.com/Alu0101030562/Screenshots/blob/main/Screenshots/1.1GitLfs/creacionRepositorio1.2.PNG)

De nuevo, instalamos git LFS y tendremos que añadir un nuevo script y una textura a la cual haremos seguimiento.

![gitlfs2](https://github.com/Alu0101030562/Screenshots/blob/main/Screenshots/1.1GitLfs/gitLfsInstall1.2.PNG)

Seguido de esto, haremos un seguimiento de las carpetas ``StarterAssets`` y ``Sci-fi Styled Module Pack`` para tener el fichero ``.gitattribute`` adecuado.

![gitlfs3](https://github.com/Alu0101030562/Screenshots/blob/main/Screenshots/1.1GitLfs/creacionRepositorio1.2.2.PNG)

En el script tiene que mostrar el mensaje "Script tarea 1.2" al ejecutar el juego.

![juego](https://github.com/Alu0101030562/Screenshots/blob/main/Screenshots/1.1GitLfs/1.2%20programa%20final.PNG)

Repositorio donde se ha creado la [practica 1.2](https://github.com/Alu0101030562/1.2-Entorno-Unity-3D)
