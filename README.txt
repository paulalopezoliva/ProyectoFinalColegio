Proyecto Colegio

Proyecto de final de curso de programacion Fullstack trainee basado en una plataforma de gestion de la base de datos de un colegio
en la cual se puede visualizar, modificar agregar y eliminar informacion de los alumnos dependiendo del usuario que inicia sesión
El estado actual se desarrollo el perfil de inicio de sesión del profesor y su opcion para visualizar sus cursos, alumnos y 
modificar notas.
-----------------------------------------------------------------------------------------------------------------------------------

Estructura del proyecto

El proyecto esta trabajado con el framework Spring basado en un modelo MVC y en peticiones a traves de servlets
-----------------------------------------------------------------------------------------------------------------------------------

Contenido

	- Login y logout.
	- Busqueda de cursos segun usuario logeado.
	- visualización de cursos y sus alumnos.
	- visualizacion y modificacion de notas de alumnos de manera individual.
-----------------------------------------------------------------------------------------------------------------------------------
Instalacion

Cargar proyecto:

Se debe descargar el proyecto desde el repositorio git en el siguiente link: -------------------
en el IDE correspondiente con el plugin de spring o directamente el STS.

Cargar base de datos:

Se debe instalar la base de datos utilizada en el proyecto para lo cual se ejecuta la secuencia SQL en el
SQLDeveloper

Modificacion del archivo POM:

se debe modificar la ruta que se encuentra en la dependencia de Ojdbc a la correspondiente a su equipo,
si no posee el jdbc se debe descargar la version 8 e indicar la ruta.

Modificacion de aplication.properties:

Se deben modificar las url,usuario,password y localhost a los correspondientes en su equipo.

