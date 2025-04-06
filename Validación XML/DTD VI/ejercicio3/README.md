# Ejercicio 3: Cuadros

## Descripción
Este ejercicio define un archivo XML que representa una colección de cuadros. Cada cuadro tiene atributos como `titulo` y `autor`.

## Estructura DTD
- **Elemento `cuadros`**: Contiene una lista de elementos `cuadro`.
- **Elemento `cuadro`**: Es vacío y tiene los atributos:
  - `titulo` (ID, obligatorio)
  - `autor` (CDATA, obligatorio)

## Notas
- Los valores del atributo `titulo` deben ser únicos.
- Se corrigió un error donde dos cuadros tenían el mismo `titulo`.
