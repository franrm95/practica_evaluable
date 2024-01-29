Esta tarea ha sido muy útil para controlar y coger experiencia tanto en Git Bash como en GitHub.
El manual que nos proporcionaste ha sido de gran ayuda para el desarrollo de la actividad.
Durante el ejercicio hemos usado comandos para crear archivos, como puede ser el comando (echo "texo que añadir" > nombreDocumento.txt), 
comandos para ver lo que hay dentro del archivo "cat nombreArchivo.txt", 
comandos para editar el archivo de otra manera "nano nombreArchivo.txt".
A raíz de la práctica se nos ha grabado a fuego lo de que si creamos o modificamos un archivo cualquiera, al principio estará en el área de trabajo (que saldrá en color rojo) 
y luego mediante el comando "git add ." lo pasaremos al área de preparación(que saldrá en color verde), donde podremos validarlo mediante el comando (git commit -m "mensaje de validacion").
También hemos usado mucho el comando "git status" que nos permite descubrir si tenemos algo en el área de trabajo o en preparación.
Hemos aprendido además a crear ramas("git branch nombreRama") donde podremos trabajar en ellas. Luego una vez hayamos terminado con la rama y hayamos validado lo realizado debemos hacer la fusión con la rama principal
(main/master) con el comando "git merge nombreRamaAFusionar main/master". La fusión se hará en la rama principal, por lo que habrá que cambiarse si estamos en la rama creada, usando el comando "git checkout main/master".
Después de fusionar ambas ramas habrá que borrar la rama que ya no usaremos con el comando "git branch -d nombreRama". 
Una vez borrada ya podemos enviar los cambios al repositorio remoto con el comando "git push origin main/master".
También hemos aprendido a generar un conflicto y a resolverlo cuando se realicen modificaciones en el mismo archivo, pero en diferentes ramas.
Y sobre todo lo que hemos aprendido es a documentar todo el proceso que realicemos, ya que nos vendrá de mucha ayuda para el futuro.
Estos son solo unos pocos de los comandos que he usado en la práctica, hay bastantes más que no he puesto aquí pero que si están desglosados en la explicación que he realizado de cada ejercicio.
