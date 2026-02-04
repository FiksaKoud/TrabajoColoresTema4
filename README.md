# 🛹 Skate Flow

**Skate Flow** es un espacio digital dedicado a la cultura del skateboarding. Este proyecto explora la esencia del skate a través de una experiencia visual interactiva, con animaciones fluidas y un diseño moderno que se adapta al usuario.

---

## 📂 Estructura del Proyecto

El sitio web está compuesto por tres páginas principales, cada una con un propósito específico:

### 1. Inicio (`index.html`)
La página de aterrizaje que introduce al usuario en el mundo de Skate Flow.
- **Hero Section**: Título 3D animado y presentación del proyecto.
- **Misión y Visión**: Sección informativa con animaciones de aparición ("reveal").
- **FAQ**: Preguntas frecuentes implementadas con elementos `<details>` y `<summary>`.

### 2. Galería (`galeria.html`)
Una exhibición visual de trucos icónicos del skate.
- **Grid Layout**: Diseño de cuadrícula responsiva para mostrar las tarjetas.
- **Tarjetas Animadas**: Cada tarjeta muestra una imagen y una descripción del truco (Ollie, Boardslide, Inward Heelflip) con efectos de aparición.

### 3. Contacto (`contacto.html`)
Punto de conexión para la comunidad.
- **Formulario de Contacto**: Formulario estilizado para unirse al "club", solicitando apodo y email.

---

## 🎨 Características CSS (`style.css`)

El diseño visual es el núcleo de este proyecto, destacando por el uso de CSS moderno y vanilla (sin frameworks).

### ✨ Estética y Diseño
- **Variables CSS (`:root`)**: Gestión centralizada de colores (paleta con acentos rojos `#e74c3c`), tipografías (`Impact` y `Arial`) y modos de color.
- **Glassmorphism**: Efecto de vidrio esmerilado en la barra de navegación (`backdrop-filter: blur`).
- **Diseño Responsivo**: Adaptable a todos los dispositivos mediante Media Queries, incluyendo un menú hamburguesa animado para móviles.

### 🌗 Modo Oscuro/Claro
- Implementación "CSS-only" utilizando el hack del checkbox y la pseudoclase `:has()`.
- Transiciones suaves de color en todo el sitio (`transition: background-color 0.5s`).

### 🚀 Animaciones Avanzadas
- **Scroll-driven Animations**: La barra de navegación se encoge y añade un borde al hacer scroll.
- **Reveal on Scroll**: Los elementos aparecen (`opacity` y `transform`) a medida que entran en el viewport (`view-timeline`).
- **Efectos 3D**: Títulos con perspectiva y rotación 3D (`transform: rotateY/rotateX`).
- **Micro-interacciones**:
  - Icono de sol/luna giratorio.
  - Botones con efectos de brillo (`filter`) al pasar el mouse.
  - Indicador de scroll (rueda girando).

---

## 🛠️ Tecnologías
- **HTML5**: Semántico y accesible.
- **CSS3**: Uso avanzado de nuevas especificaciones (Grid, Flexbox, Nesting, scroll-timeline).

---

© 2026 | FiksaKoud | Proyecto DIW Tema 4