# 🌐 Portafolio Profesional — Daniela Romero

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap_5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?style=for-the-badge&logo=githubpages&logoColor=white)
![Responsive](https://img.shields.io/badge/Diseño-Responsivo-2ea44f?style=for-the-badge)
![Accessibility](https://img.shields.io/badge/Accesibilidad-WCAG-0d6efd?style=for-the-badge)

### **Desarrolladora Web y de Aplicaciones**

*Diseño y construcción de experiencias digitales claras, sólidas y preparadas para crecer*

<br>

### 🔗 **[VER SITIO EN VIVO →](https://desarollo-web-coder-house.github.io/Mi-Portafolio/)**

[![Ver Demo](https://img.shields.io/badge/🚀_Visitar_Portafolio-1a73e8?style=for-the-badge)](https://desarollo-web-coder-house.github.io/Mi-Portafolio/)
[![Repositorio](https://img.shields.io/badge/📂_Código_Fuente-24292e?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Desarollo-web-coder-house/Mi-Portafolio)

</div>

---

## 🎨 Arquitectura SCSS — Pre-Entrega

La hoja de estilos fue refactorizada completamente a SCSS sin modificar las cinco páginas HTML ni la identidad visual existente. El proyecto utiliza `scss/main.scss` como único punto de entrada y `@use` para orquestar todos los partials.

### Estructura obligatoria

```text
scss/
├── main.scss
├── utilities/
│   ├── _variables.scss
│   └── _mixins.scss
├── base/
│   ├── _tipografia.scss
│   └── _base.scss
├── layout/
│   ├── _header.scss
│   ├── _footer.scss
│   └── _nav.scss
└── components/
    ├── _buttons.scss
    └── _cards.scss
```

No se agregan otras carpetas dentro de `scss/`. Los colores y demás valores reutilizados se centralizan en `_variables.scss`; los mixins reutilizables se encuentran en `_mixins.scss`; y los componentes utilizan variables en lugar de colores escritos directamente.

### Compilación

Instalar dependencias:

```bash
npm install
```

Compilar el único archivo CSS final:

```bash
npm run build
```

> **Importante:** `css/style.css` es un archivo generado. Después de cualquier modificación dentro de `scss/`, ejecutá `npm run build` para actualizarlo.

### Checklist de cumplimiento de la Pre-Entrega

- `scss/main.scss` es el único punto de entrada y utiliza `@use`.
- La arquitectura se divide en `utilities`, `base`, `layout` y `components`.
- Los colores reutilizados están centralizados en `_variables.scss`.
- Los mixins reutilizables están centralizados en `_mixins.scss`.
- Se utiliza nesting y `&` en los componentes y estados interactivos.
- La responsividad está organizada con metodología **Mobile First** y breakpoints ascendentes mediante `min-width`.
- Se mantienen los estados `:hover`, `:focus` y `:active` donde aportan interacción.
- No se utilizan transformaciones `transform` para los efectos visuales.
- El diseño visual, la paleta y la estructura HTML original se conservan.

El comando genera:

```text
css/style.css
```

Para trabajar con compilación automática:

```bash
npm run watch
```

El CSS generado no utiliza source map, por lo que el entregable conserva un único archivo CSS final.

---

## 📖 Tabla de Contenidos

- [🌐 Portafolio Profesional — Daniela Romero](#-portafolio-profesional--daniela-romero)
    - [**Desarrolladora Web y de Aplicaciones**](#desarrolladora-web-y-de-aplicaciones)
    - [🔗 **VER SITIO EN VIVO →**](#-ver-sitio-en-vivo-)
  - [🎨 Arquitectura SCSS — Pre-Entrega](#-arquitectura-scss--pre-entrega)
    - [Estructura obligatoria](#estructura-obligatoria)
    - [Compilación](#compilación)
    - [Checklist de cumplimiento de la Pre-Entrega](#checklist-de-cumplimiento-de-la-pre-entrega)
  - [📖 Tabla de Contenidos](#-tabla-de-contenidos)
  - [🔗 Sitio en Producción](#-sitio-en-producción)
  - [🎯 Filosofía del Proyecto](#-filosofía-del-proyecto)
  - [🧭 Descripción General](#-descripción-general)
  - [🖼️ Vista Previa](#️-vista-previa)
  - [✨ Características Principales](#-características-principales)
  - [🛠️ Stack Tecnológico](#️-stack-tecnológico)
  - [🎨 Arquitectura SCSS — Entrega de refactorización](#-arquitectura-scss--entrega-de-refactorización)
    - [Compilación](#compilación-1)
  - [📂 Arquitectura del Proyecto](#-arquitectura-del-proyecto)
  - [🔍 Detalle Técnico por Vista](#-detalle-técnico-por-vista)
  - [🎨 Sistema de Diseño](#-sistema-de-diseño)
  - [🚀 Instalación y Puesta en Marcha](#-instalación-y-puesta-en-marcha)
  - [🌐 Despliegue en GitHub Pages](#-despliegue-en-github-pages)
    - [Cómo replicar este despliegue](#cómo-replicar-este-despliegue)
    - [Alternativas de despliegue](#alternativas-de-despliegue)
  - [🗺️ Mapa del Sitio](#️-mapa-del-sitio)
  - [🧱 Principios de Trabajo y Buenas Prácticas](#-principios-de-trabajo-y-buenas-prácticas)
  - [♿ Accesibilidad y Posicionamiento (SEO)](#-accesibilidad-y-posicionamiento-seo)
  - [⚡ Rendimiento y Optimización](#-rendimiento-y-optimización)
  - [🌍 Compatibilidad](#-compatibilidad)
  - [👩‍💻 Sobre la Autora](#-sobre-la-autora)
  - [📬 Contacto](#-contacto)
  - [📄 Licencia](#-licencia)

---

## 🔗 Sitio en Producción

El portafolio se encuentra **publicado y disponible en línea**, desplegado mediante **GitHub Pages**, el servicio de alojamiento estático integrado a GitHub que publica el sitio directamente desde el repositorio.

| Recurso | Enlace |
|---|---|
| 🌐 **Sitio en vivo** | **[desarollo-web-coder-house.github.io/Mi-Portafolio](https://desarollo-web-coder-house.github.io/Mi-Portafolio/)** |
| 📂 **Repositorio** | [github.com/Desarollo-web-coder-house/Mi-Portafolio](https://github.com/Desarollo-web-coder-house/Mi-Portafolio) |
| 🔄 **Actualización** | Automática ante cada `push` a la rama principal |

> Al tratarse de un sitio completamente estático, cada actualización del código se refleja en producción en cuestión de segundos, sin necesidad de servidores intermedios ni procesos de compilación.

---

## 🎯 Filosofía del Proyecto

Este portafolio no fue pensado como una simple vidriera de trabajos, sino como **una pieza de ingeniería web en sí misma**: un caso de estudio vivo que demuestra, a través de su propia construcción, los mismos criterios de calidad, orden y escalabilidad que se aplican a cada proyecto entregado a un cliente.

Cada decisión —desde la organización del código hasta la elección tipográfica— responde a un principio rector: **la forma comunica tanto como el contenido**. Por eso el sitio se apoya en una estructura de información clara, una identidad visual coherente y una navegación fluida, sin sacrificar velocidad de carga ni accesibilidad.

En términos simples: el sitio no solo *cuenta* cómo se trabaja, sino que lo *demuestra* en cada línea de código.

---

## 🧭 Descripción General

Este repositorio contiene el **sitio web de portafolio personal** de Daniela Romero: una plataforma de presentación profesional que integra identidad de marca, trayectoria académica y técnica, catálogo de servicios y canales de contacto directo en una experiencia unificada, accesible y completamente adaptable a cualquier dispositivo.

El proyecto está construido sobre una **estructura semántica HTML5** —es decir, un código que describe el significado de cada bloque de contenido y no solo su apariencia—, complementada con una hoja de estilos propia (`style.css`) y el framework **Bootstrap 5**. En todo momento se priorizó la fidelidad visual, la facilidad de uso, la mantenibilidad del código y el rendimiento de carga.

El sitio se organiza en **cinco vistas independientes pero interconectadas**, cada una con un propósito comunicacional definido dentro del recorrido de un potencial cliente:

| Etapa | Vista | Objetivo |
|---|---|---|
| 1️⃣ Captar atención | **Inicio** | Transmitir la propuesta de valor en los primeros segundos |
| 2️⃣ Generar confianza | **Sobre mí** | Respaldar con formación, trayectoria y filosofía de trabajo |
| 3️⃣ Demostrar capacidad | **Proyectos** | Evidenciar resultados concretos y competencia técnica |
| 4️⃣ Presentar la oferta | **Servicios** | Explicar con claridad qué soluciones se ofrecen |
| 5️⃣ Facilitar la acción | **Contacto** | Reducir al mínimo el esfuerzo para iniciar la conversación |

---

## 🖼️ Vista Previa

> *Sugerencia: reemplazar este bloque con capturas reales del sitio publicado una vez tomadas las pantallas de cada vista.*

| Inicio | Sobre mí | Proyectos | Servicios | Contacto |
|:---:|:---:|:---:|:---:|:---:|
| 🏠 | 👩‍💻 | 💼 | 🛠️ | 📬 |

**[👉 Explorar el sitio completo en vivo](https://desarollo-web-coder-house.github.io/Mi-Portafolio/)**

---

## ✨ Características Principales

- **🔄 Diseño totalmente responsivo (enfoque *Mobile First*)** — La interfaz se adapta con naturalidad a cualquier pantalla gracias al sistema de grillas de Bootstrap 5. El diseño se concibe primero para el celular y luego escala hacia tablets, notebooks y monitores de escritorio, garantizando una experiencia consistente en todos los contextos de uso.

- **🧭 Navegación clara y persistente** — Barra de navegación replicada de forma idéntica en las cinco vistas, con menú desplegable (*hamburger menu*) en dispositivos móviles. El usuario siempre sabe dónde está y cómo llegar a cualquier sección.

- **🎠 Carrusel dinámico de proyectos destacados** — Componente interactivo con transición automática, indicadores de posición y controles manuales, que permite recorrer los trabajos realizados sin abandonar la vista actual.

- **📲 Canales de contacto preconfigurados** — Enlaces directos a WhatsApp (con mensaje inicial ya redactado), Gmail (con destinatario y asunto precargados) e Instagram. El objetivo es eliminar toda fricción: el usuario pasa de la intención al contacto en un solo clic.

- **🔤 Tipografía corporativa personalizada** — Tres familias tipográficas integradas desde Google Fonts (*Google Sans Flex*, *Roboto* y *Stack Sans Headline*), combinadas estratégicamente para construir jerarquía visual y reforzar la identidad de marca.

- **🎯 Iconografía vectorial integrada** — Íconos en formato SVG incorporados directamente en el código, lo que garantiza nitidez perfecta en cualquier resolución y evita descargas adicionales que ralenticen el sitio.

- **♿ Accesibilidad como estándar, no como agregado** — Textos alternativos en imágenes y etiquetas descriptivas en elementos interactivos, para que el sitio sea comprensible también para personas que navegan con lectores de pantalla.

- **🧩 Estructura modular de contenido** — Cada bloque del sitio funciona como una unidad autónoma y reutilizable, lo que facilita mantener, corregir o ampliar el proyecto sin afectar al resto.

---

## 🛠️ Stack Tecnológico

| Categoría | Tecnología | Función dentro del proyecto |
|---|---|---|
| **Estructura** | HTML5 semántico | Organiza el contenido dando significado a cada sección |
| **Estilos** | CSS3 (`style.css`) | Define la identidad visual, el layout y el theming de marca |
| **Framework UI** | Bootstrap 5.0.2 | Aporta el sistema de grillas y los componentes responsivos |
| **Iconografía** | Bootstrap Icons (SVG) | Íconos vectoriales de contacto y redes sociales |
| **Tipografía** | Google Fonts | *Google Sans Flex*, *Roboto*, *Stack Sans Headline* |
| **Interactividad** | Bootstrap Bundle (JS) | Anima el menú desplegable y el carrusel de proyectos |
| **Versionado** | Git & GitHub | Historial de cambios y trazabilidad del desarrollo |
| **Despliegue** | GitHub Pages | Publicación automática del sitio en producción |

> **💡 Decisión técnica:** el proyecto evita deliberadamente herramientas de compilación (Webpack, Vite) y frameworks de componentes (React, Vue). Al mantenerse como un sitio estático liviano, logra tiempos de carga mínimos, cero dependencias que mantener y un despliegue inmediato en cualquier servicio de alojamiento.

---


---

## 🎨 Arquitectura SCSS — Entrega de refactorización

La hoja de estilos fue refactorizada completamente a **SCSS**, manteniendo la estructura HTML y la apariencia visual existente. El archivo `style.css` es únicamente el resultado compilado de `scss/main.scss`.

```text
scss/
├── main.scss              # único punto de entrada (con @use)
├── utilities/
│   ├── _variables.scss
│   └── _mixins.scss
├── base/
│   ├── _tipografia.scss
│   └── _base.scss
├── layout/
│   ├── _header.scss
│   ├── _footer.scss
│   └── _nav.scss
└── components/
    ├── _buttons.scss
    └── _cards.scss
```

### Compilación

Instalar las dependencias:

```bash
npm install
```

Compilar el SCSS:

```bash
npm run build
```

Modo desarrollo con compilación automática:

```bash
npm run watch
```

`scss/main.scss` es el único punto de entrada y utiliza `@use` para orquestar los partials. Los colores reutilizados están centralizados en `_variables.scss` y las herramientas reutilizables de SCSS se encuentran en `_mixins.scss`.

## 📂 Arquitectura del Proyecto

```
Mi-Portafolio/
│
├── index.html                     # Página principal — presentación y punto de entrada
│
├── css/
│   └── style.css                  # Hoja de estilos global: el núcleo visual del sitio
│
├── img/
│   ├── logo.png                   # Identidad de marca (barra de navegación)
│   ├── hero_section.png           # Imagen principal de cabecera
│   ├── Perfil.jpeg                # Fotografía de perfil profesional
│   ├── Proyectos/                 # Imágenes de los proyectos destacados
│   │   ├── Curriculum.png
│   │   ├── Petshop.png
│   │   ├── SuperHeroes.png
│   │   ├── GameShop.png
│   │   ├── TrailerFlix.png
│   │   └── TiendaML.png
│   └── Servicios/                 # Imágenes del catálogo de servicios
│
└── pages/
    ├── sobre_mi.html              # Perfil profesional, formación y competencias
    ├── proyectos.html             # Galería completa de proyectos
    ├── servicios.html             # Catálogo detallado de soluciones
    └── contacto.html              # Canales de comunicación directa
```

Esta organización responde al principio de **cada cosa en su lugar**: los recursos visuales (`img/`), los estilos (`css/`) y las vistas internas (`pages/`) se mantienen separados de la página raíz. El resultado es un proyecto ordenado, fácil de recorrer para cualquier desarrollador y preparado para crecer sin volverse caótico.

---

## 🔍 Detalle Técnico por Vista

| Vista | Contenido | Componentes destacados |
|---|---|---|
| **`index.html`** | Cabecera de presentación, síntesis de "Sobre mí", adelanto de servicios, carrusel de proyectos y bloque de contacto | Carrusel Bootstrap, navegación interna |
| **`sobre_mi.html`** | Perfil profesional, formación académica (Diplomatura en Desarrollo Web Full Stack y Carrera de Desarrollo de Apps Móviles), stack técnico segmentado (Frontend y Backend, Web y Mobile), pilares de trabajo, habilidades técnicas y blandas | Jerarquía de encabezados `h2`–`h4`, listados de competencias |
| **`proyectos.html`** | Galería ampliada de los seis proyectos destacados, con descripción técnica de cada desarrollo | Carrusel extendido, tarjetas de proyecto |
| **`servicios.html`** | Catálogo de soluciones: desarrollo a medida, ecosistemas web y presencia digital, sistemas de gestión operativa | Tarjetas de servicio estructuradas semánticamente |
| **`contacto.html`** | Canales directos de contacto con enlaces ya configurados | Tarjetas de contacto con iconografía SVG |

---

## 🎨 Sistema de Diseño

- **Jerarquía tipográfica:** *Google Sans Flex* para títulos y elementos de impacto, *Roboto* para el cuerpo de texto por su alta legibilidad en pantalla, y *Stack Sans Headline* para acentos y niveles intermedios. La combinación guía la lectura sin necesidad de recursos visuales adicionales.

- **Identidad de marca consistente:** el logo acompaña al usuario en las cinco vistas, reforzando el reconocimiento visual a lo largo de todo el recorrido.

- **Lenguaje visual unificado:** tarjetas, secciones y artículos comparten una misma gramática de espaciado, bordes y sombras. Esta repetición deliberada genera coherencia y sensación de solidez.

- **Micro-interacciones sutiles:** sombreados, bordes redondeados y transiciones suaves del carrusel aportan profundidad y modernidad sin comprometer el rendimiento ni distraer del contenido.

---

## 🚀 Instalación y Puesta en Marcha

El proyecto es completamente estático: **no requiere instalar dependencias, gestores de paquetes ni ejecutar procesos de compilación**. Puede ejecutarse de inmediato tras clonarlo.

```bash
# 1. Clonar el repositorio
git clone https://github.com/Desarollo-web-coder-house/Mi-Portafolio.git

# 2. Acceder al directorio del proyecto
cd Mi-Portafolio

# 3. Abrir index.html en el navegador
#    Recomendado: usar la extensión "Live Server" de VS Code,
#    que simula un servidor local con recarga automática al guardar.
```

> 💡 **Recomendación técnica:** el sitio utiliza rutas relativas entre `index.html` y las vistas alojadas en `pages/`. Por eso conviene servirlo mediante un servidor local (Live Server, `http-server`, `serve`) en lugar de abrir los archivos directamente con doble clic (protocolo `file://`), que puede provocar fallos en la carga de imágenes y estilos.

---

## 🌐 Despliegue en GitHub Pages

El sitio está publicado en **GitHub Pages**, que toma el contenido del repositorio y lo sirve como una página web accesible desde cualquier navegador, sin costo y sin necesidad de configurar un servidor propio.

**🔗 Sitio publicado:** https://desarollo-web-coder-house.github.io/Mi-Portafolio/

### Cómo replicar este despliegue

1. Subir el proyecto a un repositorio público de GitHub.
2. Ingresar a **Settings → Pages** dentro del repositorio.
3. En *Source*, seleccionar la rama principal (`main`) y la carpeta raíz (`/root`).
4. Guardar los cambios y esperar unos instantes: GitHub genera la URL pública automáticamente.
5. A partir de ese momento, **cada `push` actualiza el sitio en vivo** sin pasos adicionales.

### Alternativas de despliegue

| Plataforma | Ventaja principal |
|---|---|
| **GitHub Pages** ⭐ | Gratuito, integrado al repositorio, despliegue automático *(opción actual)* |
| **Netlify** | Publicación continua con vistas previas de cada cambio antes de publicarlo |
| **Vercel** | Distribución global de alto rendimiento con configuración mínima |

---

## 🗺️ Mapa del Sitio

| Página | Ruta | Propósito |
|---|---|---|
| **Inicio** | [`/`](https://desarollo-web-coder-house.github.io/Mi-Portafolio/) | Primera impresión, propuesta de valor y acceso al resto del sitio |
| **Sobre mí** | [`/pages/sobre_mi.html`](https://desarollo-web-coder-house.github.io/Mi-Portafolio/pages/sobre_mi.html) | Construir confianza mediante trayectoria, formación y filosofía de trabajo |
| **Proyectos** | [`/pages/proyectos.html`](https://desarollo-web-coder-house.github.io/Mi-Portafolio/pages/proyectos.html) | Demostrar capacidad técnica con trabajos concretos |
| **Servicios** | [`/pages/servicios.html`](https://desarollo-web-coder-house.github.io/Mi-Portafolio/pages/servicios.html) | Presentar de forma ordenada la oferta de soluciones |
| **Contacto** | [`/pages/contacto.html`](https://desarollo-web-coder-house.github.io/Mi-Portafolio/pages/contacto.html) | Facilitar el primer contacto con el menor esfuerzo posible |

---

## 🧱 Principios de Trabajo y Buenas Prácticas

- **📱 Mobile First** — El diseño se concibe primero para la pantalla más pequeña y luego se amplía. Este orden garantiza que la experiencia móvil, hoy mayoritaria, nunca quede relegada a un segundo plano.

- **🏷️ Código con significado (semántica)** — Uso disciplinado de etiquetas como `<header>`, `<main>`, `<section>`, `<article>` y `<footer>`. Esto permite que buscadores y tecnologías de asistencia comprendan la estructura del sitio, no solo su apariencia.

- **🧩 Separación de responsabilidades** — Contenido (HTML), presentación (CSS) y comportamiento (JavaScript) se mantienen en capas independientes. Modificar el diseño nunca implica tocar el contenido, y viceversa.

- **🔗 Rutas relativas consistentes** — La jerarquía de carpetas está diseñada para que todos los enlaces funcionen correctamente, tanto en entorno local como en producción.

- **📝 Nomenclatura descriptiva** — Clases con nombres claros y autoexplicativos (`contenido_principal`, `tarjeta_contacto`, `navbar_propia`) que permiten entender la función de cada bloque con solo leerlo.

- **🛡️ Mejora progresiva** — El sitio permanece legible y funcional incluso si algún recurso externo (una fuente, un ícono) no llega a cargar. La experiencia se degrada con elegancia, nunca se rompe.

- **♻️ No repetirse (principio DRY)** — Los componentes compartidos —barra de navegación, pie de página, tarjetas— mantienen una estructura idéntica entre vistas, de modo que una corrección se aplica una sola vez y de forma predecible.

---

## ♿ Accesibilidad y Posicionamiento (SEO)

Un sitio accesible es, además, un sitio mejor posicionado: ambos objetivos comparten las mismas buenas prácticas.

- **Textos alternativos descriptivos** en la totalidad de las imágenes, para que su contenido sea comprensible mediante lectores de pantalla.
- **Etiquetas descriptivas** (`aria-label`, `aria-controls`, `aria-expanded`) en todos los elementos interactivos, como el botón del menú y los controles del carrusel.
- **Jerarquía de encabezados respetada** (`h1` a `h4`), sin alterarla por razones estéticas. Esto favorece tanto la navegación asistida como la interpretación del contenido por parte de los buscadores.
- **Enlaces externos seguros** mediante `rel="noopener noreferrer"`, previniendo vulnerabilidades conocidas al abrir páginas en pestañas nuevas.
- **Configuración correcta de `viewport`**, asegurando una visualización adaptada desde el primer instante de carga en dispositivos móviles.

---

## ⚡ Rendimiento y Optimización

- **Íconos SVG integrados directamente en el código**, en lugar de descargar librerías completas de íconos: menos peso y menos peticiones al servidor.
- **`preconnect` a Google Fonts**, que anticipa la conexión con el servidor tipográfico y reduce el tiempo de espera antes de que el texto se muestre correctamente.
- **Bootstrap servido desde CDN** con verificación de integridad (`integrity` + `crossorigin`), lo que aprovecha la caché del navegador y garantiza que el archivo recibido no haya sido alterado.
- **Recursos visuales optimizados** y una estructura de documento pensada para que el contenido esencial se muestre primero.
- **Sitio 100 % estático**, sin base de datos ni lógica de servidor: la respuesta es prácticamente instantánea.

---


## 🌍 Compatibilidad

| Navegador | Soporte |
|---|:---:|
| Google Chrome | ✅ |
| Mozilla Firefox | ✅ |
| Microsoft Edge | ✅ |
| Safari (macOS / iOS) | ✅ |
| Opera | ✅ |

Compatible con las dos últimas versiones estables de cada navegador, siguiendo los estándares de soporte oficiales de Bootstrap 5.

---

## 👩‍💻 Sobre la Autora

**Daniela Romero** es desarrolladora web y de aplicaciones móviles, formada en **Desarrollo Web Full Stack** y en **Desarrollo de Aplicaciones Móviles**. Su enfoque profesional se sostiene sobre cinco pilares:

| Pilar | En qué se traduce |
|---|---|
| 🏗️ **Arquitectura sólida y escalable** | Bases de código pensadas para crecer sin volverse frágiles |
| 🎨 **Diseño centrado en el usuario (UX/UI)** | Cada decisión visual responde a una necesidad real de uso |
| ⏱️ **Cumplimiento metódico de plazos** | Entregas puntuales y planificación realista desde el inicio |
| ✅ **Calidad de código y buenas prácticas** | Código legible, documentado y mantenible en el tiempo |
| 💬 **Comunicación transparente** | Alineación constante con el cliente durante todo el proceso |

Su stack técnico abarca el desarrollo **frontend y backend web**, el desarrollo de **aplicaciones móviles** y servicios en la nube, complementado con competencias sólidas en diseño de interfaces, optimización de rendimiento y resolución analítica de problemas.

---

## 📬 Contacto

¿Tenés un proyecto en mente o buscás digitalizar tu empresa? Conversemos y convirtamos esa idea en una solución digital concreta.

<div align="center">

[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/5493544656873)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:daniela.romero.developer@gmail.com)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/daniela.romero___)
[![Portafolio](https://img.shields.io/badge/Portafolio_Web-1a73e8?style=for-the-badge&logo=googlechrome&logoColor=white)](https://desarollo-web-coder-house.github.io/Mi-Portafolio/)

</div>

---

## 📄 Licencia

Este proyecto se publica con fines de exhibición profesional. Todos los derechos sobre el diseño, la estructura de contenido y los recursos visuales pertenecen a **Daniela Romero**. Queda prohibida su reproducción total o parcial —con fines comerciales o como portafolio propio— sin autorización previa y expresa de la autora.

---

<div align="center">

© 2026 Daniela Romero — Desarrolladora Web y de Apps

Hecho con precisión técnica, criterio estético y atención al detalle.

🔗 desarollo-web-coder-house.github.io/Mi-Portafolio
</div>
