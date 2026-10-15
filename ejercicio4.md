# Ejercicio 4: ¿Cómo colaborar en un proyecto de software libre? ¿Qué es un Pull Request (PR)?

El primer paso consta de clonar el repositorio original del profesor con el comando `git clone`.
![ClonarRepo](Imagenes4/clone_repo_prof.jpeg)

Creo la rama con mis iniciales para agregar en ella los cambios en los ficheros que contiene el repositorio original.
![CrearRama](Imagenes4/crear_rama_iniciales.jpeg)

En la página de GitHub, accedo al repositorio del profesor y localizo el botón "Fork". Creo uno y después lo clono en mi equipo local mediante `git clone`. Después creo la misma rama que creé anteriormente.
![ClonarFork](Imagenes4/clonar_fork.jpeg)

En el repositorio clonado, modifico el archivo "Files" para agregar un enlace al README que modifico después, respondiendo a las preguntas solicitadas.
![ModificarREADME](Imagenes4/README_NJG.jpeg)

![Enlace](Imagenes4/enlace_NJG.jpeg)

Subo los cambios con `git push`y el nombre de la rama con mis iniciales.
![SubirCambios](Imagenes4/subir_cambios.jpeg)

Después de haber subido los cambios, entro a GitHub y en el repositorio clonado verifico que se haya creado la rama correctamente. Debe tener dos ramas, la **main**, que es la que contiene los archivos originales del profesor y la **ejercicio4-NJG**, que contiene mis archivos modificados y el enlace al README.
![ComprobarRama](Imagenes4/comprobar_rama.jpeg)

![RamaNJG](Imagenes4/rama_NJG.jpeg)

Finalmente, creo el Pull Request en el botón superior que dice **Compare and Pull Request**. Le agrego una descripción y lo creo.
![CrearPR](Imagenes4/crear_PR.jpeg)
