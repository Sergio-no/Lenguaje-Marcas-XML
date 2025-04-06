# Ejercicio 4: Corrección de errores en XML

## Descripción
Este archivo XML representa una lista de flores. Incluye una definición DTD interna que valida la estructura del documento.

## Estructura
- **Elemento raíz**: `<flores>`  
  Contiene una lista de flores.

- **Elementos secundarios**:
  - `<flor>`: Representa una flor. Contiene texto (#PCDATA).

## Validación
El archivo incluye una DTD interna que define:
- `<flores>` puede contener cero o más `<flor>`.
- `<flor>` contiene texto (#PCDATA).

## Ejemplo
```xml
<flores>
    <flor>Rosa</flor>
</flores>
```
