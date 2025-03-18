Bitacora del Examen Parcial 1

1.a) En el directorio de archivos de la computadora, se creó una carpeta llamada ExamParc1

1.b) Se crearon 4 archivos de texto, las cuales contienen texto o programas rudimentarios de Python

1.c) Con la dirección de la carpeta, se inicia usando el comando git init. Se usó git add para agregar los 4 archivos al repositorio y git commit para hacer commit a esos cambios.

2.a) Entré a la página web de GitHub e inicié sesión. Ya de ahí, creé un repositorio nuevo con el nombre examen-parcial-1, siendo un repositorio público

2.b) Asegúrese de que la opción de agregar un README se encuentre desactivado, ya de ahí cree su repositorio

2.c) En la página del repositorio recien generado, se copió el vínculo para poder accederlo por medio de la terminal

3.a) Dentro de la terminal, se usó git remote add origin con el vínculo previamente copiado para poder conectar el repositorio local con el remoto. Ya de ahí se uso git branch -M main para crear la rama principal del repositorio. Por último, se uso git push -u origin main para subir el contenido del repositorio local al remoto.

3.b) Ahora regresando a GitHub, se creó un archivo readme dentro del repositorio remoto. En este por ahora solo se indicó que era la bitácora del examen (Este texto fue escrito originalmente en el bloc de notas). Con el texto terminado, se presiona al botón de hacer un commit  y guardar los cambios dentro del repositorio

4.a) Se usó el comando git pull para guardar los cambios en el repositorio remoto dentro de la computadora

5.a) Se hicieron cambios en los dos archivos de Python para que hagan cosas completamente diferentes

5.b) Se agregaron estas instrucciones al archivo README que se creó en GitHub (y que para este punto ya se encuentra en la misma computadora)

5.c) Se guardan los cambios con git add, se agregan al repositorio usando git commit y se publica a GitHub usando git push

6.a) Dentro de GitHub se modificaron los 2 archivos de texto, cambiando su contenido con texto diferente

6.b) Se agregaron la versión más actualizada de los instrucciones al archivo README que se creó en GitHub, fueron enviados al repositorio local Y fueron publicado de nueva en GitHub (y que para este punto ya fueron publicados en GitHub)

6.c) Se usó git pull para traer los cambios de GitHub de regreso al repositorio local

7.a) Se creó una nueva rama usando git branch, esta se va a llamar rama-1

7.b) Se crearon dos archivos nuevos a la carpeta, ahora siendo imágenes para su facil distinción en el repositorio 

7.c/d) Se escribió git checkout para poder acceder a rama-1 y hacer los cambios dentro de esta. El procedimiento es el mismo, usar git add para agregar los archivos al repositorio, git commit para guardar los cambios y git push para publicarlos a GitHub. Se puede corroborar si se publicó correctamente al ver la pestaña de ramas dentro de GitHub.

7.e) Se puede regresar a la rama main usando git checkout. Para hacer la fusión entre ambas, se utiliza git merge con el nombre de la rama que se va a fusionar (rama-1). En este caso, se van a agregar las imágenes dentro del repositorio principal.

7.f) Se puede corroborar si los cambios se hicieron correctamente en el repositorio al intentar fusionar de nuevo. Si se menciona que los cambios ya están actualizados, entonces ya está listo.

7.g) Ahora las instrucciones fueron agregadas en el readme en el repositorio, y fue publicado por medio de git push para que los cambios en el repositorio local se guarden en el remoto