- En esta página se encuentran las distintas plantillas, si se desea editar alguna se hace desde esta página
- # Proceso
- # Titulo Proceso
  template:: Proceso
	- Grupo:: Indica el grupo al que pertenece mediante una tag, tags - #tags
	- subgrupo:: Indica el subgrupo con una tag - #tags
	- estatus:: indica el estatus con una tag - #tags
	- tipo:: #proceso
	- # Título
		- Grupo:: Indica el grupo al que pertenece mediante una tag, tags - #tags
		  subgrupo:: Indica el subgrupo con una tag - #tags
		  Tipo:: #RACI
		- | Actividad|     R      |  A | C | I |
		  |----------|:-------------:|------:|------:|------:|
		  | Actividad 1|  Responsable| Aprobador| Consultado | Informado |
		  | Actividad 2 |    Responsable   |   Aprobador| Consultado | Informado  |
		  | Actividad 3 | Responsable |    Aprobador | Consultado | Informado  |
	- ## Responsable
	- Indica el responsable del proceso
	- ## Entrada
		- Indica la entrada del proceso
	- ## Salida
		- Indica la salida esperada del proceso
	- ## Resumen
		- Resumen de lo que realiza el proceso
	- ## Lista de acciones
		- Acción 1
		  logseq.order-list-type:: number
		- Acción 2
		  logseq.order-list-type:: number
		- Acción 3
		  logseq.order-list-type:: number
	- ### Nota(opcional)
	- Agrega una nota si hay alguna observación o acción a tomar en cuenta mientras se realiza el proceso
-
- # Término
- # Título
  template:: Término
	- Categoría:: Indica a la categoría a la que pertenece el término con una tag, tags - #tags
	  Tipo:: #término
	- ## Significado
		- Se indica el significado del término indicado
	- ## Imagen
		- Aquí se coloca una imagen en caso de ser requerida
-
- # Guía
- # Título Guía
  template:: Guía
	- Grupo:: Indica el grupo al que pertenece mediante una tag, tags - #tags
	- subgrupo:: Indica el subgrupo con una tag - #tags
	- Tipo:: #guía
	- ## Resumen
		- Aquí va un resumen sobre de que va la guía
	- ## Recomendaciones
		- ### Recomendación 1
			- Descripción de recomendación 1
		- ### Recomendación 2
			- Descripción de recomendación 2
		- ### Recomendación 3
			- Descripción de recomendación 3
	- ## Conclusión
		- Una conclusión sobre la guía proporcionada
id:: 65c85f1c-95bf-4399-9ea8-6093aefa2071
-
id:: 65c85fc2-fd13-4ae3-b0fd-3e1da07382a5
- # RACI
	- # Título
	  template:: RACI
		- Grupo:: Indica el grupo al que pertenece mediante una tag, tags - #tags
		  subgrupo:: Indica el subgrupo con una tag - #tags
		  Tipo:: #RACI
		- | Actividad|     R      |  A | C | I |
		  |----------|:-------------:|------:|------:|------:|
		  | Actividad 1|  Responsable| Aprobador| Consultado | Informado |
		  | Actividad 2 |    Responsable   |   Aprobador| Consultado | Informado  |
		  | Actividad 3 | Responsable |    Aprobador | Consultado | Informado  |
-
- # Persona
- # Nombre persona
  template:: Persona
	- Grupo:: Indica el grupo al que pertenece mediante una tag, tags - #tags
	  subgrupo:: Indica el subgrupo con una tag - #tags
	  Nivel:: Indica el nivel con una tag - #tags
	  Estatus:: Indica el estatus de la persona en la empresa - #Tags
	  Tipo:: #persona
	- ## Email
		- Email de la persona
	- ## Supervisor
		- Nombre de la persona que supervisa
	- ## Horario
		- | L| M |  M | J | V |
		  |- |:--:|---:|--:|--:|
		  | Horario |  Horario| Horario| Horario| Horario|
-
- # Herramienta
- # Nombre herramienta
  template:: Herramienta
	- Grupo:: Indica el grupo al que pertenece mediante una tag, tags - #tags
	  subgrupo:: Indica el subgrupo con una tag - #tags
	  Nivel:: Indica el nivel de dificultad de la herramienta con una tag - #tags
	  Tipo:: #herramienta
	- ## Costo
		- Costo de la herramienta
	- ## Función
		- Función que realiza la herramienta
	- ## Comentarios
		- Comentarios a tomar en cuenta sobre la herramienta
	- ## Documentación
		- Link a la documentación
-
- # Equipo
- # Nombre del equipo
  template:: Equipo
	- Tipo:: #equipo
	  Grupo:: Indica el grupo al que pertenece mediante una tag, tags - #tags
	  subgrupo:: Indica el subgrupo con una tag - #tags
	- ## Integrantes
		- Integrante 1
		- Integrante 2
		- Integrante 3
	- ## Responsable
		- Responsable del proyecto
	- ## Proyecto
		- Proyecto asignado al equipo
-
- # Política
- # Título de la política
  template:: Política
	- Estado:: Indica si la política esta vigente o no mediante una tag - #Tags
	- Tipo:: #política
	- ## Descripción
		- Descripción de la política
	- ## Fecha de creación
		- Fecha de la creación de la política
	- ## Nota
		- Alguna nota sobre la política a tomar en cuenta
-
- # Fuente de información
- # Título de la fuente de información
  template:: Fuente de información
	- Estatus:: Indica si esta activa o no la fuente de la información - #Tags
	- Tipo:: [[#Fuente de información]]
	- ## Información sobre grupos
		- Información que se puede saber sobre los grupos dada la fuente de información
	- ## Información sobre subgrupos
		- Información que se puede saber sobre los subgrupos dada la fuente de información
	- ## Información sobre proyectos
		- Información que se puede saber sobre los proyectos dada la fuente de información
	- ## Información sobre personas
		- Información que se puede saber sobre las personas dada la fuente de información
- # Issue
- # Titulo del issue
  template:: Issue
	- Grupo:: Indica el grupo al que pertenece mediante una tag, tags - #tags
	  subgrupo:: Indica el subgrupo con una tag - #tags
	  Estado:: Estado del issue - #Tags
	  Paso:: Paso en el que esta el issue - #Tags
	  Tipo:: #issue
	- ## Objetivo
		- Objetivo u objetivos del issue
	- ## Plan
		- Acción 1
		- Acción 2
		- Acción 3
	- ## Entregables
		- Los entregables del issue
	- ## Testing
	- ## Recursos
	-