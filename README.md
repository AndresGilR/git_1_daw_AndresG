# git_1_daw_AndresG
#Práctica entregable

1)git clone https://github.com/AndresGilR/git_1_daw_AndresG.git //Para traer el repositorio remoto a la máquina

2)Para que se ignoren los archivos tendremos que crear un archivo oculto llamado .gitignore. Una vez creado, tendremos que poner la ruta de los archivos a ignorar, siempre comenzando por un /

3)Para crear un archivo en nuestro repositorio local podremos usar tanto touch, como echo, como gedit,vim,nano, etc. En mi caso usaré echo ya que es más fácil:
	>>echo "Esto es el primer archivo de pruebas">1.txt
	
4)Para crear un tag simplemente tendremos que usar el comando:
	>>git tag v0.1
	>>git commit -m "Tag añadido"
	>>git push 
		
5)Para crear una rama nueva simplemente usaremos el comando
	>>git checkout -b v0.2
	>>git commit -m "Creada nueva branch"
	>>git push
6) Si no estamos en la rama main o master, usaremos el comando checkout para cambiar
	>>git checkout master
Y para realizar el merge usaremos 
	>>git merge v0.2
	
7)Para generar un conflicto con una rama simplemente tendremos que cambiar el valor de un archivo que se encuentre en la rama v0.2 para que, cuando intentemos hacer el merge, nos diga de que hay dos archivos que difieren, por lo que tendríamos que resolver la incidencia volviendo a poner lo mismo en ambos archivos.

8)Para arreglar el conflicto simplemente tenemos que hacer lo que dije en el punto anterior.

9) Para ver todos los cambios realizados en el repositorio usaremos el comando: 
	>>git log
	

| NOMBRE  |GITHUB   |
|---|---|
| Nombre del compañero  |enlace    |
|   |   |
|   |   |

