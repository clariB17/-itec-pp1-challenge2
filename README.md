# -itec-pp1-challenge2
desafío  interfaz API Rest
El desafío consiste en tener una aplicación que implemente un interfaz API Rest para la gestión de tareas.
Una tarea tiene como mínimo los siguientes campos:
título
descripción
fecha de creación 
fecha en que se completó.
el nombre de la persona que tiene asignada la tarea
estado de la tarea: NEW, ACTIVE, IN_PROGRESS, DONE,BLOQUED
La api debe contar con las siguientes operaciones: 
permitir crear, actualizar y borrar una tarea
obtener la lista de tareas
El proyecto debe estar en github, tener un README y estar documentado con swagger

Deseables
- que el proyecto tenga activado integración continua
- test unitarios (pytest u otro framework)
- las tareas pueden estar en una base de datos o sin persistencia (desaparecen cuando se detiene la aplicación)
