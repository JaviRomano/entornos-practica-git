### Informacion sobre todo lo aprendido
***
#### Enlaces de interés en **GITHUB**
___

[sintaxis markdown](https://markdown.es/sintaxis-markdown/#imagenes)
[Videotutorial para principiantes Git - GitHub](https://www.youtube.com/watch?v=3GymExBkKjE&t=195s)



~~~ 
`ls` muestra el contenido del directorio

`cd Desktop` ir al escritorio

`cd ..` volver directorio anterior

`pwd` muestra directorio actual

`mkdir “nueva carpeta”` crear directorio dentro del actual (make directory)

vamos al directorio creado donde alojaremos nuestro control de versiones

`git config — global [user.name](http://user.name) “nombre”` configura nombre de usuario

`git config — global user.mail “mail”` configura direccion de email

`touch holaGit.txt` genera un archivo txt con el nombre holaGit

`git init` Inicializa git como repositorio (iniciar tracking) (crea directorio .git donde se alojarán los archivos)

`git branch -m main` a la rama inicial se le renombra ‘main’ (master al parecer suena feo).

`git status` muestra el contenido de la rama ‘main’

`git log` muestra historial de commit 

- `git log` muestra id de los commit (puede extenderse y devolver distintos tipos de lineas de informacion)
    
     `git log --graph` | `git log --graph --pretty=oneline` | `git log --graph --decorate --all --oneline`
    

`git commit -m` "comentario sobre el cambio de version"

`git checkout id-del-commit-específico` realizar un checkout a un commit específico

`git checkout NOMBRE-DE-LA-RAMA` realizar checkout a una rama existente

`git checkout -b NOMBRE-DE-LA-RAMA-NUEVA` crear y checkout a una rama nueva (cambia automatico)

`git config --global alias.tree "log --graph --decorate --all --oneline"` establece alias sobre un comando  | ‘tree’ es la palabra usada para el alias, “comando sobre el que aplicamos el alias” | Se añade en el .gitconfig

`git diff` muestra los cambios entre codigos

`git tag elegido` asigna un tag a la instantanea | tag: elegido | minusculas_y_numeros

~~~
