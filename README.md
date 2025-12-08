# FUGA DE FLAMENCOS — Landing & Plataforma de Reservas

Web corporativa y plataforma de reservas para **FUGA DE FLAMENCOS** (Seseña, Toledo).  
Proyecto **Full-Responsive**, **SEO-first** y **GDPR Compliant**: HTML5 semántico, Core Web Vitals optimizados, JSON-LD multiservicio, sistema de gestión de cookies granular y motor de reservas integrado.

![Hero preview](assets/images/fdf-stage-logo-final.webp)

---

## ✨ Características Principales

### 🎨 Diseño y UX (Look & Feel "Cyberpunk Flamenco")
- **Identidad Visual:** Paleta de alto contraste (Negro Puro `#050505` + Magenta Neón `#FF3DCD`).
- **Tipografía:** Combinación de **Jost** (Google Fonts, alternativa geométrica a Futura) para títulos y **Montserrat** para cuerpos de texto.
- **Responsive Total:** Grids flexibles (`minmax`), tipografía fluida (`clamp()`) y layout adaptativo para móviles, tablets y desktop.
- **Navegación:** Header **Fixed** (fijo al scroll) con menú hamburguesa móvil accesible y transiciones suaves.

### 🛠 Ingeniería y Rendimiento
- **SEO Técnico:** Metaetiquetas completas, Open Graph, Twitter Cards, `canonical` y precarga de recursos críticos (`preload`).
- **Core Web Vitals:** Prevención de CLS con dimensiones explícitas en imágenes, `loading="lazy"`, `decoding="async"`.
- **Structured Data (JSON-LD)**: Esquema complejo definiendo el negocio como `MusicSchool`, `RecordingStudio` y `EventVenue` simultáneamente.

### 🍪 Cumplimiento Legal (RGPD/LSSI)
- **Gestión de Cookies Granular:** - Banner no intrusivo.
  - **Modal de configuración:** Permite al usuario activar/desactivar cookies Analíticas y de Marketing por separado.
  - Persistencia de consentimiento mediante `localStorage`.
- **Páginas Legales:** Secciones dedicadas y enlazadas para Aviso Legal, Política de Privacidad y Cookies.

### 📅 Sistema de Reservas
- **Integración Cal.com:** Página dedicada `/reservas/` con `iframe` dinámico que carga calendarios específicos según el servicio (Ensayo, Estudio, Eventos).
- **Fallback:** CTA directos a WhatsApp para gestión manual de citas.

---

## 📂 Estructura del Proyecto

```text
/
├── index.html              # Landing Page Principal
├── reservas/
│   └── index.html          # Motor de Reservas (Cal.com)
├── legal/
│   ├── aviso-legal/        # Texto legal LSSI
│   ├── privacidad/         # Política RGPD
│   └── cookies/            # Política de Cookies detallada
└── assets/
    ├── images/             # Imágenes optimizadas (WebP/JPG)
    └── fonts/              # (Opcional si se alojan localmente)

