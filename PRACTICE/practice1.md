# 8/03/2021

## CLEAN CODE AND SOLID PRINCIPLES
### BEST PRACTICES


#### Software rot

- Software rots as functionality increases and code is updraded.
- Cost per feature goes up. But Never reach functional celinig without rewriting. You will spend lot of time solving the problem non best practices isues.

##### Symptoms 
- Rigidity, is the tendency for software to change. A disign is rigid if a single change causes a cascade of subsequents modules.
- Fragility, if a made a change and suddenly the program break in many places. 
- Inmobility, is the inability to reuse softwarefrom other projects or from parts of the same project.
- Viscosity, appears in 2 forms
  - When a change is faced, it can be addressed by preserving the design or by hacking. When hacking is easier than mantainig the disgn.
  - Viscosity of environment comes about when the development environment is slow and inefficient.

##### Causes.
- One common aspect: inappropiate dependecy management of system modules.
  - It degrades the dependecy architecture.
  - Impossibility of software management.
- Another inmediate cause of degradiation is a chnge in requirements in a way that was not anticipated
  - Engineers are unfamilit with the initial design
  - Very rapid and unanticipated changes
  - Requirements document not updated
  
##### How do we prevent it?
- Code refractoring: design continuous improvement.
- Software tests (unit/integretion/contract tests).
- Regular code revision.
- Updated documentation, including comments in code
- Application of **design principles and best practices**.
- **¡Simplicity!**

### What is _"clean code"_?
- Can be ***easily undestood by the entire team***
- Must be readable and easy to improve ***by a developer different than the original one***.
- If code can be understood, it will be ***readable, changeable, extensible and maintenable***.

### How "clean code" is developed?
1. ADD FUNCTIONAL CODE
2. REFACTOR CODE

### General rules

#### Follow standard conventions
- Avoid non-standard notations. (Hungarian notation, variable underlining).

- Adapt to the conventions of wach language. lower case for attributes and methods, upper case for class names, etc.

- This is likely to be much better understood by the following programer.

- ***"KEEP IT SIMPLE STUPID"***, simpler is always better
  - Reduce complexity as much as possible.
 
- Apply the ***Boy scout rule*** -> _"Leave the campground cleaner than you found it"_.
  - When edition code, do not just add lines of code -> it increases technical debt _(Cost that somebody will pay in the future when you dont make things right)_.
  - Always **check** the code you edit, **refractor it** and **remove "code smells"** 
