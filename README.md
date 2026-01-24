# 💰 SmartBudget - Landing Page

> **SmartBudget** es una interfaz web moderna, responsiva y escalable diseñada para una fintech. 
---

## 📸 Vista Previa

<img width="1873" height="3823" alt="Prototipo" src="https://github.com/user-attachments/assets/34999000-d3e9-4ba3-9a18-de64813d789c" />

---

## 🚀 Características Principales

* **Diseño Completamente Responsivo:** Adaptable a móviles, tablets y escritorio.
* **Header "Sticky":** Navegación fija con cambio de estilos y logo adaptable al scroll.
* **Arquitectura SASS 7-1:** Estructura de estilos modular y escalable.
* **Metodología BEM:** Nombramiento de clases (Block-Element-Modifier) evita conflictos de CSS.
* **Integración Híbrida:** Uso de estilos personalizados (SASS) combinados con componentes JS de **Bootstrap 4** .
* **Grillas Modernas:** Implementación de CSS Grid y Flexbox para layouts complejos.

---

## 🛠️ Tecnologías Utilizadas

* **HTML5 Semántico:** Estructura optimizada para SEO y accesibilidad.
* **SASS (SCSS):** Pre-procesador CSS.
* **Bootstrap 4.6:** Framework para componentes interactivos (Modales).
* **Node.js / NPM:** Gestión de paquetes para compilación de SASS.
* **Git / GitHub:** Control de versiones.

---

## 📂 Estructura del Proyecto (Patrón 7-1)

El proyecto sigue el patrón arquitectónico 7-1 para SASS, lo que garantiza un mantenimiento sencillo:

```text
/scss
│
├── abstract/      # Variables, mixins y funciones
├── base/          # Reset, tipografía y utilidades globales
├── components/    # Botones, tarjetas, inputs
├── layout/        # Header, footer, secciones (grid, banner)
├── pages/         # Estilos específicos de página (si aplica)
├── themes/        # Temas de color (Dark mode, etc.)
├── vendors/       # Librerías externas
└── main.scss      # Archivo maestro que importa todo
