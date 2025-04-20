# Ejercicio 5: Muebles

## Descripción
Este archivo XSD define un esquema para representar una lista de muebles. Cada mueble tiene un tipo (como armario, mesa o silla) y un color (como blanco, gris, negro o wengue).

## Estructura
- **Elemento principal:** `muebles`
  - Contiene una secuencia de elementos `mueble`.
- **Atributos de `mueble`:**
  - `color`: Define el color del mueble con valores restringidos.
- **Tipos definidos:**
  - `tipoMueble`: Define los tipos de muebles permitidos.
  - `tipoColorMueble`: Extiende `tipoMueble` añadiendo el atributo `color`.

## Uso
Este esquema puede ser utilizado para validar documentos XML que describan inventarios o catálogos de muebles.
