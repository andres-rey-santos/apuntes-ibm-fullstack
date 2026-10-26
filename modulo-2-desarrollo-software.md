# Apuntes del Módulo 2: Desarrollo de Software

## Desarrollo Web y la Nube

- **Comunicación entre cliente y servidor:** El usuario utiliza un navegador para ingresar una URL que solicita información a un servidor.
- El servidor responde enviando HTML (estructura), CSS (estilo) y JavaScript (interactividad) para mostrar el sitio web.

## Desarrollo Front-end y Back-end

- **El Front-end** se encarga de lo que el usuario ve e interactúa, usando HTML, CSS y JavaScript.
- **El Back-end** maneja la lógica, funcionalidad y seguridad en el servidor, trabajando con bases de datos.

### Front-End
- **Lenguajes básicos para crear sitios web:**
  - **HTML:** Crea la estructura física del sitio, incluyendo texto, enlaces, imágenes y botones.
  - **CSS:** Se usa para diseñar y estilizar el sitio, además de la compatibilidad entre navegadores y dispositivos.
- **Interactividad y tecnologías:**
  - **JavaScript:** Añade interactividad como funcionalidad de botones y carga rápida.
  - **Lenguajes como SASS y LESS:** Extienden CSS para facilitar la organización y creación de estilos.

### Back-End
- **Rol del desarrollador:**
  - Gestiona los recursos y la infraestructura del servidor para responder a las solicitudes de los usuarios.
  - Trabaja en conjunto con desarrolladores frontend para asegurar la interacción adecuada entre cliente y servidor.
- **Funciones:**
  - Procesar datos de entrada como búsquedas, autenticación de usuarios y pagos en línea.
  - Asegurar la seguridad y almacenamiento adecuado de información sensible.
- **Tecnologías y herramientas:**
  - Utilizar APIs, rutas y endpoints para manejar las solicitudes del frontend.
  - Emplea lenguajes como JavaScript (Node.js, Express) y Python (Django, Flask), además de bases de datos y SQL para gestionar datos.

## Diseños y Frameworks

- Los sitios pueden ser **reactivos** (adaptados a diferentes tipos de pantalla) o **responsivos** (se ajustan automáticamente al dispositivo).
- **Frameworks y JavaScript** como Angular, React.js y Vue.js ayudan a construir sitios eficientes, escalables y con componentes reutilizables.
- Los desarrolladores deben actualizar constantemente sus habilidades para asegurar que los sitios funcionen en múltiples navegadores, sistemas operativos y dispositivos.

## ¿Qué es HTML?

**Hypertext Markup Language**. Es un lenguaje que se utiliza para crear la estructura física de un sitio web. Su función principal en el desarrollo web es definir y organizar los elementos básicos de una página, como texto, enlaces, imágenes, videos, divisores de página y botones.

**Ejemplo de interacción (HTML, CSS, JS):**
- **HTML:** Crea el botón en la página.
- **CSS:** Le da estilo visual al botón.
- **JavaScript:** Añade funcionalidad, como responder al clic para iniciar sesión, mostrar un mensaje o enviar datos.

## Frameworks de JavaScript

Un framework de JavaScript es un conjunto de herramientas y bibliotecas predefinidas que facilitan el desarrollo de aplicaciones web.
- Organizar y reutilizar código.
- Crear sitios web rápidos.
- Mejorar funciones como la navegación.

## API (Interfaz de Programación de Aplicaciones)

Es un conjunto de reglas y protocolos que permite que diferentes programas o componentes de software se comuniquen entre sí. Las APIs permiten que el Front-end y el Back-end se conecten para obtener datos, enviar información o ejecutar acciones, facilitando la interacción entre cliente y servidor.

## Trabajo en Equipo

Un equipo de trabajo es un grupo de personas con habilidades diversas que trabajan hacia un objetivo común. El trabajo en equipo mejora la calidad del código, reduce errores y disminuye el estrés.

### Squads
Son grupos de trabajo de hasta 10 personas que practican programación en pareja y se enfocan en desarrollar, implementar y probar características del producto de manera colaborativa.

### Comunicación y Colaboración (Estilos de programación en pareja)
- **Driver - Navigator:** Un desarrollador escribe el código (driver) mientras el otro revisa y guía (navigator) intercambiando roles.
- **Ping-Pong:** Basado en desarrollo guiado por pruebas. Al terminar, entre escribir pruebas y código para pasar esas pruebas.
- **Estilo Fuerte:** El desarrollador menos experimentado escribe el código mientras el más experimentado guía y explica sus ideas sin interrupciones.

