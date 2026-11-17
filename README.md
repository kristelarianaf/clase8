# clase8
# Proyecto Web - Animaciones y Full Responsive
Sitio web desarrollado para el curso de Desarrollo Web en Coderhouse, enfocado en maquetación responsive, arquitectura SASS avanzada y animaciones fluidas.
---
## 🚀 Tecnologías y Herramientas
- **HTML5:** Estructura semántica, prolija y accesible.
- **CSS3 / SASS (SCSS):** Arquitectura modular de 7-1 (base, utilities, layout, components).
- **Bootstrap 5:** Componentes interactivos y sistema de grilla.
- **Animate.css:** Librería externa de animaciones para títulos destacados.
- **Animaciones Nativas:** Keyframes y transiciones CSS para microinteracciones y carga sutil.
---
## 🎨 Características de SASS Aplicadas
- **Mixins con parámetros:** Utilizados para componentes dinámicos como botones e interacciones hover.
- **@extend / Placeholders (`%`):** Reutilización de estilos estructurales sin duplicar código.
- **Operadores y Funciones:** Cálculo dinámico de espaciados y ajustes de paleta con `sass:color`.
- **Media Queries integradas:** Diseño adaptado para dispositivos móviles, tablets y desktop.
---
## 📁 Estructura del Proyecto
```text
├── index.html
├── pages/
├── css/
│   └── style.css          # CSS compilado
├── scss/
│   ├── base/              # Tipografía y reseteos
│   ├── components/        # Botones, tarjetas, animaciones
│   ├── layout/            # Header, footer, secciones
│   ├── utilities/         # Variables, mixins y funciones
│   └── main.scss          # Punto de entrada principal
└── assets/                # Imágenes y recursos multimedia
