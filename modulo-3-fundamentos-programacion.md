# Apuntes del Módulo 3: Fundamentos de la Programación

## Lenguajes de Programación Interpretados

- Son lenguajes cuyo código se ejecuta mediante un intérprete que traduce el código legible por humanos a código máquina en tiempo real.
- **Ejemplos:** Python, JavaScript, HTML y Lua. Son versátiles y pueden ejecutarse en diferentes plataformas.

## Lenguajes de Programación Compilados

- El código fuente se traduce completamente a código máquina y se empaqueta en un archivo ejecutable que se puede ejecutar directamente en el dispositivo.
- Lenguajes como C, C++, C# y Java son compilados y se usan para programas complejos como sistemas operativos y aplicaciones grandes.

### Proceso y Uso
- **Los lenguajes interpretados:** Son ideales para scripts repetitivos y tareas que requieren flexibilidad.
- **Los lenguajes compilados:** Son preferidos para programas que requieren mayor rendimiento y se ejecutan directamente en el hardware del dispositivo.

## Niveles de Lenguajes de Programación

- **Lenguajes de alto nivel:** Son más sofisticados, usan lenguaje cercano al inglés y facilitan la codificación y la depuración. Ejemplos: Java, Pascal y Python.
- **Lenguajes de bajo nivel:** Usan símbolos que representan código máquina, como los lenguajes ensambladores ARM, MIPS y X86.

## Lenguajes de Consulta

- Un lenguaje de consulta permite solicitar y manipular datos en bases de datos, siendo **SQL** el más común, aunque existen otros como AQL, CQL y Datalog.
- Las bases de datos pueden ser **SQL** (relacionales, con esquemas estructurados) o **NoSQL** (no relacionales, con esquemas dinámicos). Las operaciones **CRUD** (crear, leer, actualizar, eliminar) son fundamentales.

## Lenguajes Ensambladores

- Los lenguajes ensambladores son específicos para cada arquitectura de procesador y traducen instrucciones simbólicas a código máquina mediante un ensamblador.
- Cada instrucción en ensamblador corresponde a una instrucción máquina, usando mnemónicos como `INP`, `OUT`, `LDA`, `STA`, `ADD`, con una sintaxis simple y legible.

## Métodos de Organización del Código

### Importancia de la organización del código
- Organizar el código facilita su lectura, mantenimiento y configuración, además de reducir errores y mejorar la calidad del software.
- Planificar el diseño del software antes de programar ayuda a mantener un formato lógico y consistente.

### Diagramas de Flujo y Pseudocódigo
- **Los diagramas de flujo** representan visualmente un algoritmo mediante símbolos y flechas que indican el orden de los pasos, siendo útiles para problemas pequeños y comunicación inicial.
- **El pseudocódigo** es una descripción informal y de alto nivel de un algoritmo que se asemeja a la lógica del código real, ideal para proyectos grandes y para compartir ideas sin depender de un lenguaje específico.

### Ventajas y Características
- Los diagramas de flujo usan símbolos estándar para representar procesos, decisiones y datos, y existen programas que facilitan su creación y colaboración en equipo.
- El pseudocódigo es sencillo, enfocado en la lógica, fácil de modificar, comprensible para programadores y no programadores, y sirve como puente para traducir la lógica a cualquier lenguaje de programación.

### Símbolos en un Diagrama de Flujo
En un diagrama de flujo, un algoritmo se representa gráficamente mediante:
- **Símbolos (formas)** que indican diferentes tipos de acciones o pasos como:
  - **Inicio/Fin:** Óvalo o cápsula.
  - **Proceso:** Rectángulo.
  - **Decisión:** Rombo.
  - **Entrada/Salida de datos:** Paralelogramo.
- **Flechas** que conectan los símbolos y muestran el orden en que se ejecutan los pasos.