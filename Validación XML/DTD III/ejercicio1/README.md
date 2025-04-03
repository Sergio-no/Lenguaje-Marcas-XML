# Ejercicio 1: Cuentos

**Autor:** Sergio Negro Oliva  
**Curso:** 1ºDAM  
**Fecha:** 30/03/2025  

## Descripción  
Este ejercicio almacena información sobre cuentos en un archivo XML. Cada cuento contiene datos como el código, el título, el género, los personajes, la trama, etiquetas y el precio. El archivo XML está validado mediante un archivo DTD (`ejercicio1.dtd`).

## Estructura del XML  
El archivo XML sigue la siguiente estructura:  

- `<cuerpo>`: Elemento raíz que contiene la lista de cuentos.  
  - `<cuento>`: Representa un cuento específico.  
    - **Atributos**:  
      - `cod`: Código identificativo del cuento.  
      - `titulo`: Título del cuento.  
      - `genero`: Género del cuento (por ejemplo, fantasía, infantil).  
    - `<personajes>`: Contiene la lista de personajes del cuento.  
      - `<personaje>`: Representa un personaje del cuento.  
        - **Atributos**:  
          - `id`: Identificador único del personaje.  
          - `tipo`: Tipo de personaje (principal, antagonista, etc.).  
        - `<nombre>`: Nombre del personaje.  
        - `<genero>`: Género del personaje (M/F).  
        - `<descripcion>`: Descripción del personaje.  
        - `<descripcion_fisica>`: Descripción física del personaje (opcional).  
        - `<url>` o `<imagen>`: URL de una imagen del personaje (opcional).  
    - `<trama>`: Describe la trama principal del cuento.  
    - `<etiqueta>`: Etiqueta temática del cuento (por ejemplo, aventura, amistad).  
      - **Atributos**:  
        - `nombre`: Nombre de la etiqueta.  
    - `<precio>`: Precio del cuento.  
      - **Atributos**:  
        - `moneda`: Moneda en la que se expresa el precio (por ejemplo, USD).  
