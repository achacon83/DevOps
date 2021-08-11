# DevOps
Trabajo practico para Cursada de DevOps

# Consigna:

Se requiere crear un proyecto en Vagrant que debe estar contenido en el directorio UTNDevOps de su computadora. Así mismo, se debe crear un proyecto en Github con el nombre "utn-devops" para versionar la infraestructura (recomendamos que sea de tipo público para facilitar las prácticas).
El proyecto en Vagrant debe estar versionado en el repositorio recientemente creado bajo la rama (branch) "unidad-1-vagrant" y subirlo a Github. Vagrant deberá cumplir con lo siguiente:
● Crear una máquina virtual (VM) Ubuntu.
● Redirigir el tráfico web de la VM al puerto 8080 de la máquina Host (su propia computadora).
● Mapear la carpeta del proyecto de la máquina Host al directorio "/vagrant" en Ubuntu
● Copiar el archivo de configuración del servidor web desde la máquina host a la VM Ubuntu
● Script de aprovisionamiento:
    ○ instalación del servicio web que sirva el código de una aplicación simple (puede ser un sitio estático, por ejemplo en PHP, React, HTML, etc). Para esto podrán elegir el lenguaje que quieran o bien utilizar el siguiente código de ejemplo en el branch "unidad-1" (URL al código).
    ○ instalación de las dependencias que requiera la aplicación.
    ○ Descargar el código de la aplicación dentro de Ubuntu para que el servicio web lo presente.
Si se decide optar por crear una aplicación, la misma debe estar alojada en un repositorio en Github distinto al de la infraestructura. En este enlace hay un artículo con una guía detallada de los conceptos básicos y sino aquí pueden encontrar la documentación inicial, desde la configuración y comandos básicos.
