# 🌐 Portafolio Profesional — Daniela Romero

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![SCSS](https://img.shields.io/badge/SCSS-CSS3-CC6699?style=for-the-badge&logo=sass&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap_5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![AOS](https://img.shields.io/badge/AOS-Animation-6C63FF?style=for-the-badge)
![Responsive](https://img.shields.io/badge/Diseño-Mobile--First-2ea44f?style=for-the-badge)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?style=for-the-badge&logo=githubpages&logoColor=white)

### **Desarrolladora Web y de Aplicaciones**

*Diseño y construcción de experiencias digitales claras, sólidas, responsivas, accesibles y preparadas para crecer.*

<br>

### 🔗 **[VER SITIO EN VIVO →](https://desarollo-web-coder-house.github.io/Mi-Portafolio/)**

[![Ver Demo](https://img.shields.io/badge/🚀_Visitar_Portafolio-1a73e8?style=for-the-badge)](https://desarollo-web-coder-house.github.io/Mi-Portafolio/)
[![Repositorio](https://img.shields.io/badge/📂_Código_Fuente-24292e?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Desarollo-web-coder-house/Mi-Portafolio)

</div>

---

## 📖 Tabla de Contenidos

- [🌐 Portafolio Profesional — Daniela Romero](#-portafolio-profesional--daniela-romero)
    - [**Desarrolladora Web y de Aplicaciones**](#desarrolladora-web-y-de-aplicaciones)
    - [🔗 **VER SITIO EN VIVO →**](#-ver-sitio-en-vivo-)
  - [📖 Tabla de Contenidos](#-tabla-de-contenidos)
  - [🔗 Sitio en Producción](#-sitio-en-producción)
  - [🎯 Objetivo del Proyecto](#-objetivo-del-proyecto)
  - [✨ Características Principales](#-características-principales)
  - [🎬 Animaciones e Interactividad](#-animaciones-e-interactividad)
    - [Animación nativa](#animación-nativa)
    - [Librería AOS](#librería-aos)
    - [Carrusel de proyectos](#carrusel-de-proyectos)
  - [🔎 Estrategia SEO](#-estrategia-seo)
    - [SEO On-Page](#seo-on-page)
    - [Metadatos](#metadatos)
    - [Keywords](#keywords)
    - [Semántica HTML](#semántica-html)
    - [Nomenclatura SEO de recursos](#nomenclatura-seo-de-recursos)
    - [SEO técnico y publicación](#seo-técnico-y-publicación)
  - [♿ Accesibilidad](#-accesibilidad)
  - [🎨 Arquitectura SCSS](#-arquitectura-scss)
    - [Responsabilidad de cada capa](#responsabilidad-de-cada-capa)
  - [🧩 Recursos Avanzados de SCSS](#-recursos-avanzados-de-scss)
    - [Mixin con parámetros](#mixin-con-parámetros)
    - [`@extend`](#extend)
    - [Operadores SCSS](#operadores-scss)
    - [Nesting y `&`](#nesting-y-)
  - [📱 Estrategia Responsive](#-estrategia-responsive)
    - [Base — Mobile](#base--mobile)
    - [Tablet — `768px`](#tablet--768px)
    - [Escritorio — `1024px`](#escritorio--1024px)
    - [Verificación responsive](#verificación-responsive)
  - [📂 Arquitectura del Proyecto](#-arquitectura-del-proyecto)
  - [🔍 Detalle Técnico por Vista](#-detalle-técnico-por-vista)
  - [🛠️ Stack Tecnológico](#️-stack-tecnológico)
  - [🎨 Sistema de Diseño](#-sistema-de-diseño)
    - [Identidad cromática](#identidad-cromática)
    - [Tipografía](#tipografía)
    - [Componentes](#componentes)
  - [🚀 Instalación y Desarrollo](#-instalación-y-desarrollo)
    - [1. Clonar el repositorio](#1-clonar-el-repositorio)
    - [2. Acceder al proyecto](#2-acceder-al-proyecto)
    - [3. Instalar dependencias](#3-instalar-dependencias)
    - [4. Compilar SCSS](#4-compilar-scss)
    - [5. Compilación automática durante el desarrollo](#5-compilación-automática-durante-el-desarrollo)
    - [6. Visualización local](#6-visualización-local)
  - [🌐 Despliegue en GitHub Pages](#-despliegue-en-github-pages)
    - [Sitio publicado](#sitio-publicado)
    - [Flujo de actualización](#flujo-de-actualización)
  - [🗺️ Mapa del Sitio](#️-mapa-del-sitio)
  - [🧱 Buenas Prácticas](#-buenas-prácticas)
  - [⚡ Rendimiento](#-rendimiento)
  - [🌍 Compatibilidad](#-compatibilidad)
  - [👩‍💻 Sobre la Autora](#-sobre-la-autora)
  - [📬 Contacto](#-contacto)
  - [📄 Licencia](#-licencia)

---

## 🔗 Sitio en Producción

El portafolio se encuentra publicado mediante **GitHub Pages**, permitiendo acceder a la versión funcional directamente desde un navegador.

| Recurso | Enlace |
|---|---|
| 🌐 **Sitio en vivo** | [desarollo-web-coder-house.github.io/Mi-Portafolio](https://desarollo-web-coder-house.github.io/Mi-Portafolio/) |
| 📂 **Repositorio** | [github.com/Desarollo-web-coder-house/Mi-Portafolio](https://github.com/Desarollo-web-coder-house/Mi-Portafolio) |
| 🔄 **Actualización** | Mediante commits y `push` al repositorio |

---

## 🎯 Objetivo del Proyecto

El proyecto consiste en un **portafolio profesional de desarrollo web y aplicaciones**, concebido para comunicar de forma clara la identidad profesional, formación, competencias, proyectos, servicios y canales de contacto.

El desarrollo se construye de manera incremental sobre una base HTML5, CSS/SCSS, Bootstrap y JavaScript, incorporando progresivamente:

1. **Arquitectura SCSS modular y mantenible.**
2. **Diseño responsive bajo metodología Mobile First.**
3. **Componentes interactivos y micro-interacciones visuales.**
4. **Animaciones nativas mediante CSS/SCSS y animaciones al desplazarse mediante AOS.**
5. **Optimización SEO On-Page y fortalecimiento de la semántica HTML5.**
6. **Mejoras de accesibilidad y nomenclatura descriptiva de recursos.**
7. **Preparación y consolidación del sitio para publicación mediante GitHub Pages.**

Todas las mejoras técnicas se integran sobre la estructura existente, priorizando la **consistencia visual, reutilización, mantenibilidad y experiencia de usuario**, sin alterar innecesariamente la identidad gráfica del proyecto.

---

## ✨ Características Principales

- **📱 Diseño Mobile First:** la estructura parte de dispositivos móviles y escala progresivamente hacia tablet y escritorio.
- **🧭 Navegación responsive:** menú adaptable a diferentes resoluciones.
- **🎠 Carruseles interactivos:** navegación mediante controles e indicadores con comportamiento responsive.
- **🎬 Animaciones nativas:** utilización de `transition`, `transform` y estados interactivos como `:hover`, `:focus` y `:active`.
- **✨ Animaciones AOS:** incorporación de efectos asociados al desplazamiento de la página.
- **🧩 Arquitectura SCSS modular:** estilos organizados por responsabilidad mediante partials y un único punto de entrada.
- **🔎 SEO On-Page:** títulos, metadescripciones, keywords y contenido contextualizado para cada vista.
- **🏷️ HTML semántico:** utilización de encabezados y elementos estructurales adecuados.
- **🖼️ Recursos descriptivos:** nombres de archivos normalizados y atributos `alt` contextualizados.
- **♿ Accesibilidad:** consideración de foco, etiquetas descriptivas, estructura semántica, contraste y atributos ARIA cuando corresponden.
- **🎨 Identidad visual preservada:** se mantienen paleta cromática, tipografías, componentes y lenguaje visual.
- **🌐 Publicación online:** despliegue mediante GitHub Pages.

---

## 🎬 Animaciones e Interactividad

El proyecto incorpora una capa de interacción visual orientada a mejorar la experiencia de navegación sin interferir con la funcionalidad.

### Animación nativa

La capa de animación propia del proyecto combina recursos de CSS/SCSS orientados a mejorar la interacción sin alterar la identidad visual:

- `@keyframes` propio para una entrada suave del sitio;
- `animation` para ejecutar la animación nativa;
- `transition`;
- `transform`;
- `:hover`;
- `:focus`;
- `:active`.

El `@keyframes entradaSuave` se encuentra integrado en `scss/base/_base.scss` y utiliza únicamente la propiedad `opacity`, por lo que la apariencia final, la distribución, los colores y los componentes existentes permanecen sin modificaciones.

Las transiciones funcionan como **micro-interacciones**, aportando respuesta visual a botones, enlaces y otros elementos interactivos.

Los `transform` existentes se conservan como parte de la evolución visual del proyecto y se aplican de manera controlada.

Además, se incorpora `prefers-reduced-motion` para desactivar la animación nativa cuando el usuario solicita reducir el movimiento, manteniendo la accesibilidad del sitio.

### Librería AOS

Se integra **AOS (Animate On Scroll)** como recurso complementario para animar determinados elementos al desplazarse por las páginas.

La integración contempla:

- hoja de estilos de AOS;
- biblioteca JavaScript de AOS;
- atributos `data-aos` en los elementos seleccionados;
- inicialización mediante `AOS.init()`.

### Carrusel de proyectos

El carrusel de `proyectos.html` mantiene sus controles interactivos y cuenta con un ajuste responsive específico para garantizar el **centrado vertical de los controles en diferentes tamaños de pantalla**.

La corrección se integra dentro de la arquitectura SCSS del proyecto, evitando modificar innecesariamente el resto de la composición.

---

## 🔎 Estrategia SEO

La optimización SEO se incorpora como una capa técnica transversal, orientada a mejorar la **comprensión temática, indexabilidad, accesibilidad y claridad estructural** del sitio, manteniendo intacta su presentación visual.

### SEO On-Page

La optimización se aplica directamente sobre los documentos HTML y contempla:

- títulos de página específicos y descriptivos;
- metadescripciones diferenciadas según el contenido de cada vista;
- keywords contextualizadas, evitando prácticas de **keyword stuffing**;
- jerarquía de encabezados coherente;
- contenido textual relacionado con la temática de cada página;
- estructura HTML5 semántica;
- atributos `alt` descriptivos en los recursos gráficos.

### Metadatos

Cada documento HTML incorpora metadatos acordes con su propósito:

```html
<title>Título específico de la página</title>
<meta name="description" content="Descripción contextualizada del contenido de la página.">
<meta name="keywords" content="keywords relacionadas con la página">
```

Las descripciones se mantienen diferenciadas entre **Inicio, Sobre mí, Proyectos, Servicios y Contacto**, evitando utilizar una descripción genérica para todo el sitio.

### Keywords

Las palabras clave se seleccionan de acuerdo con la intención y contenido de cada vista, priorizando la **relevancia semántica** frente a la repetición artificial.

Entre los conceptos trabajados se encuentran:

- desarrollo web;
- desarrollo de aplicaciones;
- servicios de desarrollo;
- proyectos web;
- perfil profesional;
- competencias técnicas;
- contacto profesional.

### Semántica HTML

Se mantiene como criterio:

- un único `<h1>` por documento;
- encabezados `<h2>` y `<h3>` en orden jerárquico;
- utilización de elementos como `<header>`, `<nav>`, `<main>`, `<section>`, `<article>` y `<footer>` cuando corresponde;
- reducción de contenedores genéricos innecesarios;
- contenido estructurado de acuerdo con su función.

### Nomenclatura SEO de recursos

Los recursos gráficos utilizan nombres descriptivos, legibles y consistentes.

La convención adoptada es:

```text
nombre-descriptivo-del-recurso.ext
```

Se priorizan:

- minúsculas;
- palabras separadas mediante guiones medios (`-`);
- nombres descriptivos;
- ausencia de nombres genéricos;
- extensión coherente con el formato real del recurso.

Ejemplos:

```text
logo-daniela-romero.png
hero-desarrolladora-web-daniela-romero.png
foto-profesional-daniela-romero.jpeg
servicio-arquitectura-backend.png
sistema-punto-de-venta.png
```

Esta nomenclatura facilita el mantenimiento del proyecto y aporta mayor claridad semántica a las rutas de recursos.

### SEO técnico y publicación

La estructura del sitio mantiene rutas relativas consistentes, documentos HTML diferenciados y una organización de recursos compatible con un despliegue estático.

La publicación se realiza mediante **GitHub Pages**, utilizando el repositorio como fuente del código y de los recursos del sitio.

---

## ♿ Accesibilidad

La accesibilidad se considera como parte de la optimización técnica y semántica del proyecto.

Se contemplan:

- **atributos `alt` descriptivos** en las imágenes;
- textos alternativos relacionados con el contenido real de cada recurso;
- etiquetas y nombres comprensibles para elementos interactivos;
- atributos `aria-label`, `aria-controls` y `aria-expanded` cuando corresponden;
- jerarquía de encabezados coherente;
- configuración adecuada del viewport;
- estados `:focus` para elementos interactivos;
- revisión del contraste entre fondos y textos;
- estructura semántica HTML5 compatible con una interpretación más clara del contenido.

El objetivo es que la optimización técnica contribuya tanto a la indexabilidad como a una experiencia digital más clara, perceptible y navegable.

---

## 🎨 Arquitectura SCSS

La hoja de estilos se encuentra organizada mediante **SCSS**, utilizando `scss/main.scss` como único punto de entrada.

```text
scss/
│
├── main.scss
│
├── utilities/
│   ├── _variables.scss
│   └── _mixins.scss
│
├── base/
│   ├── _tipografia.scss
│   └── _base.scss
│
├── layout/
│   ├── _header.scss
│   ├── _footer.scss
│   └── _nav.scss
│
└── components/
    ├── _buttons.scss
    └── _cards.scss
```

### Responsabilidad de cada capa

| Carpeta | Responsabilidad |
|---|---|
| `utilities/` | Variables y herramientas reutilizables |
| `base/` | Tipografía y estilos generales |
| `layout/` | Estructura del encabezado, navegación y pie |
| `components/` | Botones, tarjetas, carruseles y componentes visuales |
| `main.scss` | Punto único de entrada y orquestación de los partials |

La arquitectura permite separar responsabilidades, centralizar decisiones visuales y facilitar el mantenimiento y la evolución del proyecto.

---

## 🧩 Recursos Avanzados de SCSS

El proyecto incorpora funcionalidades de SCSS orientadas a la reutilización y reducción de código repetido.

### Mixin con parámetros

Se utilizan **mixins parametrizados** para reutilizar declaraciones con diferentes valores.

```scss
@mixin ejemplo($fondo, $color, $radio) {
  background-color: $fondo;
  color: $color;
  border-radius: $radio;
}
```

Los parámetros permiten adaptar el mismo recurso a diferentes componentes.

### `@extend`

Se utiliza `@extend` para compartir conjuntos de propiedades entre componentes relacionados, evitando duplicación innecesaria.

### Operadores SCSS

Se incorporan operaciones con variables para construir valores reutilizables:

```scss
$spacing-unit: 10px;

padding: $spacing-unit * 2;
```

### Nesting y `&`

El nesting y el selector padre `&` permiten organizar estados y relaciones entre elementos:

```scss
.elemento {
  &.activo {
    /* estado */
  }

  &:focus {
    /* accesibilidad */
  }
}
```

---

## 📱 Estrategia Responsive

La responsividad sigue una metodología estrictamente **Mobile First**, partiendo de estilos base para pantallas pequeñas y ampliando progresivamente la interfaz.

### Base — Mobile

Los estilos principales se aplican sin media query y están pensados inicialmente para dispositivos móviles.

### Tablet — `768px`

```scss
@media (min-width: 768px) {
  /* ajustes para tablet */
}
```

### Escritorio — `1024px`

```scss
@media (min-width: 1024px) {
  /* ajustes para escritorio */
}
```

La estrategia utiliza **breakpoints ascendentes mediante `min-width`**, evitando depender de media queries descendentes.

### Verificación responsive

Las cinco vistas fueron contempladas para:

| Vista | Mobile | Tablet | Escritorio |
|---|:---:|:---:|:---:|
| Inicio | ✅ | ✅ | ✅ |
| Sobre mí | ✅ | ✅ | ✅ |
| Proyectos | ✅ | ✅ | ✅ |
| Servicios | ✅ | ✅ | ✅ |
| Contacto | ✅ | ✅ | ✅ |

La implementación busca evitar:

- scroll horizontal innecesario;
- contenido superpuesto;
- textos cortados;
- controles fuera de posición;
- elementos que excedan el ancho disponible.

---

## 📂 Arquitectura del Proyecto

```text
Mi-Portafolio/
│
├── index.html
│
├── css/
│   └── style.css
│
├── scss/
│   ├── main.scss
│   ├── utilities/
│   ├── base/
│   ├── layout/
│   └── components/
│
├── img/
│   ├── logo-daniela-romero.png
│   ├── hero-desarrolladora-web-daniela-romero.png
│   ├── foto-profesional-daniela-romero.jpeg
│   ├── Proyectos/
│   └── Servicios/
│
└── pages/
    ├── sobre_mi.html
    ├── proyectos.html
    ├── servicios.html
    └── contacto.html
```

La separación de documentos, estilos y recursos facilita la lectura del proyecto, el mantenimiento y la incorporación de futuras funcionalidades.

---

## 🔍 Detalle Técnico por Vista

| Vista | Contenido | Componentes destacados |
|---|---|---|
| **`index.html`** | Presentación, síntesis de perfil, servicios, proyectos y contacto | Navbar responsive, carrusel Bootstrap y animaciones AOS |
| **`sobre_mi.html`** | Perfil, formación, stack técnico, habilidades y pilares de trabajo | Secciones informativas y componentes responsivos |
| **`proyectos.html`** | Galería ampliada de proyectos | Carrusel, tarjetas, controles responsive y animaciones |
| **`servicios.html`** | Catálogo de servicios ofrecidos | Tarjetas y componentes reutilizables |
| **`contacto.html`** | Canales de comunicación directa | Tarjetas y enlaces de contacto |

---

## 🛠️ Stack Tecnológico

| Categoría | Tecnología | Función |
|---|---|---|
| Estructura | HTML5 | Organización semántica del contenido |
| Estilos | SCSS | Arquitectura modular y generación de CSS |
| Framework UI | Bootstrap 5.0.2 | Grid y componentes responsive |
| Animaciones | CSS3 / SCSS | Transiciones, transformaciones y estados interactivos |
| Animaciones externas | AOS | Animaciones al desplazarse |
| Interactividad | JavaScript / Bootstrap Bundle | Navbar y carruseles |
| Tipografía | Google Fonts | Identidad tipográfica |
| Versionado | Git & GitHub | Control de versiones |
| Despliegue | GitHub Pages | Publicación del sitio |

---

## 🎨 Sistema de Diseño

El sistema visual mantiene la identidad construida durante las diferentes etapas del proyecto.

### Identidad cromática

La paleta existente se conserva y los colores se mantienen centralizados en las variables SCSS correspondientes, favoreciendo la consistencia entre las distintas vistas.

### Tipografía

Se mantienen las familias tipográficas utilizadas en el proyecto:

- **Google Sans Flex**
- **Roboto**
- **Stack Sans Headline**

### Componentes

La interfaz conserva y reutiliza:

- tarjetas;
- botones;
- navegación;
- carruseles;
- secciones informativas;
- pie de página.

Las animaciones funcionan como **micro-interacciones**, complementando la composición visual sin reemplazarla.

---

## 🚀 Instalación y Desarrollo

Para trabajar con el proyecto localmente:

### 1. Clonar el repositorio

```bash
git clone https://github.com/Desarollo-web-coder-house/Mi-Portafolio.git
```

### 2. Acceder al proyecto

```bash
cd Mi-Portafolio
```

### 3. Instalar dependencias

```bash
npm install
```

### 4. Compilar SCSS

```bash
npm run build
```

Esto genera:

```text
css/style.css
```

### 5. Compilación automática durante el desarrollo

```bash
npm run watch
```

### 6. Visualización local

Se recomienda utilizar **Live Server** desde Visual Studio Code para ejecutar correctamente las rutas relativas y visualizar los cambios durante el desarrollo.

> `css/style.css` es el archivo CSS generado a partir de `scss/main.scss`. Las modificaciones de estilos deben realizarse dentro de los partials SCSS y posteriormente compilarse.

---

## 🌐 Despliegue en GitHub Pages

El proyecto se publica mediante GitHub Pages.

### Sitio publicado

https://desarollo-web-coder-house.github.io/Mi-Portafolio/

### Flujo de actualización

```bash
git add .
git commit -m "Actualización del portafolio"
git push
```

Una vez enviado el commit al repositorio, GitHub Pages actualiza la versión publicada.

---

## 🗺️ Mapa del Sitio

| Página | Ruta | Propósito |
|---|---|---|
| **Inicio** | `/` | Presentación y acceso al resto del sitio |
| **Sobre mí** | `/pages/sobre_mi.html` | Perfil, formación y competencias |
| **Proyectos** | `/pages/proyectos.html` | Presentación de proyectos |
| **Servicios** | `/pages/servicios.html` | Catálogo de servicios |
| **Contacto** | `/pages/contacto.html` | Canales de comunicación |

---

## 🧱 Buenas Prácticas

- **📱 Mobile First:** el diseño parte de la pantalla más pequeña.
- **🧩 Separación de responsabilidades:** HTML, SCSS y JavaScript cumplen funciones diferenciadas.
- **♻️ Reutilización:** variables, mixins, `@extend` y componentes reducen la duplicación.
- **🏷️ Semántica HTML:** se utilizan elementos estructurales adecuados para cada contenido.
- **🔎 SEO contextual:** cada página posee metadatos y contenido alineados con su propósito.
- **🖼️ Recursos descriptivos:** las imágenes utilizan nombres de archivo claros y atributos `alt` pertinentes.
- **📝 Nomenclatura consistente:** los recursos utilizan minúsculas y guiones medios como separadores.
- **🔗 Rutas relativas consistentes:** permiten mantener la navegación y las referencias internas.
- **♿ Accesibilidad:** se consideran estructura semántica, textos alternativos, foco, ARIA y contraste.
- **📐 Breakpoints ascendentes:** se utiliza `min-width` para ampliar progresivamente la interfaz.
- **🎯 Animaciones con propósito:** los efectos visuales acompañan la interacción y no reemplazan la funcionalidad.
- **🎨 Integridad visual:** las optimizaciones técnicas se integran sin alterar innecesariamente el sistema visual.

---

## ⚡ Rendimiento

El proyecto prioriza una estructura liviana y organizada:

- Bootstrap se incorpora mediante CDN;
- las animaciones se mantienen sutiles;
- los estilos se generan desde una arquitectura SCSS modular;
- se evita duplicar reglas innecesariamente;
- se mantienen rutas y recursos organizados;
- el sitio conserva una estructura estática de fácil despliegue.

---

## 🌍 Compatibilidad

El diseño está preparado para adaptarse a diferentes tamaños de pantalla y navegadores modernos.

| Navegador | Soporte |
|---|:---:|
| Google Chrome | ✅ |
| Mozilla Firefox | ✅ |
| Microsoft Edge | ✅ |
| Safari | ✅ |
| Opera | ✅ |

---

## 👩‍💻 Sobre la Autora

**Daniela Romero** es desarrolladora web y de aplicaciones móviles, formada en **Desarrollo Web Full Stack** y **Desarrollo de Aplicaciones Móviles**.

Este portafolio funciona tanto como presentación profesional como demostración práctica de conocimientos en:

- desarrollo frontend;
- HTML5 semántico;
- CSS y SCSS;
- Bootstrap;
- JavaScript;
- diseño responsive;
- animaciones e interacción;
- optimización SEO;
- accesibilidad web;
- organización y mantenimiento de código;
- control de versiones con Git y GitHub.

---

## 📬 Contacto

<div align="center">

[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/5493544656873)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:daniela.romero.developer@gmail.com)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/daniela.romero___)
[![Portafolio](https://img.shields.io/badge/Portafolio_Web-1a73e8?style=for-the-badge&logo=googlechrome&logoColor=white)](https://desarollo-web-coder-house.github.io/Mi-Portafolio/)

</div>

---

## 📄 Licencia

Este proyecto se publica con fines de exhibición profesional. Los derechos sobre el diseño, contenido y recursos visuales pertenecen a **Daniela Romero**.

La reproducción total o parcial del proyecto para fines comerciales o como portafolio propio requiere autorización previa de la autora.

---

<div align="center">

© 2026 Daniela Romero — Desarrolladora Web y de Apps

**SCSS · Animaciones · Full Responsive · SEO · Accesibilidad · GitHub Pages**

</div>
