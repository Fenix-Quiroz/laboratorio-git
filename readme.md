# Laboratorio Git

1. Primero creamos una carpeta.
![Imagen](./content/crear-carpeta.png)

2. Abrimos la carpeta con **"Visual Estudio Code"**.


3. Creamos un archivo **"readme.md"**.
![Imagen](./content/readme.png)


4. Creamos un **"repositorio"** en **"GitHub"**.
![Imagen](./content/crear-repo.png)


5.  Volvemos al ***Visual Studio Code*** y en la terminal realizamos un **"git init"** , agregamos el archivo ***readme.md*** con **"git add"** ,hacemos un **"commit"** y conectamos con el repositorio que creamos en GitHub haciendo **"git remote add origin"**.
![Imagen](./content/iniciar-git.png)


6. Hacemos un **"git push"**.
![Imagen](./content/primer-push.png)


7. Creamos un archivo y agregamos unos **"console.log()"**.
![Imagen](./content/crear-archivo.png)


8. Agregamos el nuevo archivo con **"git add"** , hacemos el **"commit"** y un **"git push"** para subir el nuevo archivo al repositorio de **"GitHub"**.
![Imagen](./content/subir-nuevo-archivo.png)


 ### Creando la rama DEVELOPMENT
 1. Creamos la nueva rama con ***"git branch development"*** , cambiamos de la rama **"main"** a la rama **"development"** que acabamos de crear haciendo un ***"git checkout development"***.
![Imagen](./content/nueva-rama.png)


2. Un vez  que cambiamos de rama modificamos el **"arcivo.js"**.
![Imagen](./content/modificar-archivo.png)


3. Hacemos un **"git add"** y un **"commit"**.
![Imagen](./content/add-nueva-rama.png)


4. Haceamos un ***"git push"*** para subir los cambios de la nueva rama a ***GitHub***.
![Imagen](./content/nueva-rama-push.png)

5. Como paso final volvemos a la rama **main**  con ***git checkout main*** y en esa rama hacemos un ***git merge development*** para traernos lo que hicimos en esa rama y tenerlos en **main**.
![Imagen](./content/merge.png)

Y finalmente asi quedaría nuestro repositorio en **GitHub**.
![Imagen](./content/vista-github.png)