# Ejercicio 3: Artículos

## Descripción
Este archivo XSD define un esquema para representar una lista de artículos con su nombre y precio.

## Estructura
- **Elemento principal:** `articulos`
  - Contiene una secuencia de elementos `articulo`.
- **Subelementos de `articulo`:**
  - `nombre`: Nombre del artículo.
  - `precio`: Precio del artículo con un atributo `moneda` obligatorio.

## Uso
Este esquema puede ser utilizado para validar documentos XML que describan catálogos de productos o listas de precios.
