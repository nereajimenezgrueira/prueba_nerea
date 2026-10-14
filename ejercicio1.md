# Ejercicio 1: Introducción a git y GitHub.
## En este archivo Markdown están documentados los pasos del ejercicio 14 del Ejercicio 1.

### Vamos a crear un nuevo repositorio llamado prueba2_tu_nombre. Ten en cuenta lo siguiente:
## En esta ocasión, crea primero el repositorio local en Windows (usando git init). El repositorio debe contener, al menos, dos archivos de texto: archivo1.txt y archivo2.txt. El contenido de ambos archivos es libre.
El repositorio fue creado manualmente desde la propia página de GitHub. Así, después se pudo obtener el enlace HTTPS para poder conectarlo remotamente con el repositorio local creado en el equipo de clase o para clonarlo y volver a descargar los cambios desde una máquina virtual Ubuntu Server.

### Creación del repositorio en el equipo local.
Después de haber creado el repositorio en GitHub, creé una carpeta en el equipo local que se llamase igual que el repositorio. Ahí creé dos archivos de texto e inicialicé el repositorio con el comando 
```
git init
```
![CrearRepo](/Imágenes//capturas%20IAW/capturas%20Ejercicio%201/creacion_repositorio.jpeg)

### Conectar el repositorio local con el remoto en GitHub.
Este apartado fue realizado con el comando `git remote add origin` y el enlace HTTPS, utilizando el token para poder loguearme y conectar el repositorio.
![ConectarRepo](/Imágenes//capturas%20IAW/capturas%20Ejercicio%201/conectar_repositorio.jpeg)

### Subir el repositorio.
Después de haber realizado un `git add .`y un `git commit`para poder confirmar los cambios de los ficheros creados anteriormente, realicé un `git push origin main`para subir los cambios al repositorio remoto.
![SubirRepo](/Imágenes/capturas%20IAW/capturas%20Ejercicio%201//subir_repositorio.jpeg)

## Clonar el repositorio.
Para este apartado fue utilizado un clon de una máquina virtual Ubuntu Server 26.04. Una vez tuve el repositorio remoto, lo cloné en la máquina virtual con el comando `git clone` y la URL del repositorio que proporciona GitHub, siempre la de HTTPS.
![ClonarRepo](/Imágenes//capturas%20IAW/capturas%20Ejercicio%201/clonar_mv.jpeg)

## Modificar uno de los archivos y crear otro. Subir los cambios.
Para realizar esta práctica, modifiqué el archivo1.txt, añadiéndole otra línea. 
![ModificarArchivo](/Imágenes//capturas%20IAW/capturas%20Ejercicio%201/modificar_archivo.jpeg)

Seguidamente, creé un archivo nuevo con `echo`, agregándole un texto y redirigiendo la salida a un archivo con extensión .txt
Finalmente, agregé todos los archivos modificados con el comando `git add` y confirmé con los cambios con `git commit` y subí los cambios con `git push`.
![Archivo3](/Imágenes//capturas%20IAW/capturas%20Ejercicio%201/archivo3_subida.jpeg)

## Actualizar la versión local del repositorio.
El apartado final consistió en actualizar el repositorio clonado en la máquina virtual. En otras palabras, _traer los cambios_ del repositorio remoto. 
```
Git pull
``` 
es el comando para realizar este ejercicio.
![ActualizarRepo](/Imágenes//capturas%20IAW/capturas%20Ejercicio%201/git_pull.jpeg)
