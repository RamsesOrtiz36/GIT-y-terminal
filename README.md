# GIT-y-terminal
Uso de Git para seguimiento de cambios en archivos de código de forma local, posteriormente se usan aplicaciones para vincular el programa de Git local con GitHub plataforma que ayuda a compartir y controlar de forma remota, o en la nube, a los repositorios (carpetas con archivos de codigo)

Abrir una ventana de terminal de comandos en ubuntu se puede hacer de varias formas

* Combinación de teclas **Alt+Ctrl+t**.
* Clic derecho en el escritorio y seleccionar "Abrir en una terminal".
* Buscar en la lista de aplicaciones (Los 9 puntos e la parte de abajo a la izquierda en la pantalla), una vez encontrada se recomienda anclarla en la barra de tareas.

+ En terminal introducir el siguiente codigo:

        sudo apt-get install git
        
        git version
        
Comprueba que se ha instalado git.
![imagen version git](https://github.com/RamsesOrtiz36/GIT-y-terminal/blob/main/Git%20version.png)

+ Para crear carpeta de repositorio local se usa.

        git init [nombre de carpeta]
        
+ Crear archivo de texto en directorio creado.

        touch texto.txt
        
+ Comprobar estado del directorio.

        git status
        
+ Supervisar todos los archivos del directrio.

        git add .

+ Hacer un commit.

        git commit -m "Descripción"

+ Registro de usuario.

        git config --global user.email "you@examples.com"
        git config -- user.name "you name"
        
+ Realizar commit

        git commit "primer commit local"


Hay mas comandos y muchas veces los usuarios haces sus propias hojas de resumen de comandos (cheat sheets)

![git cheat sheets](https://github.com/RamsesOrtiz36/GIT-y-terminal/blob/main/git-cheat-sheet-Rebellabs-1536x1086.png)



        
