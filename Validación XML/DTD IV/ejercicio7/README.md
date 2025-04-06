# Ejercicio 7: Corrección de errores en XML

## Descripción
Este archivo XML representa una lista de músicos. Incluye una definición DTD interna que valida la estructura del documento.

## Estructura
- **Elemento raíz**: `<musicos>`  
  Contiene una lista de músicos.

- **Elementos secundarios**:
  - `<musico>`: Representa un músico con los siguientes subelementos:
    - `<nombre>`: Nombre del músico (obligatorio).
    - `<apodo>`: Apodo del músico (opcional).
    - `<fechaNacimiento>`: Fecha de nacimiento del músico (obligatorio).

## Validación
El archivo incluye una DTD interna que define:
- `<musicos>` puede contener cero o más `<musico>`.
- `<musico>` debe contener `<nombre>` y `<fechaNacimiento>`, y opcionalmente `<apodo>`.

## Ejemplo
```xml
<musicos>
    <musico>
        <nombre>Antonio Vivaldi</nombre>
        <apodo>El cura pelirrojo</apodo>
        <fechaNacimiento>4 de marzo de 1678</fechaNacimiento>
    </musico>
</musicos>
```
