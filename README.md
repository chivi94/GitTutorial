# GitTutorial
Tutorial básico de git en el que se incluyen comandos básicos, gestión de ramas y gitflow.

## Comandos básicos para el uso de git.

En este apartado se verán los comandos más básicos para poder hacer un uso sencillo de git a través de terminal. Estos comandos son:

- git clone nombreRepositorio: Dentro de nuestra máquina local, usaremos este comando para clonar un repositorio remoto ya creado.
- git init: En la ruta que hayamos elegido dentro de nuestra máquina, este comando iniciará un repositorio git.
- git remote add origin nombreRepositorio: Una vez iniciado en local el repositorio, y habiendo creado uno remoto (en GitHub o BitBucket, por ejemplo) usaremos este comando para añadir a nuestro repositorio local un origen, es decir, una centralización del código. Cabe destacar que podremos añadir todos los que queramos, para tener varias copias de nuestro código en distintos orígenes.
- git status: Nos da información de los archivos que se encuentran en nuestro repositorio.
- git add * : Añade para poder enviar al origen todos los ficheros que se encuentren en el respositorio local. Si se quiere añadir uno específico, tendremos que especificar el nombre del mismo.
- git commit -m "Mensaje": Con este comando añadiremos los cambios, preparados para ser enviados al repositorio remoto.
- git push origin ramaDestino: Realizando esto, confirmaremos los cambios realizados y los enviaremos al repositorio remoto, a la rama deseada, especificada cómo "ramaDestino".
- git pull origin ramaDestino: Nos trae cambios desde el repositorio remoto al repositorio local.
- git branch: Nos da información sobre las ramas que tenemos en nuestro repositorio local.
  - git branch nombreRama: Crea una nueva rama llamada nombreRama
- git checkout rama: Nos desplaza a la rama especificada.
  - git checkout -b nombreRama: Crea una nueva rama llamada nombreRama y nos desplaza a ella.
- git merge nombreRama: ¡CUIDADO! Esto fusiona la rama nombreRama dentro de la rama en la que nos encontramos actualmente. Se debe poner atención a los posibles conflictos que surjan entre los ficheros que se llamen igual y que hayan sufrido cambios distintos en las mismas líneas.
