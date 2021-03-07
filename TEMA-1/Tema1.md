# Tema 1. Introducción a las arquitecturas de software

## Introducción
- Los sistemas cada vez tienen mayores requisitos
- La problemática **no solo afecta a la operación** del sistema, sino también al **modo en que se plantea su desarrollo** (visión _metodológica_)
- Debemos definir **cómo organizamos el sistema** para satisfacer estos requisitos, tanto desde el punto de vista **hardware** como **software**

## Proceso de diseño de software

### ¿Qué es diseño de software?
- Diseño es el **proceso creativo** de transformar un problema en una solución. La descripción de esta **solución** también se llama diseño.
- El diseño de software es el proceso de **modelar y especificar** los detalles de cómo el sistema cumplirá las **especificaciones de requerimientos** 
  establecidas en el análisis.
  
### Fases del proceso creativo

#### 1. Preparación
Identificación del problema
1. Selección e identificación del objeto creativo sobre el que trabajar.
2. Recopilación de información relacionada con el objeto.
3. Experimentación y búsqueda de alternativas.

#### 2. Incubación
Tiempo de reflexión no consciente
1. Periodo de descanso, no se trabaja de forma consciente, pero se lleva a cabo otro tipo de elaboración no consciente
2. El inconsciente sigue trabajando

#### 3. Insipiración
Intuición de que la solución está cerca
1. Aparecen ideas que sabemos que están cerca

#### 4. Iluminación
La idea emerge
1. La idea surge en el momento menos pensado. _Las tres B: Bus, Bed; Bath_ 
 
#### 5. Verificación
Desarrollo y evaluación de la solución
1. Verificamos si la idea es valiosa
2. Reakuzacuñib de pruebas, si no es válida, se considera una nueva fase de inspiración


### Diseño de software
- Diseño == proceso creativo
- Diseño == solución
- No existe una solución completamente óptima, sino soluciones buenas, mediocres, malas
- Dependiendo del cliente, requerimientos, diseñador.

### Principios básicos del diseño [Pressman]
- No debe realizarse con las _"orejeras"_ puestas.
- Deberá ser rastreable hasta el modelo de análisis.
- Evitar reinventar la rueda.
- Minimizar la distancia intelectual entre el software y el ingeniero software.
- Deberá presentar uniformidad e integración.
- Deberá estructurarse para admitir cambios.
- Deberá estructurarse para degradarse poco a poco, incluso ante sucesos y condiciones extremadamente aberrantes.
- Escibir código != diseñar.
- Diseñar != escribir código.
- Deberá evaluarse conforme se desarrolla, no al final.
- Deberá revisarse frente a errores conceptuales (semánticos).


## Concepto de arquitectura
### Arquitectura de un sistema
- Define la **división  y estructura** de un sistema en **subsistemas** y establece un **marco de control**, **comunicación y cooperación** entre los distintos subsistemas.

### Arquitectura de software
- **Organización fundamental** de un sistema encarnado en sus **componentes**, 
  las **relaciones entre ellos**, el ambiente y los **principios que orientan su diseño y evolución** 

### Propiedades emergentes de un sistema (COMPLETAR CON ANKI)
- Confiabilidad
- Rendimiento
- Extensibilidad
- Seguridad
- Eficiencia memoria/ejecución
- Escalabilidad
- Portabilidad
- Disponibilidad
- Reusabilidad
- Mantenibilidad
- Facilidad de prueba


### ¿Cuál es el impacto de la arquitectura de un sistema
- **Rendimiento**: 
  Si el **rendimiento es crítico**, debería existir tan **poca comunicación como sea posible entre los subsistemas**. **Predomina** el uso de
  **componentes de grano grueso frente a los de grano fino**.
- **Protección**:
  Si la **protección es crítica**, debería **estructurarse el sistema en capas**, con los recursos **más protegidos en las capas internas** y 
  **validando seguridad entre las capas**.
- **Seguridad**:




  











