# Ejercicio 8: Corrección de errores en XML

## Descripción
Este archivo XML representa una agenda de contactos. Incluye una definición DTD interna que valida la estructura del documento.

## Estructura
- **Elemento raíz**: `<agenda>`  
  Contiene una lista de contactos.

- **Elementos secundarios**:
  - `<contacto>`: Representa un contacto con los siguientes subelementos:
    - `<nombre>`: Nombre del contacto (obligatorio).
    - `<telefonofijo>`: Número de teléfono fijo (opcional).
    - `<telefonmovil>`: Número de teléfono móvil (opcional).

## Validación
El archivo incluye una DTD interna que define:
- `<agenda>` puede contener cero o más `<contacto>`.
- `<contacto>` debe contener `<nombre>` y opcionalmente `<telefonofijo>` y `<telefonmovil>`.

## Ejemplo
```xml
<agenda>
    <contacto>
        <nombre>Ayuntamiento</nombre>
        <telefonofijo>91 000 00 00</telefonofijo>
    </contacto>
</agenda>
```
