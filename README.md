# git_1_daw_AndresG
#Práctica entregable

1)git clone https://github.com/AndresGilR/git_1_daw_AndresG.git //Para traer el repositorio remoto a la máquina

2)Para que se ignoren los archivos tendremos que crear un archivo oculto llamado .gitignore. Una vez creado, tendremos que poner la ruta de los archivos a ignorar, siempre comenzando por un /

3)Para crear un archivo en nuestro repositorio local podremos usar tanto touch, como echo, como gedit,vim,nano, etc. En mi caso usaré echo ya que es más fácil:
	>>echo "Esto es el primer archivo de pruebas">1.txt
	
4) OJO para hacer un push sin que de problema hay que tener en cuenta de que el push por HTTPS fue deprecado en 2021, así que tendríamos que cambiar la URL por la de SSH para que nos permita hacer cambios. Para ello usaremos el siguiente comando: 
	>>git remote set-url origin (enlace SSH de nuestro repositorio)

5) Para crear un tag en Git lo único que debemos hacer es usar el comando : 
	>>git tag v0.1
	
6) Para crear una rama nueva usaremos el comando : 
	>> git checkout -b v0.2
	
7) El merge directo es sencillo, simplemente debemos hacer un: 
	>>git merge v0.2
	
8) El conflicto viene de que todos los archivos son igules salvo el 1.txt que tiene información dispar, por lo que para solucionar el merge conflictivo simplemente debemos adecuar el contenido del mismo archivo y hacer que coincida con el 1.txt en la rama master.

9)Para eliminar un rama usaremos el comando : 
	>> git branch -D "nombre de la rama"
	
10) Para ver todos los cambios realizados dentro del repositorio usaremos el comando : 
	>> git log 
	
	
| NOMBRE  |GITHUB   |
|---|---|
| Nombre del compañero  |enlace    |
|   |   |
|   |   |

