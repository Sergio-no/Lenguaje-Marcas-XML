# Ejercicio 5: Corrección de errores en XML

## Descripción
Este archivo XML representa una lista de animales. Incluye una definición DTD interna que valida la estructura del documento.

## Estructura
- **Elemento raíz**: `<animales>`  
  Contiene una lista de animales.

- **Elementos secundarios**:
  - `<animal>`: Representa un animal. Contiene texto (#PCDATA).

## Validación
El archivo incluye una DTD interna que define:
- `<animales>` puede contener cero o más `<animal>`.
- `<animal>` contiene texto (#PCDATA).

## Ejemplo
```xml
<animales>
    <animal>Caniche</animal>
    <animal>Siámes</animal>
</animales>
```
