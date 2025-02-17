# Practica-final

Para esta práctica usaremos las dos aplicaciones que trabajamos en el curso:

1.	CatalogoNET

2.	ShoppingCart


**Para el CatalogoNET**

●	Crea una nueva entidad llamada Empleado con los properties:
○	Nombre Completo
○	Fecha Nacimiento
○	Profesion

●	Carga con data de prueba a empleado, crea los archivos de migración y genera la tabla empleados en la base de datos.

●	Crea un endpoint controller que permite consultar la lista de empleados y hacer búsquedas por el nombre, por ejemplo si el parametro de busqueda es ‘la’ , entonces el endpoint debería devolver todos los nombres de empleados que contengan el texto ‘la’, por ejemplo:

○	‘Laura’

○	‘Lautaro’

○	‘Zavala’


**Para ShoppingCart**

●	Dentro del archivo Shared/Networking/Catalogo.Api crea un nuevo método para invocar al endpoint para obtener la data de empleado que anteriormente creaste en la aplicación CatalogoNET

●	Crea un nuevo directorio dentro Features llamado Empleado.

●	Dentro del directorio Features/Empleado crea un nuevo Minimal Api archivo llamado SearchEmpleado para devolver la lista de empleados a un cliente pasándole como parámetro el nombre del empleado.

