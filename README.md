 **- Clonar vuestro repositorio en local**
¿
    $ git clone https://github.com/Damsh-bit/devjumpers.git


**- Crear en nuestro repositorio local un
documento README.md**
`cd devjumpers` *(para entrar dentro del repo clonado)*  
`$ touch README.md` *(para crear el documento readme)*

**- Commit inicial**
`$ git add .` *(para agregar el readme )*

`$ git commit -m "Commit inicial"` *(para hacer el commit inicial)*

**- Push inicial**
`$ git push` *(para pushear los cambios y subir el commit)*

-**- Ignorar archivos**
`$ touch privado.txt` *(creo doc de txt)*

`$ mkdir privada` *(creo carpeta)*

`$ touch .gitignore` *(crea txt llamado .gitignore)*

`$ echo privada > .gitignore` *(le escribo privada para ignorar la carpeta, dentro de gitignore)*

`$ git status` *(para verifiar que la ignora)*

`$ echo privado.txt > .gitignore` *(le escribo privado.txt para ignorar la el texto, dentro de gitignore)*

`$ git status` *(para verifiar que lo ignoro)*

**- Añadir fichero 1.txt al repositorio local.**

`$ touch 1.txt` *(agrego 1.txt al local)*

**- Crear una rama con el nombre v0.2.**

`$ git branch v0.2` *(crea una rama con ese nombre)*

`$ git checkout v0.2` *(nos posicionamos en la rama creada)*

`$ touch 2.txt` *(crea fichero en esa rama)*

`$ git status` *(para ver que se modifico)*

`$ git add .` *(para agregar todo)*

**- Añadir fichero 1.txt**

    $ touch 1.txt

**- Añadir un fichero 2.txt en la rama v0.2**

    $ touch 2.txt

**- Crear rama remota v0.2, subir cambios al repo remoto**

`$ git status` *(verifico los cambios en la rama)*
`$ git add .` *(agrego todo)*
`$ git commit -m "Nueva rama, se agrega fichero 2.txt"` *(commiteo con informacion)*
`$ git push origin v0.2` *(pusheo cambios en v0.2)*

**- Posicionarse en la rama master/main**
`$ git checkout main` *(voy a main)*

**- Hacer un merge de la rama v0.2 en la rama master.**
`$ git merge v0.2` *(posicionados en la main, hago un merge con la rama v0.2)*


**- En la rama master poner Hola en el fichero 1.txt y hacer commit.**

    $ echo Hola > 1.txt
    $ git status
    $ git add .
    $ git commit -m "Modifique el archivo 1.txt"
    $ git push

**- Posicionarse en la rama v0.2 y poner Adios en el fichero "1.txt" y hacer commit.**

    $ git checkout v0.2
    $ echo Adios > 1.txt
    $ git status
    $ git add .
    $ git commit -m "Modifique el archivo 1.txt"
    $ git push origin v0.2*

**- Posicionarse de nuevo en la rama master y hacer un merge con la rama v0.2**

    $ git checkout main
    $ git merge v0.2


**- Listar las ramas con merge y las ramas sin merge.**

    $ git branch --merged
    $ git branch --no-merged

**- Arreglar el conflicto anterior y hacer un commit.**

    $ git add .
    $ git commit -m "conflictos resueltos"
    $ git push

**- Borrar la rama v0.2**

    $ git branch -d v0.2


**- Listar los distintos commits con sus ramas y sus tags.**

    $ git list
    $ git log


Nombre  | Github
------------- | -------------
Armando Torres Quintana  | [Perfil de Github](http://https://github.com/ArmaTQ "Perfil de Github")
Lucas Gimenez  | [Perfil de Github](http://https://github.com/Vrodah "Perfil de Github")
Alejo Paiva  | [Perfil de Github](https://github.com/BLUHD823/ "Perfil de Github")
Cristian Ortiz | [Perfil de Github](https://github.com/Cristian550/ "Perfil de Github")
Camila Calegari | [Perfil de Github](https://github.com/camilacalegari/ "Perfil de Github")
Franco Formigo  | [Perfil de Github](https://github.com/francobenjaminformigo "Perfil de Github")

# Colaboradores
[Armando Torres Quintana](http://https://github.com/ArmaTQ)
[Camila Rios](https://github.com/camilarios01)
