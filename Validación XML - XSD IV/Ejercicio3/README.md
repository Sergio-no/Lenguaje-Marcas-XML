# Ejercicio 3 - Heladeria 1

Este ejercicio valida un archivo XML que describe helados con diferentes combinaciones de sabores y una fecha de fabricación.

## Archivos

- **Heladeria1.xsd**: Define la estructura y las restricciones del archivo XML.
- **Heladeria1.xml**: Contiene datos de helados que se validan contra el esquema XSD.

## Descripción

El esquema XSD incluye:
- Elección exclusiva entre sabores como `chocolate` o `fresa`, y `vainilla`, `turron` o `nata`.
- Restricciones en los valores de los sabores (entre 0 y 1000).
- Un atributo obligatorio `fabricación` con formato de fecha.

El archivo XML proporciona ejemplos de helados que cumplen con las reglas definidas en el esquema.
