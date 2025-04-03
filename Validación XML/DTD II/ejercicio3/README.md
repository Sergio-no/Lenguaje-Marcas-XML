# Ejercicio 3: Aeropuerto

**Autor:** Sergio Negro Oliva  
**Curso:** 1ºDAM  
**Fecha:** 30/03/2025  

## Descripción  
Este ejercicio almacena información sobre vuelos en un aeropuerto en un archivo XML. Cada vuelo contiene datos como el código del vuelo, el estado, el origen, el destino, las horas de salida y llegada, y si es un vuelo diario.  

## Estructura del XML  
- `<aeropuerto>`: Elemento raíz que contiene la información del aeropuerto.  
  - `<nombre>`: Nombre del aeropuerto.  
  - `<fecha>`: Fecha de registro de los vuelos.  
  - `<vuelos>`: Contiene la lista de vuelos.  
    - `<vuelo>`: Representa un vuelo específico.  
      - **Atributos**:  
        - `codigo`: Código identificativo del vuelo.  
        - `estado`: Estado del vuelo (E = En horario, R = Retrasado, C = Cancelado).  
      - `<origen>`: Ciudad de origen del vuelo.  
      - `<destino>`: Ciudad de destino del vuelo.  
      - `<hora-salida>`: Hora de salida del vuelo.  
      - `<hora-llegada>`: Hora de llegada del vuelo.  
      - `<diario>`: Indica si el vuelo es diario (opcional).  
