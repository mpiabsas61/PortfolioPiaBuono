# Portfolio Personal - IFTS 16 (Práctica Formativa 1 y 2)

Este proyecto es la página de presentación personal y portfolio web desarrollada para la materia **Desarrollo Web Frontend** del **IFTS 16**. El objetivo principal es aplicar conceptos avanzados de maquetación semántica con HTML5, estilos CSS3, Flexbox y diseño responsivo adaptado a múltiples dispositivos.

---

## 📸 Vista Previa

<img src="assets/img/sample.png" alt="Muestra del Portfolio Web" width="100%">

---

## 🚀 Características del Proyecto

* **Maquetación Semántica HTML5:** Estructurado utilizando etiquetas semánticas (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`) para mejorar la accesibilidad y el SEO.
* **Secciones Integradas:**
  * **Sobre mí:** Presentación personal e imagen de perfil.
  * **Qué hago:** Descripción detallada de servicios y áreas de especialización en bloques independientes.
  * **Tecnologías:** Tabla estilizada con pseudoclases (`nth-child`) para enumerar habilidades y tecnologías a aprender.
  * **Contacto:** Formulario completo con campos de Nombre, Apellido, Email, Teléfono y botón de envío con ícono.
* **Diseño Responsivo (4 Breakpoints):**
  * `1080px` - Tablet horizontal / Laptop.
  * `768px` - Tablet vertical.
  * `480px` - Mobile estándar.
  * `375px` - Mobile compacto.
* **Estilos Avanzados en CSS:**
  * Uso de **Flexbox** para la disposición horizontal y vertical de elementos.
  * Centrado mediante `margin: 0 auto` y Flexbox.
  * Control de opacidad e implementación de `z-index`.
  * Combinadores CSS (directo `>` y descendente) para evitar el sobreuso de clases e IDs.
  * Estilado completo de enlaces con pseudoclases (`:link`, `:visited`, `:hover`, `:active`).

---

## 📁 Estructura del Proyecto

```text
/
├── index.html          # Archivo principal de la página web
├── README.md           # Documentación del proyecto
├── css/
│   └── styles.css      # Hoja de estilos externa bien organizada y comentada
└── img/            # Imágenes comprimidas e íconos (< 500 KB)
        ├── pia.png
        └── sample.png  # Captura de pantalla del proyecto
