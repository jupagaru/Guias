![](https://profile.es/wp-content/media/image.png ) 

* Es una herramienta que permite desplegar aplicaciones en contenedores, de forma rápida y portable.

* Permite generar aplicaciones de bolsillo.

### Que es una imagen?
Es un paquete que contiene toda la inforación necesaria para que pueda ejecutarse la aplicación. Estas se componen por capas.

***Docker host es el servidor físico /real donde se encuentra instalado Docker***

### Docker Hub
[hub.docker.com](https://hub.docker.com)
Lugar público donde podemos subir las imágenes

Para descargar imágenes oficiales simplemente se debe buscar en docker hub y hacer pull
**(docker pull name_image:version)**

**Comandos Images**
* Para ver las imágenes
    * docker images
* Para ver imágenes en específico
    * docker images | grep nombre
* Eliminar imágen
    * docker **rmi** nombre:tag (El tag es para diferenciar en caso de que exista mas de una imagen pero con versión distinta.)