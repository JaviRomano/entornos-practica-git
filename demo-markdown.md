<div align="center">
  
# 🇯​​​​​🇦​​​​​🇻​​​​​🇮​​​​​🇷​​​​​🇴​​​​​🇲​​​​​🇦​​​​​🇳​​​​​🇴 
![Logoromano](/logo_red.png)
  
<div align="left">
He creado este documento para tratar de sincronizar lo aprendido en clase sobre Git y GitHub con lo adquirido a traves de otras fuentes y el aprendizaje durante la realización de esta práctica.

Entendemos la herramienta Git como un sistema de control de versiones que permite rastrear los cambios realizados en un conjunto de archivos mediante **instantáneas**, que vienen a ser cada una de las
iteraciones sobre los cambios efectuados en los archivos de un proyecto, manteniendo el registro de los cambios realizados.

### Instalar Git

Buscamos la versión acorde a nuestro sistema operativo en la página oficial de [Git](https://git-scm.com/), donde también se pone a nuestra disposicion toda la [documentación](https://git-scm.com/book/es/v2) referente (disponible en distintas traducciones), algo a tener en cuenta ya que ofrece bastante información valiosa en caso de surgir dudas.

### Configurar Git

Una vez instalado, desde la terminal GitBash incluida con Git debemos insertar los siguientes comandos para definir el usuario y su correo electrónico:<br>
 Esta configuración inicial es esencial para el uso de Git.
- `git config — global user.nombre`  “nombre” configura nombre de usuario.
- `git config — global user.mail`  “mail” configura direccion de email de usuario.
  
El siguiente comando se ha establecido como el estandar entre usuarios, no implica que sea obligatorio pero si aconsejable:
- `git branch -m main` a la rama inicial se le renombra ‘main’ (master, al parecer suena feo).

### Comandos GitBash

Las siguientes instrucciones se pueden realizar a traves de nuestro IDE, aunque se aconseja adquirir soltura con la consola de comandos, dado que podremos hacer frente a inconvenientes eventuales para los que determinados IDE no disponen de herramientas.

- `pwd` imprime el directorio de trabajo actual (equivale a **cd** en un terminal DOS).
- `mkdir “nueva carpeta”` crear directorio dentro del actual (MaKe DIRectory).
    > nos movemos al directorio creado donde alojaremos nuestro control de versiones.
- `git init` Inicializa git como repositorio (iniciar tracking) (crea directorio .git donde se alojarán los archivos).
- `git status` muestra el contenido de la rama ‘main’.
- `git touch holaGit.txt` 'git touch' genera un archivo txt con el nombre holaGit.
- `git add holaGit.txt` 'git add' añade el archivo txt con el nombre holaGit al área de **stage**, que es la zona donde colocamos los archivos antes de realizar un **commit**.
- `git commit` Genera la instantánea de los cambios en ese momento, pasan a ser versiones. Solo se le aplicarña a los archivos incluidos en el stage mediante  `git add`. NOTA: abre un editor de texto para generar el comentario del commit.
- `git commit -m "comentario sobre el cambio de version"` Al incluir el comentario en el comando simplifica el proceso del commit.
- `git log` muestra historial de commit.
   > muestra id de los commit (puede extenderse y devolver distintos tipos de lineas de informacion). <br> `git log --graph` | `git log --graph --pretty=oneline` | `git log --graph --decorate --all --oneline`
- `git branch nombreRama` Crea una nueva rama. 
    > Crearemos una nueva rama con la información del commit donde estábamos.
- `git switch nombreRama` cambia para situarnos en la rama nombrada.
- `git checkout id-del-commit-específico` realizar un checkout a un commit específico.
- `git checkout nombreRama` realizar checkout a una rama existente.
    > Checkout realiza la función de switch, pero puede realizarse para mas funciones, `switch` es específico unicamente para cambiar de rama.
- `git checkout -b NOMBRE-DE-LA-RAMA-NUEVA` Crea rama nueva y checkout a dicha rama (cambia automatico).
- `git config --global alias.tree "log --graph --decorate --all --oneline"` establece alias sobre un comando.
    > ‘tree’ es la palabra usada para el alias | “comando sobre el que aplicamos el alias” | Se añade en el .gitconfig
- `git diff` muestra los cambios entre versiones.
- `git tag elegido` asigna un tag a la instantanea | tag: elegido | minusculas_y_numeros
- `git tag` lista las etiquetas.
***

<div align="center">
  
## Bibliografia
  
[![Videotutorial Git & GitHub](https://markdown-videos-api.jorgenkh.no/youtube/3GymExBkKjE)](https://youtu.be/3GymExBkKjE)
[![Aprende MarkDown en 6 minutos](https://markdown-videos-api.jorgenkh.no/youtube/y6XdzBNC0_0)](https://youtu.be/y6XdzBNC0_0)

***
<img src="https://git-scm.com/images/logos/downloads/Git-Logo-White.svg" height="40"/>
<img src="https://skillicons.dev/icons?i=md,github" height="40"/>













<!--- ## Materias
Se describe el contenido de cada una y las competencias que se trabajan en ellas.
___

### Programación
Iniciacion en **Java**, operaciones logicas, aprendizaje de lógica booleana, conocimiento y aplicación de los distintos métodos de los que dispone Java, programacion orientada a objetos. Operaciones en distintos IDE: **Paiza, NetBeans, Visual Studio Code, Eclipse**.
<div align="center">  
   <img src="https://skillicons.dev/icons?i=java,eclipse,vscode" height="40"/>
  <img width="12" />
  
___
<div align="left">
  
### Base de datos
Creacion de esquema conceptual de una base de datos, diagramas entidad-relacion, creacion de una BBDD e insercion de sus registros, consulta y edicion de BBDD mediante **MySql Workbench**.
<div align="center">  
   <img src="https://skillicons.dev/icons?i=mysql" height="40"/>
  <img width="12" />
  
___
<div align="left">
  
### Sistemas informáticos
Nociones de hardware, herramientas de los distintos sistemas operativos, inicio en **Linux** y sus distintas disposiciones, aprender a trabajar mediante lineas de comandos.
<div align="center">  
<img src="https://skillicons.dev/icons?i=linux,ubuntu,kali,mint,windows,powershell" height="40"/>
<img width="12" />
  
___
<div align="left">
  
### Entornos de desarrollo
Conocimientos sobre los procesos de desarrollo y el IDE donde creamos el codigo fuente desde la concepción del codigo, el funcionamiento interno de los IDE y utilidades que ofrecen, así como el aprendizaje de distintas buenas prácticas a aplicar durante el proceso de programación. Trabajando desde **NetBeans y Eclipse**.
<div align="center">  
<img src="https://skillicons.dev/icons?i=python,markdown,notion,git,github" height="40"/>
<img width="12" />
  
___
<div align="left">
  
### Lenguaje de marcas
Aprendizaje sobre el lenguaje de marcado para dotar de una estructura ordenada y legible durante el desarrollo de un dominio web, centrando el contenido en **HTML, CSS y JavaScript**.
<div align="center">  
<img src="https://skillicons.dev/icons?i=sublime,html,css,javascript,figma" height="40"/>
<img width="12" />
  
___-->

 
