# Ejercicio 6: Corrección de errores en XML

## Descripción
Este archivo XML representa una lista de escritores. Incluye una definición DTD interna que valida la estructura del documento.

## Estructura
- **Elemento raíz**: `<escritores>`  
  Contiene una lista de escritores.

- **Elementos secundarios**:
  - `<escritor>`: Representa un escritor con los siguientes subelementos:
    - `<nombre>`: Nombre del escritor (obligatorio).
    - `<nacimiento>`: Fecha de nacimiento del escritor (obligatorio).

## Validación
El archivo incluye una DTD interna que define:
- `<escritores>` puede contener cero o más `<escritor>`.
- `<escritor>` debe contener `<nombre>` y `<nacimiento>`.

## Ejemplo
```xml
<escritores>
    <escritor>
        <nombre>Mario Vargas Llosa</nombre>
        <nacimiento>28 de marzo de 1936</nacimiento>
    </escritor>
</escritores>
```
