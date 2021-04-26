 # Especificacion de componentes.
 
 ## Objetivos.
 
 - Identificar el conjunto inicial de interfaces de negocio para los componentes de negocio
 - Identificar el conjunto inicial de interfaces del sistema para los componentes del sistema
 - Unir todos los elementos en la arquitectura de componentes.

## Especificacion de componentes. ****PREGUNTAR SI SOLO SON 2 CONTRATOS*****
- Los sistemas se crean por componentes y se unen por interfaces
  - **Usage contract**: Contratos de las interfaces.
  - **Realization contract**: Contratos de los componentes.

## IIM.
1. Crear un IIM.
    - Este en un modelo obtenido del BTM, por eso lo necesitamos. Representa la informacion que va a ser usada por cada componente.
    - Se crea uno por interfaz de negocio.
    - Tenemos que tener en cuenta los invariantes. Estos son restricciones junto a un tipo que debe ser cierta para todas las instancias 
      del tipo. (Indicadores de multiplicidad)
    
2. Crear un snapshot, para check que todo este bien.
   - Una snapshot sirve para comparar el sistema antes y despues de una operacion. Para comprobar que todo este almacenado correctamente.
      Para hacerlo, debemos tener los procesos realizados anteriormente.
      
## System interfaces
  - Debemos especificar las interfaces no solo del negocio sino tmb del sistema. Por que los contractos estan asociados a todas las interfaces
  - no solo a las de negocio.
  - Pasos para definirlas.
    - Empezamos con el BTM y creamos un IIM para cada interfaz del sistema. Se muestran las interfaces y los atributos de cada type que las requieren.
    - Refractor, si tenemos 2 interfaces si las comparamos, podemos ver que mucha de la información que aparece en 1, se repite en la otra, para quitar esta redundancia
      refactorizamos de manera que creemos una nueva interfaz que esta dividida en 2, (mediante flecha tipo herencia). Que informacion va a ser representada por esta
      tercera? todo lo que se repita.
   
Una vez que terminemos tenemos las interfaces, y las especificaciones de los componentes y la arquitectura.
    
