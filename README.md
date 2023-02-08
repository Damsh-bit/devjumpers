---Clonar vuestro repositio en local---
$ git clone https://github.com/Damsh-bit/devjumpers.git


---Crear en nuestro repositorio local un
documento README.md---
cd devjumpers (para entrar dentro del repo clonado)  
$ touch README.md (para crear el documento readme)

--Commit inicial--
$ git add . (para agregar el readme )

$ git commit -m "Commit inicial" (para hacer el commit inicial)

---Push inicial---
$ git push (para pushear los cambios y subir el commit)

---Ignorar archivos---
$ touch privado.txt (creo doc de txt)

$ mkdir privada (creo carpeta)

$ touch .gitignore (crea txt llamado .gitignore)

$ echo privada > .gitignore (le escribo privada para ignorar la carpeta, dentro de gitignore)

$ git status (para verifiar que la ignora)

$ echo privado.txt > .gitignore (le escribo privado.txt para ignorar la el texto, dentro de gitignore)

$ git status (para verifiar que lo ignoro)

---Añadir fichero 1.txt
Añadir fichero 1.txt al
repositorio local.---

$ touch 1.txt (agrego 1.txt al local)

---Crear una rama v0.2
Crear una rama con el nombre v0.2.---

$ git branch v0.2 (crea una rama con ese nombre)

$ git checkout v0.2 (nos posicionamos en la rama creada)

$ touch 2.txt (crea fichero en esa rama)

$ git status (para ver que se modifico)

$ git add . (para agregar todo)

---Añadir fichero
1.txt---
$ touch 1.txt

---Añadir un fichero 2.txt en la
rama v0.2---
$ touch 2.txt

--Crear rama remota v0.2, subir cambios al repo remoto--

$ git status (verifico los cambios en la rama)
$ git add . (agrego todo)
$ git commit -m "Nueva rama, se agrega fichero 2.txt" (commiteo con informacion)
$ git push origin v0.2 (pusheo cambios en v0.2)