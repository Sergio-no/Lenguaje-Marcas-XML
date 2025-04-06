# Ejercicio 4: Resoluciones

Este archivo XML contiene una lista de resoluciones de pantalla. Cada resolución incluye los siguientes atributos:

- **nombre**: El nombre de la resolución.
- **alto**: La altura en píxeles.
- **ancho**: El ancho en píxeles.

El archivo utiliza una definición de tipo de documento (DTD) para validar su estructura. La DTD asegura que:

- El elemento raíz es `resoluciones`, que contiene una lista de elementos `resolucion`.
- Cada elemento `resolucion` tiene los atributos `nombre`, `alto` y `ancho`, todos de tipo CDATA y obligatorios.
