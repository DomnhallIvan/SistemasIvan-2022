#Iván Paniagua Maldonado

Este repositorio tiene las prácticas y entregas de la materia de Sistemas Operativos y Redes.

## Prácticas de Parcial 1

 - [Práctica1](./Eivan.md)
 - [Práctica2](./TareaShida.md)

 - [Práctica 4](https://github.com/DomnhallIvan/Algo)

 - [Práctica 1 2Parcial](https://github.com/DomnhallIvan/SistemasIvan-2022)

 Prueba Prueba al vivo y en directooo
 
 Versión 1.0.0 Agregada

# Repaso de Preguntas Markdown
 
 1. ¿Cómo se inicializa un repositorio en Git?
    - Lo primero que tenemos que hacer es crear una carpeta en la que guardaremos nuestro repositorio por medio del comando mkdir. Si estamos en gitbash nos cambiamos a esa carpeta con el comando cd. Después podemos crear un README.md y gitignore por medio del comando touch, son preferibles aunque no sean necesarios, lo que si es necesario es después utilizar el comando git init para ahora si inicializar el repositorio.
    - ~~~
 
      git mkdir #carpeta donde guardaremos la carpeta del repositorio
      git cd #Nos redirije a la carpeta que seleccionemos, en este  caso la que creamos
      git touch README.md  (Preferiblemente)
      git touch .gitignore (Preferiblemente)
      git init (Inicializa el repositorio en Git)

      ~~~

 1. ¿Cómo creas un repositorio en GitHub?
    -  Te vas a la página de Github, te vas a la parte de "Tus repositorios" y desde ahí seleccionas la opción de "New Repository" el cuál creará un nuevo repositorio

    - ![Paso 1](https://cdn.discordapp.com/attachments/1012736848797380690/1021807372307546172/unknown.png)
    - ![Paso 2](https://cdn.discordapp.com/attachments/1012736848797380690/1021807465387536444/unknown.png)


 1. ¿Cómo vinculas un repositorio local de Git con uno remoto en GitHub?
     - ~~~
 
       git remote add origin https://github.com/usuario/repositorio.git.ejemplo (Aquí añadimos la dirección del repositorio de Github en el repositorio Git)

       ~~~

 1. ¿Cuál es el flujo básico de trabajo en Git y GitHub?
     - ~~~
 
       git add .  (Sirve para añadir un cambio en el entorno local)
       git commit -m "Escribe el nombre del commit" (Sirve para para añadir los cambios que vas a pasar de local a remoto)
       git push (Sirve para subir dichos cambios al repositorio remoto)

       git pull (Sirve para descargar cambios del repositorio remoto al local)

       ~~~