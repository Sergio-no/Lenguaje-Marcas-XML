# Ejercicio 4: Letras Admitidas

## Descripción
Este ejercicio define un esquema XML que valida cadenas formadas por pares de letras (una mayúscula seguida de una minúscula).

## Archivos
- **letrasAdmitidas.xsd**: Contiene la definición del esquema XML para validar las cadenas de letras admitidas.

## Uso
1. Utiliza el archivo `letrasAdmitidas.xsd` para validar documentos XML que contengan elementos `<letras>`.
2. Asegúrate de que las cadenas cumplan con el patrón definido (`[A-Z][a-z]`).

## Ejemplo de Uso
```xml
<letras>AbCdEf</letras>
```
