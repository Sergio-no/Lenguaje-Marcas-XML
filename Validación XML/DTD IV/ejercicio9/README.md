# Ejercicio 9: Corrección de errores en XML

## Descripción
Este archivo XML representa un sistema solar con planetas y asteroides. El archivo incluye una definición DTD interna que valida la estructura del documento.

## Estructura
- **Elemento raíz**: `<sistemaSolar>`  
  Contiene una lista de planetas y asteroides.

- **Elementos secundarios**:
  - `<planeta>`: Representa un planeta del sistema solar.
  - `<asteroide>`: Representa un asteroide del sistema solar.

## Validación
El archivo incluye una DTD interna que define:
- `<sistemaSolar>` puede contener cero o más `<planeta>` y `<asteroide>`.
- `<planeta>` y `<asteroide>` contienen texto (#PCDATA).

## Ejemplo
```xml
<sistemaSolar>
    <planeta>Tierra</planeta>
    <planeta>Marte</planeta>
    <asteroide>Ceres</asteroide>
</sistemaSolar>
```
