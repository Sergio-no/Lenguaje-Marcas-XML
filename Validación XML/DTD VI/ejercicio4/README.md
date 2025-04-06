# Ejercicio 4: Lista de la Compra

## Descripción
Este ejercicio define un archivo XML que representa una lista de la compra. Cada elemento de la lista tiene atributos como `nombre` y `cantidad`.

## Estructura DTD
- **Elemento `listaCompra`**: Contiene una lista de elementos `item`.
- **Elemento `item`**: Es vacío y tiene los atributos:
  - `nombre` (CDATA, obligatorio)
  - `cantidad` (CDATA, obligatorio)

## Notas
- Los elementos de la lista deben ser representados como `item`.
- Los atributos `nombre` y `cantidad` son obligatorios.
