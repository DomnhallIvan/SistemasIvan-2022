# Explicación de comandos B)

## Comandos Por Iván Paniagua Maldonado

---

- pwd
  - Te muestra la ubicación de la carpeta en la que te encuentras. Si aparece únicamente / es porque estas en la carpeta raíz
  ~~~
  
  Verde17@Verde17 MINGW64 /d
  $ pwd
  /d
  
  ~~~
- whoami
  - Te muestra qué usuario esta activo en la computadora
  ~~~
  
  Verde17@Verde17 MINGW64 /d
  $ whoami
  Verde17
  
  ~~~
- help
  - Enseña una serie de comandos que puedes utilizar. Muy útil por si quieres saber que más comandos puedes hacer.

      ![UwU](https://cdn.discordapp.com/attachments/845383920458924034/1014262512885170186/unknown.png)

- cd
  - Te cambia el directorio
  ~~~
  
  Verde17@Verde17 MINGW64 /d
  $ cd /c

  Verde17@Verde17 MINGW64 /c
  $
  
  ~~~

- touch
  - Permite crear archivos en la ubicación donde estes siempre y cuando definas que tipo de archivo vas a crear (.txt por ejemplo). 
  ~~~
  
  user@DESKTOP-ED44C96 MINGW64 /d
  $ touch UWU.txt

  ~~~
  ![OWO](https://cdn.discordapp.com/attachments/845383920458924034/1014285786948042752/unknown.png)



- echo
  - Es utilizado para crear archivos que contengan datos. Por ejemplo :
  ~~~

  user@DESKTOP-ED44C96 MINGW64 /e
  $ echo "Hello There" >GeneralKenobi.txt

  ~~~

  ![GeneralKenobi](https://cdn.discordapp.com/attachments/845383920458924034/1014317664245649479/unknown.png)
- cat
  - Te muestra el contenido todas de un archivo. Para salir de ahí tienes que poner CTRL + C.
  ~~~

  user@DESKTOP-ED44C96 MINGW64 /e
  $ cat leeme.txt
  Asdsdsd


  ~~~
- mkdir
  - Sirve para crear carpetas en el directorio en el que te encuentres actualmente.
  ~~~

  user@DESKTOP-ED44C96 MINGW64 /e
  $ mkdir uwu

  ~~~
   Ejemplo:
  ![Ahhh](https://cdn.discordapp.com/attachments/845383920458924034/1014289506146467940/unknown.png)
- rmdir
  - Sirve para Remover cualquier directorio  que tenga el nombre que especifiques. Ejemplo:
  ~~~
  
  user@DESKTOP-ED44C96 MINGW64 /e
  $ rmdir uwu
  
  ~~~
  ![Ohh](https://cdn.discordapp.com/attachments/845383920458924034/1014285786948042752/unknown.png)
- rm
  - Remueve cualquier archivo que necesites.
  ~~~
  
  user@DESKTOP-ED44C96 MINGW64 /e
  $ rmdir uwu.txt
  
  ~~~
  ![Ehh](https://cdn.discordapp.com/attachments/845383920458924034/1014292816211476501/unknown.png)

- cp
  - Te copia los archivos en otro lugar.
  ~~~
  
  user@DESKTOP-ED44C96 MINGW64 /e
  $ cp GeneralKenobi.txt "uwu"

  ~~~

  ![Ahhchu](https://cdn.discordapp.com/attachments/845383920458924034/1014319408761548810/unknown.png)
- mv
  - Te renombra y manda los archivos que quieras hacia otro lugar que específiques.
  ~~~

  user@DESKTOP-ED44C96 MINGW64 /e
  $ mv leeme.txt awadeuwu

  ~~~
  ![1](https://cdn.discordapp.com/attachments/845383920458924034/1014320372771991613/unknown.png)
  ![2](https://cdn.discordapp.com/attachments/845383920458924034/1014320266689650819/unknown.png)

- find
  - Al usar este comando puedes encontrar todos los archivos que contiene una carpeta. Absolutamente todos los archivos debo de resaltar.
  ~~~
  
  user@DESKTOP-ED44C96 MINGW64 /e
  $ find Entretenimiento
  
  ~~~
  ![Ejemplo](https://cdn.discordapp.com/attachments/845383920458924034/1014295411252543548/unknown.png)
 

## Comodines
---
- ~ 
  - Representa el "home" de la carpeta del usuario que este utilizando la computadora. 
  ~~~
  
  user@DESKTOP-ED44C96 MINGW64 /e
  $ pwd
  /e

  user@DESKTOP-ED44C96 MINGW64 /e
  $ cd ~

  user@DESKTOP-ED44C96 MINGW64 ~
  $ pwd
  /c/Users/user
  
  ~~~
  
- /
  - Te redirige hacia la raíz de la carpeta. O sea que si lo utilizas en Gitbash te llevará a la carpeta raíz donde se instalo el programa.
  ~~~
  
  user@DESKTOP-ED44C96 MINGW64 /c/Users
  $ cd /

  user@DESKTOP-ED44C96 MINGW64 /
  $ pwd
  /

  ~~~
- .
  - Al utilizar cd . referencia al directorio actual.
  ~~~
  
  user@DESKTOP-ED44C96 MINGW64 /c/Users
  $ cd /e

  user@DESKTOP-ED44C96 MINGW64 /e
  $ cd .

  user@DESKTOP-ED44C96 MINGW64 /e
  $

  ~~~
- ..
  - Al utilizar cd .. podemos acceder a la carpeta madre que contiene nuestra ubicación actual 
  ~~~
  
  user@DESKTOP-ED44C96 MINGW64 ~
  $ pwd
  /c/Users/user

  user@DESKTOP-ED44C96 MINGW64 ~
  $ cd ..

  user@DESKTOP-ED44C96 MINGW64 /c/Users
  $ pwd
  /c/Users

  ~~~
- "-"
  - Sirve para que el programa se regrese a la carpeta anterior.
  ~~~
  
  user@DESKTOP-ED44C96 MINGW64 /
  $ cd -
  /c/Users

  user@DESKTOP-ED44C96 MINGW64 /c/Users
  $ cd -
  /

  user@DESKTOP-ED44C96 MINGW64 /
  $ cd -
  /c/Users

  ~~~
- ""
  - Sirve por si quieres direccionarte a algún directorio específico.
  ~~~

  user@DESKTOP-ED44C96 MINGW64 ~
  $ pwd
  /c/Users/user

  user@DESKTOP-ED44C96 MINGW64 ~
  $ cd "Downloads"

  user@DESKTOP-ED44C96 MINGW64 ~/Downloads
  $

  
  ~~~




