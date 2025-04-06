# Ejercicio 5: Álbumes de Mortadelo

Este archivo XML contiene una lista de álbumes de Mortadelo y Filemón. Cada álbum incluye los siguientes atributos:

- **nombre**: El título del álbum.
- **fecha**: El año de publicación del álbum.

El archivo utiliza una definición de tipo de documento (DTD) para validar su estructura. La DTD asegura que:

- El elemento raíz es `albumesMortadelo`, que contiene una lista de elementos `album`.
- Cada elemento `album` tiene los atributos `nombre` y `fecha`, ambos de tipo CDATA y obligatorios.
