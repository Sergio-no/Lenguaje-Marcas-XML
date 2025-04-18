# Ejercicio 2 - Alumnos 2

Este ejercicio amplía la validación de datos de alumnos con soporte para múltiples direcciones y teléfonos.

## Archivos

- **Alumnos2.xsd**: Define la estructura y las restricciones del archivo XML.
- **Alumnos2.xml**: Contiene datos de varios alumnos que se validan contra el esquema XSD.

## Descripción

El esquema XSD incluye:
- Elementos como `nombre`, `direccion` (con subelementos como `calle`, `numero`, etc.) y `telefono`.
- Soporte para múltiples direcciones y hasta 5 teléfonos por alumno.
- Un atributo obligatorio `dni` con un formato específico (`8 dígitos + 1 letra`).

El archivo XML proporciona ejemplos de datos que cumplen con las reglas definidas en el esquema.
