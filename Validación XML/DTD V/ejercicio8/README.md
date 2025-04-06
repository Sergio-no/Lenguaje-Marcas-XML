# Ejercicio 8: Validación XML

## Descripción
Este ejercicio define una estructura XML para almacenar apuntes contables, que pueden ser ingresos o gastos.

## Estructura del DTD
- **contabilidad**: Elemento raíz que contiene 0 o más elementos `apunte`.
- **apunte**: Contiene un único elemento `ingreso` o `gasto`.
- **ingreso**: Contiene los elementos `fecha`, `cantidad` y `concepto`.
- **gasto**: Contiene los elementos `fecha`, `cantidad` y `concepto`.
- **fecha**: Texto que representa la fecha del apunte.
- **cantidad**: Texto que representa la cantidad del apunte.
- **concepto**: Texto que describe el concepto del apunte.

## Notas
El archivo XML actual cumple con la definición del DTD.
