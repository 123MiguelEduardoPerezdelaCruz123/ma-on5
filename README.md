Git

Sabiendo Git que es un sistema de control de versiones distribuido, lo que significa que un clon local del proyecto es un repositorio de control de versiones completo. Ahora profundisaremos en las distintas opciones que esta otorga a cada usuario.

!Vamos!


Funciones.

Tipos de archivos en el sistema de Git.

Historia.

Ordenes Basicas.

Funciones:**
las funcionalidades de crear ramas y fusiones y reescribir historiales de repositorios, lo cual ha dado como resultado muchas herramientas y flujos de trabajo innovadores y eficaces. Las solicitudes de incorporación de cambios son una herramienta popular con la que los equipos pueden colaborar en las ramas de Git y revisar con eficacia el código de los demás. Git es el sistema de control de versiones más utilizado en el mundo hoy en día, y se considera el modelo actual de desarrollo de software.


Tipos de archivos:
En Git existen 4 tipos de archivos: Blob, Tree, Commit y Annotated Tag. Estos cuatro tipos de objetos permiten almacenar archivos y monitorear los cambios en estos.

En los objetos de tipo Blob en Git almacena archivos, cualquier archivo con cualquier extensión es almacenado como Blob.

En los objetos de tipo Tree (árbol) Git almacena directorios, de la misma forma que cualquier otro tipo de archivos, un directorio puede estar vacío o contener archivos u otros directorios. Por lo cual un Tree puede contener un grupo de Blobs y otros Trees.

Los objetos tipo Commit en Git almacenan las versiones del proyecto.

Los objetos tipo Annotated en Git almacenan texto persistente de un Commit.

Historia:
 Git es un proyecto de código abierto maduro y con un mantenimiento activo que desarrolló originalmente Linus Torvalds, el famoso creador del kernel del sistema operativo Linux, en 2005. 

Linux tenía un gestor de paquetes que pasó a ser de pago, por lo que el desarrollador principal de Linux decidió crear un nuevo gestor de control de versiones para su sistema, y que diera soporte a su core. De esta forma nació Git.

 Ordenes Basicas:

 
 Git init: Esto crea un subdirectorio nuevo llamado .git, el cual contiene todos los archivos necesarios del repositorio – un esqueleto de un repositorio de Git. Todavía no hay nada en tu proyecto que esté bajo seguimiento.

Git fetch: Descarga los cambios realizados en el repositorio remoto.

Git merge <nombre_rama>: Impacta en la rama en la que te encuentras parado, los cambios realizados en la rama “nombre_rama”.

Glosario de Terminos

Ramas:
 Son espacios o entornos independientes para que un Desarrollador sea Back-end, Front-end, Tester, etc. pueda usar y así trabajar sobre un mismo Proyecto sin chancar o borrar el conjunto de archivos originales del proyecto, dándonos flexibilidad para desarrollar nuestro proyecto de manera mas organizada.

Directorio:
 Es un contenedor virtual en el que se almacenan una agrupación de archivos informáticos y otros subdirectorios, atendiendo a su contenido, a su propósito o a cualquier criterio que decida el usuario.

Repositorio: 
Es una ubicación central de almacenamiento de archivos. Es utilizado por control de versiones sistemas para almacenar múltiples versiones de archivos. Si bien un repositorio se puede configurar en una máquina local para un solo usuario, a menudo se almacena en un servidor, al que pueden acceder varios usuarios.

Repositorio remoto:
son versiones de tu proyecto que están hospedadas en Internet o en cualquier otra red. Puedes tener varios de ellos, y en cada uno tendrás generalmente permisos de solo lectura o de lectura y escritura.


