# Tema 1. Introducción a las arquitecturas de software
# Introduction to software architectures

## Introducción / Introduction
- Los sistemas cada vez tienen mayores requisitos / System are increasingly demanding requirements.

- La problemática **no solo afecta a la operación** del sistema, sino también al **modo en que se plantea su desarrollo** (visión _metodológica_) /
The problem not only affects to the system's operation but also the way its development is planned. (Methodological vision)

- Debemos definir **cómo organizamos el sistema** para satisfacer estos requisitos, tanto desde el punto de vista **hardware** como **software**
/ _its necessaty to define how to organize the system to meet the requirements, either from the point of view of hardware and software_


## Proceso de diseño de software / The process of software design 

### ¿Qué es diseño de software? / What is software design?

- Diseño es el **proceso creativo / creative process**  de transformar un problema en una solución. La descripción de esta **solución** también se llama diseño.
- El diseño de software es el proceso de **modelar y especificar / conceving (modelign) and especifying** los detalles de cómo el sistema cumplirá las **especificaciones de requerimientos**  establecidas en el análisis.
  
### Fases del proceso creativo

#### 1. Preparación
Identificación del problema
1. Selección e identificación del objeto creativo sobre el que trabajar. / select the creative object to work on
2. Recopilación de información relacionada con el objeto. / Compilation of object-related information
3. Experimentación y búsqueda de alternativas. / Searching for alternatives.

#### 2. Incubación
Tiempo de reflexión no consciente
1. Periodo de descanso, no se trabaja de forma consciente, pero se lleva a cabo otro tipo de elaboración no consciente / Rest period
2. El inconsciente sigue trabajando / The subconscious keeps working

#### 3. Insipiración
Intuición de que la solución está cerca
1. Aparecen ideas que sabemos que están cerca / Ideas come up so we know we are close to the solution.

#### 4. Iluminación
La idea emerge
1. La idea surge en el momento menos pensado. _Las tres B: Bus, Bed; Bath_ 
 
#### 5. Verificación
Desarrollo y evaluación de la solución
1. Verificamos si la idea es valiosa / We chech wether the idea is good enough.
2. Realización de pruebas, si no es válida, se considera una nueva fase de inspiración / Perform some test and consider as an inspiration stage in case it is an invalid solution


### Diseño de software
- ***THERE IS NO SINGLE SOLUTION***
- Diseño == proceso creativo
- Diseño == solución
- No existe una solución completamente óptima, sino soluciones buenas, mediocres, malas
  - Dependiendo del cliente, requerimientos, diseñador.

### Principios básicos del diseño [Pressman]
- No debe realizarse con las _"orejeras"_ puestas. / Open mind, shouldnt be done with the earmuffs on
- Deberá ser rastreable hasta el modelo de análisis. / It must be traceable to the analysis model.
- Evitar reinventar la rueda. / Avoid re-inventing the wheel.
- Minimizar la distancia intelectual entre el software y el ingeniero software. / Minimize the intellectual gap between the softweare engineer amd the software itself.
- Deberá presentar uniformidad e integración. Uniformity and integration.
- Deberá estructurarse para admitir cambios. / Accept changes.
- Deberá estructurarse para degradarse poco a poco, incluso ante sucesos y condiciones extremadamente aberrantes. / Degrade little by little.
- Escibir código != diseñar.
- Diseñar != escribir código.
- Deberá evaluarse conforme se desarrolla, no al final. / Should be evaluated as it is edveloped, not at the end.
- Deberá revisarse frente a errores conceptuales (semánticos). / It should be checked against conceptuals errors. 


## Concepto de arquitectura
### Arquitectura de un sistema
- Define la **división  y estructura** de un sistema en **subsistemas** y establece un **marco de control**, **comunicación y cooperación** entre los distintos subsistemas.
- Define the **division and structure** of a system in subsystem and the relationships with ther enviroment and the fundamental principles that govern its design and evolution.

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


