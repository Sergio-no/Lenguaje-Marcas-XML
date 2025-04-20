# Ejercicio 4: Ubicaciones

## Descripción
Este archivo XSD define un esquema para representar ubicaciones con una dirección cardinal (norte, sur, este, oeste) y una distancia en metros.

## Estructura
- **Elemento principal:** `ubicaciones`
  - Contiene una secuencia de elementos `ubicacion`.
- **Atributos de `ubicacion`:**
  - `metros`: Distancia en metros (obligatorio).
- **Tipos definidos:**
  - `direccion`: Define las direcciones cardinales permitidas.

## Uso
Este esquema puede ser utilizado para validar documentos XML que describan ubicaciones geográficas o posiciones relativas.
