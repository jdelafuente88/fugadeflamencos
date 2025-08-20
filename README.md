# FUGA DE FLAMENCOS — Landing (SEO + A11y)

Landing page moderna para **FUGA DE FLAMENCOS** (Seseña, Toledo): productora musical, representación de artistas, organización de eventos y escuela (baile, guitarra y cajón).  
Proyecto **SEO-first** y **accesible**: HTML5 semántico, Core Web Vitals, JSON-LD, Open Graph/Twitter Cards, menú sticky con **scrollspy** y microinteracciones respetuosas con `prefers-reduced-motion`.

![Hero preview](https://i.imgur.com/2sA2Q5m.jpg)

---

## ✨ Características
- **HTML5 semántico** y headings jerárquicos (H1/H2 por sección).
- **SEO**: `<title>`, `meta description`, `link rel="canonical"`, OG/Twitter Cards, **preload** de imagen hero, URLs limpias.
- **Structured Data (JSON-LD)**: `Organization`, `WebSite` (fácil extender a `FAQPage`, `BreadcrumbList`, `Event`).
- **Accesibilidad**:
  - Menú móvil accesible: `aria-expanded`, `aria-hidden`, foco gestionado, cierre con `Esc`, backdrop clicable, **scroll lock**.
  - **Skip link** (“Saltar al contenido”).
  - Estados `:focus-visible` en elementos interactivos.
- **Scrollspy**: subraya el enlace activo según la sección visible.
- **Rendimiento**: `loading="lazy"`, `decoding="async"`, `width/height` en imágenes clave (previene CLS).
- **Core Web Vitals friendly**: diseño estable, assets preconectados y pre-cargados.
- **UX**: separadores `<hr>` entre secciones, CTA claros, animaciones suaves (desactivables).

---
