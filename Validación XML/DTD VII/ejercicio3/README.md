# Ejercicio 3: Cosas por Hacer

Este archivo XML contiene una lista de tareas pendientes. Cada tarea incluye los siguientes atributos:

- **fecha**: La fecha en que se registró la tarea.
- **asunto**: Una breve descripción del asunto de la tarea.
- **fechaLimite**: La fecha límite para completar la tarea.

El archivo utiliza una definición de tipo de documento (DTD) para validar su estructura. La DTD asegura que:

- El elemento raíz es `cosasPorHacer`, que contiene una lista de elementos `cosa`.
- Cada elemento `cosa` tiene contenido de texto y los atributos `fecha`, `asunto` y `fechaLimite`, todos de tipo CDATA y obligatorios.
