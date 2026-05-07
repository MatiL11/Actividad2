# Actividad Web 2, 3 y 5 - HTML Semántico + CSS + Diseño Responsivo

Trabajos prácticos de las clases 2, 3 y 5 de la materia.

---

## Clase 2 — HTML Semántico

Replica en HTML de una noticia del diario online **The New Yorker**.

### Noticia original

**"The Futility of Rolling Stone's Best-Albums List"** — Sheldon Pearce, 2 de octubre de 2020  
URL: https://www.newyorker.com/culture/cultural-comment/the-futility-of-rolling-stones-best-albums-list

### Archivo

- `index.html` — Replica la noticia con etiquetas semánticas HTML5.

### Conceptos aplicados

- Estructura semántica HTML5 (`article`, `header`, `figure`, `figcaption`, `section`, `aside`, `time`, etc.)
- Jerarquía de encabezados (`h1`, `h2`, `h3`)
- Listas ordenadas y no ordenadas
- Hipervínculos y atributos
- Separación de contenido en secciones significativas

---

## Clase 3 y 5 — Selectores, Layout CSS y Diseño Responsivo

Replica en HTML + CSS de una noticia del diario **Infobae**.

### Noticia original

**"El musical de Elena Roger con canciones de Charly García es una celebración de la cultura popular argentina"** — Guillermo E. Pintos, 2 de mayo de 2026  
URL: https://www.infobae.com/cultura/2026/05/02/el-musical-de-elena-roger-con-canciones-de-charly-garcia-es-una-celebracion-de-la-cultura-popular-argentina/

### Archivos

- `noticia2.html` — Replica la noticia con etiquetas semánticas HTML5.
- `noticia2.css` — Hoja de estilos que replica el diseño visual de Infobae.

### Conceptos aplicados

- Hoja de estilos CSS externa vinculada con `<link>`
- Selectores de clase, elemento y pseudoclase (`:hover`, `.active`)
- Tipografía web con Google Fonts (Inter, Merriweather)
- Modelo de caja (`box-sizing`, `padding`, `margin`, `border`)
- CSS Grid para el layout de dos columnas (artículo + sidebar)
- Flexbox para navegación y header
- Posicionamiento `sticky` para el encabezado del sitio
- Media queries para diseño responsivo en tres tamaños:
  - Desktop: dos columnas con sidebar (mayor a 1023px)
  - Tablet: una columna, sidebar en grilla horizontal (768px – 1023px)
  - Mobile: una columna, navegación apilada, tipografía reducida (menor a 767px)
