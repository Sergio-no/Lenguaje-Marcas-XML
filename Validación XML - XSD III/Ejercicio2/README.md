# Ejercicio 2: Fichas

## Descripción
Este archivo XSD define un esquema para representar fichas con un nombre y una clave alfanumérica.

## Estructura
- **Elemento principal:** `fichas`
  - Contiene una secuencia de elementos `ficha`.
- **Subelementos de `ficha`:**
  - `nombre`: Nombre de la ficha.
  - `clave`: Clave alfanumérica con longitud entre 4 y 10 caracteres.

## Uso
Este esquema puede ser utilizado para validar documentos XML que describan fichas de usuarios, productos o registros.
