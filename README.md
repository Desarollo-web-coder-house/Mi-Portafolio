# 🌐 Portafolio Profesional — Daniela Romero

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap_5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Responsive](https://img.shields.io/badge/Responsive-Design-2ea44f?style=for-the-badge)
![Accessibility](https://img.shields.io/badge/Accesibilidad-WCAG-0d6efd?style=for-the-badge)
![License](https://img.shields.io/badge/Licencia-Uso_Profesional-lightgrey?style=for-the-badge)

### **Desarrolladora Web y de Aplicaciones**
*Ingeniería de interfaces, arquitectura de contenido y diseño de experiencias digitales de alto impacto*

</div>

---

## 📖 Tabla de Contenidos

- [🌐 Portafolio Profesional — Daniela Romero](#-portafolio-profesional--daniela-romero)
    - [**Desarrolladora Web y de Aplicaciones**](#desarrolladora-web-y-de-aplicaciones)
  - [📖 Tabla de Contenidos](#-tabla-de-contenidos)
  - [🎯 Filosofía del Proyecto](#-filosofía-del-proyecto)
  - [🧭 Descripción General](#-descripción-general)
  - [🖼️ Vista Previa](#️-vista-previa)
  - [✨ Características Principales](#-características-principales)
  - [🛠️ Stack Tecnológico](#️-stack-tecnológico)
  - [📂 Arquitectura del Proyecto](#-arquitectura-del-proyecto)
  - [🔍 Detalle Técnico por Vista](#-detalle-técnico-por-vista)
  - [🎨 Sistema de Diseño](#-sistema-de-diseño)
  - [🚀 Instalación y Puesta en Marcha](#-instalación-y-puesta-en-marcha)
    - [Despliegue sugerido](#despliegue-sugerido)
  - [🗺️ Mapa del Sitio](#️-mapa-del-sitio)
  - [🧱 Principios de Ingeniería y Buenas Prácticas](#-principios-de-ingeniería-y-buenas-prácticas)
  - [♿ Accesibilidad y SEO](#-accesibilidad-y-seo)
  - [⚡ Rendimiento y Optimización](#-rendimiento-y-optimización)
  - [🌍 Compatibilidad](#-compatibilidad)
  - [👩‍💻 Sobre la Autora](#-sobre-la-autora)
  - [📬 Contacto](#-contacto)
  - [📄 Licencia](#-licencia)

---

## 🎯 Filosofía del Proyecto

Este portafolio no fue concebido como una simple vidriera de trabajos, sino como una **pieza de ingeniería front-end en sí misma**: un caso de estudio vivo que demuestra, a través de su propia construcción, los criterios de calidad, orden y escalabilidad que se aplican a cada proyecto entregado a clientes.

Cada decisión —desde la jerarquía semántica del marcado hasta la elección tipográfica— responde a un principio rector: **la forma comunica tanto como el contenido**. Por ello, el sitio se apoya en una arquitectura de información clara, una identidad visual coherente y una experiencia de navegación fluida, sin sacrificar rendimiento ni accesibilidad.

---

## 🧭 Descripción General

Este repositorio contiene el **sitio web de portafolio personal** de Daniela Romero, una plataforma de presentación profesional que articula identidad de marca, trayectoria académica y técnica, catálogo de servicios y canales de contacto directo, todo integrado en una experiencia web unificada, accesible y completamente adaptable a cualquier dispositivo.

El proyecto fue desarrollado siguiendo una arquitectura de **maquetación semántica HTML5**, complementada con una hoja de estilos propia (`style.css`) y el framework **Bootstrap 5**, priorizando en todo momento la fidelidad visual, la usabilidad, la mantenibilidad del código y el rendimiento de carga en cada una de sus vistas.

El sitio se estructura en **cinco vistas independientes pero interconectadas**, cada una diseñada con un propósito comunicacional específico dentro del embudo de conversión de un potencial cliente: captar atención (*Inicio*), generar confianza (*Sobre mí*), demostrar capacidad técnica (*Proyectos*), presentar la oferta de valor (*Servicios*) y facilitar la acción (*Contacto*).

---

## 🖼️ Vista Previa

> *Sugerencia: reemplaza este bloque con capturas reales renderizadas a partir de `img/hero_section.png`, `img/Perfil.jpeg` y las miniaturas de `img/Proyectos/` una vez publicado el sitio en producción.*

| Inicio | Sobre mí | Proyectos | Servicios | Contacto |
|:---:|:---:|:---:|:---:|:---:|
| 🏠 | 👩‍💻 | 💼 | 🛠️ | 📬 |

---

## ✨ Características Principales

- **Diseño 100% Responsivo (Mobile First):** interfaz fluida y adaptable mediante el sistema de grillas de Bootstrap 5, garantizando una experiencia visual consistente en dispositivos móviles, tablets, notebooks y monitores de escritorio.
- **Navegación Semántica y Persistente:** barra de navegación (`navbar`) fija con menú colapsable (*hamburger menu*) para entornos móviles, replicada de forma idéntica en las cinco vistas del sitio para reforzar la orientación del usuario.
- **Carrusel Dinámico de Proyectos Destacados:** componente interactivo (`Bootstrap Carousel`) con seis diapositivas, transición automática cronometrada, indicadores de posición y controles de navegación manual, utilizado tanto en la vista de inicio como en la galería completa.
- **Canales de Contacto Integrados y Pre-configurados:** enlaces directos hacia WhatsApp (con mensaje predefinido vía API `wa.me`), Gmail (con asunto y destinatario precargados mediante `mailto`/Gmail Compose API) e Instagram, reduciendo la fricción de conversión en el primer contacto comercial.
- **Tipografía Corporativa Personalizada:** integración de tres familias tipográficas desde Google Fonts —*Google Sans Flex*, *Roboto* y *Stack Sans Headline*— combinadas estratégicamente para reforzar jerarquía visual e identidad de marca.
- **Iconografía Vectorial Embebida:** uso de SVG inline (Bootstrap Icons) en lugar de sprites externos, garantizando nitidez en cualquier resolución y eliminando peticiones HTTP adicionales.
- **Accesibilidad (a11y) como Estándar, no como Añadido:** atributos `alt`, `aria-label`, `aria-controls` y `aria-expanded` implementados de forma consistente en todos los componentes interactivos.
- **Arquitectura de Contenido Modular:** cada sección del sitio (`<section>`, `<article>`, `<figure>`) encapsula una unidad de contenido autocontenida, facilitando el mantenimiento y la escalabilidad futura del proyecto.

---

## 🛠️ Stack Tecnológico

| Categoría | Tecnología | Propósito dentro del proyecto |
|---|---|---|
| **Marcado** | HTML5 semántico | Estructura del contenido y accesibilidad del documento |
| **Estilos** | CSS3 (hoja propia `style.css`) | Identidad visual, layout personalizado y theming de marca |
| **Framework UI** | Bootstrap 5.0.2 | Sistema de grillas, componentes responsivos (navbar, carrusel) |
| **Iconografía** | Bootstrap Icons (SVG inline) | Iconos vectoriales de redes sociales y contacto |
| **Tipografía** | Google Fonts | *Google Sans Flex*, *Roboto*, *Stack Sans Headline* |
| **Interactividad** | Bootstrap Bundle (JS + Popper) | Comportamiento del navbar colapsable y del carrusel |
| **Control de Versiones** | Git & GitHub | Historial de cambios y despliegue continuo |

> **Nota técnica:** el proyecto no introduce dependencias de *build tools* (Webpack, Vite) ni frameworks de componentes (React, Vue), manteniéndose deliberadamente como un sitio estático de bajo acoplamiento, ideal para *hosting* ligero (GitHub Pages, Netlify, Vercel) y tiempos de carga mínimos.

---

## 📂 Arquitectura del Proyecto

```
Portfolio-Daniela-Romero/
│
├── index.html                     # Landing page — presentación, resumen y CTA
│
├── css/
│   └── style.css                  # Hoja de estilos global (≈ núcleo visual del sitio)
│
├── img/
│   ├── logo.png                   # Identidad de marca (navbar)
│   ├── hero_section.png           # Imagen principal de cabecera
│   ├── Perfil.jpeg                # Fotografía de perfil profesional
│   ├── Proyectos/                 # Assets visuales de proyectos destacados
│   │   ├── Curriculum.png
│   │   ├── Petshop.png
│   │   ├── SuperHeroes.png
│   │   ├── GameShop.png
│   │   ├── TrailerFlix.png
│   │   └── TiendaML.png
│   └── Servicios/                 # Assets visuales del catálogo de servicios
│
└── pages/
    ├── sobre_mi.html               # Perfil profesional, formación y stack técnico
    ├── proyectos.html              # Galería completa de proyectos desarrollados
    ├── servicios.html              # Catálogo detallado de soluciones ofrecidas
    └── contacto.html               # Canales de comunicación directa
```

Esta organización responde al principio de **cohesión por responsabilidad**: los recursos estáticos (`img/`), la lógica de presentación (`css/`) y las vistas secundarias (`pages/`) permanecen desacoplados de la vista raíz (`index.html`), facilitando la escalabilidad del sitio ante la incorporación de nuevas secciones.

---

## 🔍 Detalle Técnico por Vista

| Vista | Contenido estructural | Componentes destacados |
|---|---|---|
| **`index.html`** | Hero de presentación, resumen "Sobre mí", vista previa de servicios, carrusel de proyectos, bloque de contacto | Carrusel Bootstrap, navegación por anclas internas |
| **`sobre_mi.html`** | Perfil profesional, formación académica (Diplomatura Full Stack, Desarrollo de Apps Móviles), stack tecnológico segmentado (Frontend/Backend Web y Mobile), pilares de filosofía de trabajo, habilidades técnicas y blandas | Estructura jerárquica `h2`–`h4`, listas de competencias |
| **`proyectos.html`** | Galería ampliada de los seis proyectos destacados con descripciones técnicas detalladas | Carrusel extendido, tarjetas de proyecto |
| **`servicios.html`** | Catálogo de soluciones: desarrollo a medida, ecosistemas web y sistemas de gestión operativa | Tarjetas de servicio estructuradas semánticamente |
| **`contacto.html`** | Canales directos de contacto con enlaces preconfigurados | Tarjetas de contacto (`tarjeta_contacto`) con iconografía SVG |

---

## 🎨 Sistema de Diseño

- **Paleta tipográfica:** combinación de *Google Sans Flex* (títulos y elementos de impacto), *Roboto* (cuerpo de texto, alta legibilidad) y *Stack Sans Headline* (acentos y jerarquías intermedias).
- **Identidad de marca:** logo y favicon consistentes en el `navbar` de las cinco vistas, reforzando el reconocimiento visual durante toda la navegación.
- **Componentización visual:** tarjetas (`tarjeta_contacto`), secciones (`contenido_principal`, `sobre_mi`, `servicios_principal`, `proyectos_principal`) y artículos reutilizan una misma gramática visual para mantener consistencia entre vistas.
- **Micro-interacciones:** sombreado (`shadow`), bordes redondeados (`rounded-4`) y transiciones del carrusel aportan profundidad y modernidad sin comprometer el rendimiento.

---

## 🚀 Instalación y Puesta en Marcha

No se requieren dependencias externas, gestores de paquetes ni procesos de compilación (*build*). El proyecto es completamente estático y puede ejecutarse de inmediato.

```bash
# 1. Clonar el repositorio
git clone https://github.com/Desarollo-web-coder-house/Mi-Portafolio.git

# 2. Acceder al directorio del proyecto
cd Desarollo-web-coder-house/Mi-Portafolio

# 3. Abrir index.html en el navegador
#    (recomendado: usar la extensión "Live Server" de VS Code
#    para simular un entorno de servidor local con recarga en caliente)
```

> 💡 **Recomendación técnica:** dado que existen rutas relativas entre `index.html` y las vistas alojadas en `pages/`, se sugiere servir el proyecto mediante un servidor local (Live Server, `http-server`, `serve`) en lugar de abrir los archivos directamente vía protocolo `file://`, evitando así inconsistencias en la resolución de assets.

### Despliegue sugerido

| Plataforma | Ventaja |
|---|---|
| **GitHub Pages** | Despliegue gratuito directo desde el repositorio |
| **Netlify** | CI/CD automático ante cada `push`, *preview deploys* |
| **Vercel** | Alto rendimiento en CDN global, configuración mínima |

---

## 🗺️ Mapa del Sitio

| Página | Ruta | Propósito comunicacional |
|---|---|---|
| **Inicio** | `/index.html` | Primera impresión, propuesta de valor y navegación hacia el resto del sitio |
| **Sobre mí** | `/pages/sobre_mi.html` | Construcción de confianza mediante trayectoria, formación y filosofía profesional |
| **Proyectos** | `/pages/proyectos.html` | Evidencia técnica del trabajo realizado |
| **Servicios** | `/pages/servicios.html` | Presentación estructurada de la oferta comercial |
| **Contacto** | `/pages/contacto.html` | Conversión: facilitar el primer contacto con el menor esfuerzo posible |

---

## 🧱 Principios de Ingeniería y Buenas Prácticas

- **Mobile First:** el diseño se concibe primero para el viewport más restrictivo, escalando progresivamente hacia resoluciones mayores.
- **Semántica ante todo:** uso disciplinado de `<header>`, `<main>`, `<section>`, `<article>`, `<figure>` y `<footer>`, otorgando significado estructural al documento más allá de su apariencia visual.
- **Separación de responsabilidades (SoC):** contenido (HTML), presentación (CSS) y comportamiento (JavaScript) permanecen desacoplados en capas independientes.
- **Rutas relativas consistentes:** jerarquía de directorios diseñada para garantizar la integridad de los enlaces entre la vista raíz y las vistas internas de `pages/`.
- **Nomenclatura BEM-like:** clases descriptivas en español (`contenido_principal`, `tarjeta_contacto`, `navbar_propia`) que favorecen la legibilidad del código para futuros mantenedores.
- **Progressive Enhancement:** el sitio permanece funcional y legible incluso si algún recurso externo (fuente, ícono) no llega a cargar.
- **DRY (Don't Repeat Yourself):** componentes reutilizados (navbar, footer, tarjetas de contacto) mantienen una estructura idéntica entre vistas para simplificar el mantenimiento.

---

## ♿ Accesibilidad y SEO

- Etiquetas `alt` descriptivas en la totalidad de las imágenes del sitio.
- Atributos `aria-label`, `aria-controls` y `aria-expanded` en elementos interactivos (botón de menú, carrusel).
- Jerarquía de encabezados (`h1`–`h4`) respetada y no alterada por motivos estéticos, favoreciendo tanto la accesibilidad como el posicionamiento en buscadores (SEO on-page).
- Uso de `rel="noopener noreferrer"` en enlaces externos con `target="_blank"`, mitigando riesgos de seguridad asociados a *tabnabbing*.
- Metaetiqueta `viewport` correctamente configurada para una renderización adaptativa desde el primer render.

---

## ⚡ Rendimiento y Optimización

- **SVG inline** en lugar de fuentes de íconos completas, reduciendo peticiones HTTP innecesarias.
- **`preconnect`** a los orígenes de Google Fonts, anticipando la resolución DNS y disminuyendo la latencia de carga tipográfica.
- **Carga diferida implícita** de recursos no críticos mediante la organización del documento.
- **CDN para Bootstrap:** aprovechamiento de *jsDelivr* con verificación de integridad (`integrity` + `crossorigin`) para mitigar riesgos de manipulación de terceros.

---

## 🌍 Compatibilidad

| Navegador | Soporte |
|---|:---:|
| Google Chrome | ✅ |
| Mozilla Firefox | ✅ |
| Microsoft Edge | ✅ |
| Safari (macOS / iOS) | ✅ |
| Opera | ✅ |

Compatible con las últimas dos versiones estables de cada navegador, siguiendo los estándares de soporte de Bootstrap 5.

---

## 👩‍💻 Sobre la Autora

**Daniela Romero** es desarrolladora web y de aplicaciones móviles, formada en Desarrollo Web Full Stack y Desarrollo de Aplicaciones Móviles. Su enfoque profesional combina tres pilares fundamentales:

- **Arquitectura robusta y escalable**, priorizando bases de código mantenibles a largo plazo.
- **Diseño centrado en el usuario (UX/UI)**, donde cada decisión visual responde a una necesidad de usabilidad concreta.
- **Comunicación transparente y cumplimiento metódico de plazos**, garantizando alineación estratégica con cada cliente a lo largo de todo el ciclo de desarrollo.

Su stack técnico abarca tanto el desarrollo **frontend y backend web**, como el desarrollo de **aplicaciones móviles** y servicios cloud, complementado con sólidas competencias en diseño de interfaces, optimización de rendimiento y resolución metódica de problemas.

---

## 📬 Contacto

¿Tienes un proyecto en mente o buscas digitalizar tu empresa? Conversemos y transformemos tu visión en una solución digital a medida.

[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/5493544656873)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:daniela.romero.developer@gmail.com)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/daniela.romero___)

---

## 📄 Licencia

Este proyecto se distribuye con fines de exhibición profesional. Todos los derechos sobre el diseño, la estructura de contenido y los assets visuales pertenecen a **Daniela Romero**. Queda prohibida su reproducción total o parcial, con fines comerciales o de portafolio propio, sin autorización previa y expresa de la autora.

---

<div align="center">

**© 2026 Daniela Romero — Desarrolladora Web y de Apps**

</div>