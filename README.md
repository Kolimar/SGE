SISTEMA DE GESTION PARA ESTUDIOS.


SE VA A TRABAJAR CON 2 FRAMEWORKS SEPARADOS. CADA UNO EN SU RESPECTIVA CARPETA, FRONTEND Y BACKEND.
EL DESARROLLO Y PASOS A SEGUIR PARA HACER FUNCIONAR CADA PROYECTO (API Y FRONT) TIENE QUE ESTAR DESCRIPTO EN UN README DENTRO DE LA CARPETA CORRESPONDIENTE.

LA CARPETA PATRONES VA A TENER ALGUNOS EJEMPLOS TRABAJADOS EN PHP PARA QUE SIRVAN DE EJEMPLO SOBRE ALGUNAS PRACTICAS ÚTILES.


COMANDOS GIT:

"git fetch" : actualiza la información del proyecto de manera local y con el servidor.

"git merge" : sincroniza la información local actual con el branch que se aclara.(los mezcla)

"git pull" : realiza un fetch y merge actualizando lo que tenemos en la pc con la rama en la que estamos parados.

"git add" : añade todo lo modificado a un paquete

"git commit" : etiqueta el paquete para su posterior subida.

"git push" : envia al servidor todos los paquetes que estan etiquetados.

"git status" : compara los cambios locales con la ultima imagen del servidor que se trajo con fetch.

"git branch" : muestra el nombre de la rama donde estamos y las demas ramas 

"git checkout " : se usa frecuentemente para cambiar o verificar la rama donde estamos.

ACLARACION: Todos los comandos o casi todos es conveniente ejecutarlos aclarando el nombre del puntero y la rama. Por ejemplo para actualizar la rama master del puntero original conviene traerla con el comando "git pull origin master". Esto evita que te puedas equivocar al subir o actualizar.

SUB COMANDOS ÚTILES:
"git commit -m 'este es mi mensaje'" : Etiqueta un paquete sin necesidad de abrir un editor de texto.
"git add . " : añade todo lo que se hizo sin necesidad de aclarar nada.
"git checkout . " : vuelve todo lo trabajado a la version que está subida descartando todo.
"git checkout branchname" : Cambia a la rama branchname donde branchname es el nombre de la rama a la que queres moverte.
"git checkout -b branchname" : Crea y cambia a la rama branchname

HAY MUCHOS MAS COMANDOS, TODA LA DOCUMENTACIÓN ESTA EN https://git-scm.com/