# practica-contenedor
1. crear un repositorio en Github: practica-contenedor
2. Ingresar a start.spring.io y crear un proyecto, añadir dependecia web
3. Subir el proyecto del punto 2 al repositorio creado en el punto 1
4. Agregar un endpoint REST al proyecto Java que implemente lo siguiente (Sin BDD todo en memoria)(List o arraList)
	GET/api/v1/task
	[
		{
			taskId:1
			name: Hacer mi tarea
			dueDate: 25/12/2023
			status: PENDING
		}...
	]
	POST /api/v1/task
	{
		name: Hacerr mi tarea
		dueDate: 25/12/2023
		status:PENDING
	}
	DELETE /api/v1/task/1
# 5. Crear la imagen docker de la aplicacion java
# 6. exponer la aplicacion con un NGIX por delante del JAVA haciendo Reverse Proxy.
