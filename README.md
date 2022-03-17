# Ejercicio3-ejemplo-rebase
mkdir directorio1
cd directorio1
nano archivoRebase
#creamos varias ramas para comprobar lo que hariamos con un rebase
git checkout -b rama1
git checkout -b rama2
crearimos dos archivos en cada rama , le hariamos add y commit
Una vez hecho esto nos iriamos de nuevo a a la rama master con el checkout master
y realizariamos un rebase desde aqui, con el comando git rebase --interactive "hash" apuntando al has en este caso de la rama master
