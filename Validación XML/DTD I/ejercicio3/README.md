# Ejercicio 3: Información de Agenda Personal

**Autor:** Sergio Negro Oliva  
**Curso:** 1ºDAM  
**Fecha:** 30/03/2025  

## Descripción  
Este ejercicio almacena información personal en una agenda dentro de un archivo XML. La agenda contiene datos como nombre, apellidos, teléfono, fecha de nacimiento y lugar de nacimiento. 

## Estructura del XML  
- `<agenda>`: Elemento raíz que contiene la información personal.  
  - `<nombre>`: Nombre de la persona.  
  - `<apellido>`: Primer apellido de la persona.  
  - `<apellido>`: Segundo apellido de la persona.  
  - `<telefono>`: Número de teléfono de la persona.  
  - `<fecha_nacimiento>`: Contiene la información de la fecha de nacimiento.  
    - `<anio>`: Año de nacimiento.  
    - `<mes>`: Mes de nacimiento.  
    - `<dia>`: Día de nacimiento.  
  - `<lugar_nacimiento>`: Contiene la información del lugar de nacimiento.  
    - `<pais>`: País de nacimiento.  
    - `<ciudad>`: Ciudad de nacimiento.  
    - `<localidad>`: Localidad de nacimiento.  