### Beneficios
- Facilita la transferencia de conocimiento entre devs.
- Mejora la calidad del código.
- Fomenta habilidades blandas como comunicación y colaboración.

### Desafíos
- Requiere concentración prolongada.
- Puede haber desequilibrios en personalidades.

## Herramientas de Desarrollo de Apps

### Control de Versiones
- Permite rastrear cambios en el código, saber quién y cuándo lo hizo, y resolver conflictos.
- **Git y GitHub** son ejemplos populares que almacenan el código en repositorios; permiten crear ramas para desarrollo paralelo.

### Bibliotecas de Código
- Son colecciones de código reutilizable que facilitan agregar funcionalidades específicas sin tener que programarlas desde cero.
- **Ejemplos:** jQuery para manipulación del DOM y Apache Commons para componentes de Java reutilizables.

### Frameworks
- Proveen una estructura estándar para construir aplicaciones, definiendo la arquitectura y el flujo de programa.
- Son menos flexibles que las bibliotecas, controlan el desarrollo mediante la **inversión del control** y suelen incluir sus propias bibliotecas. Ejemplos: AngularJS, Vue.js y Django.
- **La inversión del control** en framework significa que el framework, y no el desarrollador, controla el flujo del programa.

### CI/CD y Automatización
- **CI (Integración Continua):** Asegura que los componentes de código funcionen juntos.
- **CD (Despliegue/Entrega Continua):** Despliega automáticamente los cambios a entornos de prueba o staging.
- Permite a los equipos entregar cambios frecuentes y confiables mediante la automatización de la integración, pruebas y despliegue de código.

### Herramientas de Construcción (Build Tools)
- Transforman el código fuente en binarios listos para instalar, gestionan dependencias y automatizan tareas como compilación, pruebas y despliegue.
- Existen utilidades de construcción que generan artefactos y servidores de construcción que ejecutan estas utilidades de forma programada o bajo demanda. Ejemplos: Webpack, Babel y Web Assembly.

### Paquetes y Gestores de Paquetes
- Los paquetes agrupan los archivos de la aplicación junto con instrucciones y metadatos para facilitar la instalación y distribución.
- Los gestores de paquetes automatizan la búsqueda, instalación, actualización y gestión de dependencias de software.
- **Ejemplos:** npm para JavaScript, Pip para Python, Maven para Java.

## Pilas de Software (Software Stacks)

- Una pila de software incluye tecnologías como lenguaje de programación, frameworks, servidores y bases de datos que trabajan juntas para soportar una aplicación.
- **Pilas simples (3 capas):**
  1. Presentación
  2. Lógica de negocio
  3. Datos
- **Pilas complejas** (incluyen): Virtualización, Seguridad, Redes.

### Ejemplos de Pilas de Software
- **Python-Django:** Usa Python y el framework Django. Ideal para aplicaciones web grandes y dinámicas.
- **Ruby on Rails:** Combina Ruby con un framework para aplicaciones web, útil para manejo de datos en JSON o XML.
- **ASP.NET:** Utiliza tecnologías Microsoft como ASP.NET MVC, IIS, SQL Server y Azure.

### Comparación de Pilas Populares: LAMP, MEAN y MEVN
- **LAMP (Linux, Apache, MySQL, PHP):** Es una pila clásica, abierta y flexible, pero menos adaptable a datos no estructurados y con diferentes lenguajes en front-end y back-end.
- **MEAN (MongoDB, Express.js, AngularJS, Node.js):** Usa JavaScript en toda la pila, facilitando el desarrollo rápido y el uso de módulos reutilizables, aunque puede ser menos adecuado para aplicaciones muy grandes.
- **MEVN:** Es similar a MEAN pero reemplaza AngularJS con Vue.js, que es más ligero y puede ofrecer mejor rendimiento, aunque con menos bibliotecas disponibles.

### Ventajas y Desafíos de las Pilas
- Las pilas abiertas como MEAN y LAMP ofrecen bajo costo y gran comunidad de soporte.
- La uniformidad del lenguaje en MEAN y MEVN facilita el desarrollo, mientras que LAMP puede ser más rígida por su dependencia a Linux.
- La elección de pila depende del tipo de aplicación, datos a manejar, y preferencias del equipo de desarrollo.