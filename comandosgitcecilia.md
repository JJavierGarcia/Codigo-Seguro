Crear una rama:​

$ git checkout -b rama1​

Ver enque ramaestamo​
$ git Branch​

Cambiar de rama​

$ git checkout master​

Ver los cambios entre ramas​

$ git diff --stat master rama1​

Fusionar rama​

$ git checkout master​

$ git merge --no-ff rama1​

Eliminarla rama​
$ git branch -d rama1​

​

Paso 1:Vamos a crear una rama develop en nuestro remote>>​

 git checkout -b develop​

 git push origin develop

PULL RESQUEST

​
Crearla rama$ ​

$ git checkout –b feature-RE1 develop​
​

Añade tu nombre en README.md en el apartado Colaboradores​

Subirlos cambiosenlocal​

$ git add .​

$ git commit ​
​

Subirlos cambios​

$ git push --set-upstream origin feature-RE1​
​

Ir a github solicitar una pull request