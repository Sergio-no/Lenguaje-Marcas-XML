# Ejercicio 4: Alumnos de DAW

**Autor:** Sergio Negro Oliva  
**Curso:** 1ºDAM  
**Fecha:** 23/03/2025  

## Descripción  
Este ejercicio consiste en un archivo XML que almacena información sobre un módulo de DAW, incluyendo su nombre, horas semanales, características y una lista de alumnos matriculados.  

## Estructura del XML  
- `<modulo>`: Elemento raíz que contiene la información del módulo.  
  - `<nombre>`: Nombre del módulo.  
  - `<horas_semanales>`: Número de horas semanales de la asignatura.  
  - `<caracter>`: Indica si la asignatura es obligatoria u opcional.  
  - `<fecha_inicio>` y `<fecha_fin>`: Fechas de inicio y fin del curso.  
  - `<alumnos>`: Contiene la lista de alumnos matriculados.  
    - `<alumno>`: Cada alumno tiene los siguientes subelementos:  
      - `<nombre>`: Nombre completo del alumno.  
      - `<dni>`: Documento Nacional de Identidad del alumno.  
      - `<telefono>`: Número de teléfono de contacto.  
      - `<email>`: Correo electrónico del alumno.  
      - `<direccion>`: Dirección completa del alumno.  
      - `<notas>`: Calificación obtenida en el módulo.  
      - `<faltas>`: Número de faltas acumuladas durante el curso.  
