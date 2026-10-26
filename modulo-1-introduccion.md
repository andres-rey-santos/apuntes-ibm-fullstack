# Apuntes del Módulo 1: Introducción a la Ingeniería de Software

## SDLC (Ciclo de Vida del Desarrollo de Software)

- **Definición:** Es un proceso sistemático para crear software de alta calidad dentro de un tiempo y presupuesto predecibles.
- **Propósito:** Minimizar riesgos y costos. Puede implementarse de forma iterativa para adaptarse a cambios.
- **Ventajas clave:**
  - Proporciona un proceso claro para el equipo, mejorando la eficiencia y reduciendo gastos.
  - Facilita la comunicación entre clientes, partes interesadas y el equipo de desarrollo.
  - Define roles y responsabilidades, evitando conflictos.
  - Permite iteraciones para incorporar nuevos requisitos y resolver problemas temprano.
- **Fases del SDLC:**
  1.  **Planificación:** Definir objetivos, alcance, recursos y cronograma.
  2.  **Análisis de requisitos:** Recopilar y documentar las necesidades del cliente.
  3.  **Diseño:** Crear la arquitectura y diseño del software.
  4.  **Pruebas:** Verificar que el software funcione correctamente.
  5.  **Implementación:** Desplegar el software para su uso real.
  6.  **Mantenimiento:** Realizar correcciones, mejoras y actualizaciones.

## Metodologías de Desarrollo de Software

- **Modelo secuencial o de cascada (Waterfall):** Método secuencial donde cada fase comienza solo después de completar la anterior. Sigue un flujo lineal (Planificación -> Diseño -> Desarrollo -> Pruebas -> Implementación). No permite volver atrás y hacer cambios. Es adecuado cuando los requisitos son claros.
- **Modelo secuencial en V:** También es secuencial, con fases de verificación descendentes y fases de validación ascendentes.
- **Modelo Ágil:** Enfoque iterativo y colaborativo que trabaja en ciclos cortos llamados **Sprints**, con entregas frecuentes de código funcional y retroalimentación continua. Se basa en cuatro valores clave:
  1.  Individuos e interacciones.
  2.  Software funcionando.
  3.  Colaboración con el cliente.
  4.  Respuesta al cambio.
- **Cambios en un proyecto usando Agile:**
  1.  Dividir el trabajo en sprints cortos.
  2.  Planificar al inicio de cada sprint.
  3.  Entregar versiones funcionales parciales.
  4.  Fomentar la comunicación continua.
  5.  Priorizar el backlog.

## Requisitos de Software

- **Proceso de recopilación de requisitos:** Se compone de 6 pasos: identificar interesados, establecer metas y objetivos, obtener requisitos, documentarlos, analizarlos y confirmarlos, y priorizarlos. La obtención se realiza mediante encuestas, entrevistas y cuestionarios.
- **Especificación de Requisitos de Software (SRS):** Es el proceso de recopilar y documentar el conjunto de requisitos que el software debe cumplir. Incluye descripciones detalladas como casos de uso y flujos de usuario. Es fundamental para definir qué debe hacer el software antes de pasar al diseño y desarrollo.
- **Categorías de requisitos:**
  - **Funcionales:** Describen las funciones específicas que el software debe realizar.
  - **Externos y de interfaz de usuario (UI):** Cómo interactúa el software con los usuarios u otros sistemas.
  - **Características del sistema:** Aspectos técnicos y operativos.
  - **No funcionales:** Relacionados con la calidad (rendimiento, seguridad, usabilidad).
- **Diferencia entre SRS y SySRS:**
  - **SRS (Software Requirements Specification):** Describe detalladamente las funcionalidades que el software debe tener. Es técnico y orientado al equipo de desarrollo.
  - **SySRS (System Requirements Specification):** Es más amplio que el SRS e incluye capacidades del sistema, interfaces, requisitos de políticas, regulaciones, personal, rendimiento, seguridad y hardware. Se enfoca en las necesidades y expectativas del usuario final.

## Niveles de Testing

- **Unitario:** Pruebas a nivel de funciones o módulos individuales.
- **Integración:** Pruebas que verifican la interacción correcta entre módulos combinados.
- **Sistema:** Pruebas en el sistema completo.
- **Aceptación:** Pruebas formales realizadas por los usuarios.

## Tipos de Testing

- **Testing Funcional:** Verifica que el software cumpla con los requisitos funcionales mediante pruebas de caja negra, enfocándose en entradas y salidas sin revisar el código interno.
- **Testing No Funcional:** Evalúa atributos como rendimiento, seguridad, escalabilidad y disponibilidad.
- **Testing de Regresión:** Confirma que cambios recientes (como correcciones de errores) no afecten funcionalidades existentes.

## Documentación de Software

- **Definición:** Es información que describe qué es un producto de software y cómo usarlo.
- **Tipos:**
  1.  Documentación de requisitos.
  2.  Documentación de diseño.
  3.  Documentación técnica.
  4.  Documentación de aseguramiento de calidad.
  5.  Documentación para usuarios.
- **Procedimientos Operativos Estándar (SOP):** Son instrucciones detalladas y específicas de la organización para realizar tareas complejas. Pueden presentarse como diagrama de flujo, esquemas jerárquicos o instrucciones paso a paso.

## Versiones de Software

- **Versionamiento y numeración:** Los números de versión indican cuándo se actualizó o corrigió un software.
- **Sistema de numeración sistemática:** En la numeración sistemática, el primer número indica cambios mayores, el segundo cambios menores, el tercero parches o correcciones, y el cuarto número o fecha de compilación. *No todos siguen este formato.*

## Roles en los Proyectos de Software

- **Project Manager o Scrum Master:** Asegura que el proyecto avance sin problemas.
- **Stakeholders:** Son quienes definen los requisitos del proyecto.
- **Roles técnicos:**
  - **Arquitecto de Software:** Diseña y comunica la arquitectura del proyecto.
  - **Diseñador UX:** Se enfoca en la experiencia de usuario.
- **Roles de desarrollo y calidad:**
  - **Desarrolladores:** Escriben el código siguiendo la arquitectura, requisitos y diseño UX.
  - **Testers o Ingenieros de QA:** Garantizan la calidad.
- **Roles de soporte:**
  - **Ingeniero de Confiabilidad de Sitio (SRE):** Combina ingeniería de software y gestión de sistemas para fiabilidad y automatización.
  - **Product Manager u Owner:** Lidera la visión del producto.
  - **Redactor Técnico:** Crea documentación para usuarios finales y ayuda a la comunicación.