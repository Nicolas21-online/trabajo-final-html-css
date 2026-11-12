# 🏆 [Caciques F.C / Proyecto Web]

Sitio web oficial desarrollado como Trabajo Final del módulo de **HTML5 y CSS3**, diseñado para ofrecer una experiencia de usuario fluida, accesible, responsiva y optimizada.

---

## 🔗 Enlaces de Entrega

* **Repositorio público en GitHub:** [https://github.com/Nicolas21-online/trabajo-final-html-css](https://github.com/Nicolas21-online/trabajo-final-html-css)
* **Sitio web alojado en GitHub Pages:** [https://nicolas21-online.github.io/trabajo-final-html-css/](https://nicolas21-online.github.io/trabajo-final-html-css/)


---

## 📁 Estructura del Proyecto

El proyecto respeta estrictamente la arquitectura de carpetas y rutas relativas solicitada en el enunciado:

```text
trabajo-final-html-css/
├── favicon.ico
├── README.md
├── index.html
├── css/
│   └── estilos.css
├── views/
│   ├── contacto.html
│   ├── equipos.html
│   ├── Inscripcion.html
│   ├── galeria.html
└── assets/
    ├── favicon/
    └── img/
        └── [imágenes y recursos del proyecto]
```[cite: 19, 20]

---

## 📋 Descripción de las Vistas

* **Inicio (`index.html`):** Página principal del sitio web con estructura semántica (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`) y apartados diferenciados que presentan la identidad y finalidad del proyecto.
* **Galería (`views/galeria.html`):** Cuadrícula homogénea compuesta por 12 imágenes con dimensiones originales declaradas en HTML (`width` y `height`) y redimensionamiento visual gestionado íntegramente mediante CSS.
* **Inscripción (`views/Inscripcion.html`):** Formulario para solicitar la inscripción, con datos de contacto, un campo opcional para más información y aceptación de la política de privacidad.
* **Equipos (`views/equipos.html`):** Presentación de las categorías del club, desde Benjamín hasta Juvenil, con información sobre cada etapa.
* **Contacto (`views/contacto.html`):** Información detallada con la ubicación física de la entidad e imagen estática del mapa de localización.[cite: 17, 18, 20, 21]

---

## 🛠️ Características Técnicas y Cumplimiento de Normas

* **HTML5 Semántico y Validado:** Código limpio, correctamente indentado, comentado y validado mediante el **Validador W3C** sin errores ni advertencias.
* **CSS3 Centralizado:** Hoja de estilos única (`css/estilos.css`), sin estilos embebidos ni en línea, con diseño adaptable (*Responsive Design* mediante *Media Queries*), paleta de colores contrastada y *Sticky Footer* fijo en la parte inferior.
* **Rutas Relativas:** Todas las referencias a recursos internos, hojas de estilo y navegación utilizan rutas relativas para garantizar un funcionamiento idéntico en entorno local y en GitHub Pages.[cite: 17, 18, 20, 22, 23]

---

## 📊 Auditoría de Calidad y Accesibilidad

El proyecto ha sido evaluado con herramientas estándar de auditoría web, obteniendo las siguientes calificaciones:

* **WAVE (Web Accessibility Evaluation Tool):** **10 / 10** (0 errores de accesibilidad).
* **Google Lighthouse:**
  * **Rendimiento:** 92 / 100
  * **Accesibilidad:** 100 / 100
  * **Buenas Prácticas:** 100 / 100
  * **SEO:** 91 / 100[cite: 14]