# Demo Git

Comprobar si esta instalado 

git --version

Instalar git

 sudo apt install git

Agregar nombre de usuario

git config --global user.name "Your Name"

Agregar email

 git config --global user.email "youremail@domain.com"

Comprobar la configuración

git config --list
Iniciar repositorio

git init

Añadir el contenido (stage)

git add .

Confirmar el contenido

git commit -m "Se inicializa el repositorio con el fichero readme"

Comprobar la rama

git branch 

Añadir el reposiotio remoto al local

git remote add origin https://github.com/sotobotero/devops_udemy.git

Enviar los cambiso al repositorio remoto

git push -u origin master 
Crear un nuevo branch

git branch feacture/cs-2356847 master 

Cambiarse a la nueva branch

git checkout feacture/cs-2356847 

Actualizar el branch actual(el seleccionado) desde el branch master

 git pull origin master 
Inicializar el repositorio 

git flow init

Crear una rama de caracteristica

git flow feature start cd32658

Eliminar la caracteristica

git flow feature finish cd32658 

>Fin....
