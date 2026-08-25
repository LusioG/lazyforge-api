#  LazyForge - API y Generador (Backend)

Este repositorio contiene la lógica del servidor y el motor de generación para **LazyForge**, la herramienta para crear mods de Minecraft 1.21.1 sin programar.

Aquí se alojan los scripts que procesan las solicitudes y ensamblan los archivos necesarios (`zipAssembler.js`, `pathBuilder.js`, etc.) para entregar el mod listo para compilar.

 **[¡Prueba la herramienta visual aquí!](https://luchidev17.github.io/lazyforge-web/)**


## 🛠️ Estructura Principal

*   `server.js`: El punto de entrada principal de la API.
*   `/generator/`: Contiene los scripts y plantillas base (como Gradle y Java) que ensamblan la estructura del mod dinámicamente.
