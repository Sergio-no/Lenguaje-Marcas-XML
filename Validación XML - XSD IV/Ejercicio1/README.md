# Ejercicio 1 - Alumnos 1

Este ejercicio valida un archivo XML que describe la información de un alumno utilizando un esquema XSD.

## Archivos

- **Alumnos1.xsd**: Define la estructura y las restricciones del archivo XML.
- **Alumnos1.xml**: Contiene los datos de un alumno que se validan contra el esquema XSD.

## Descripción

El esquema XSD incluye:
- Elementos como `nombre`, `direccion` (con subelementos como `calle`, `numero`, etc.) y `telefono`.
- Un atributo obligatorio `dni` con un formato específico (`8 dígitos + 1 letra`).

El archivo XML proporciona un ejemplo de datos que cumplen con las reglas definidas en el esquema.
