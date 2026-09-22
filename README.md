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

*Diseño y construcción de experiencias digitales claras, sólidas, responsivas y preparadas para crecer.*

<br>

### 🔗 **[VER SITIO EN VIVO →](https://desarollo-web-coder-house.github.io/Mi-Portafolio/)**

[![Ver Demo](https://img.shields.io/badge/🚀_Visitar_Portafolio-1a73e8?style=for-the-badge)](https://desarollo-web-coder-house.github.io/Mi-Portafolio/)
[![Repositorio](https://img.shields.io/badge/📂_Código_Fuente-24292e?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Desarollo-web-coder-house/Mi-Portafolio)

</div>

---

## 📌 Pre-entrega 8 — Animaciones y Full Responsive

Esta versión corresponde a la **Pre-entrega 8** del proyecto y representa la última capa de evolución visual y técnica del portafolio.

El objetivo principal de esta etapa es conservar la identidad visual desarrollada durante las entregas anteriores y, sobre esa base, incorporar **animaciones sutiles, una arquitectura SCSS más avanzada y un cierre integral de la responsividad**.

La implementación se realizó sin reemplazar la estructura existente del proyecto. Los nuevos recursos se integran dentro de la arquitectura SCSS ya definida, manteniendo `scss/main.scss` como único punto de entrada.

### Objetivos alcanzados

- Arquitectura SCSS modular y organizada.
- Metodología **Mobile First**.
- Breakpoints ascendentes en `768px` y `1024px`.
- Animaciones nativas mediante `transition`, `transform` y estados interactivos.
- Integración de la librería **AOS (Animate On Scroll)**.
- Uso de **mixins parametrizados**.
- Uso de **`@extend`**.
- Uso de **operadores SCSS**.
- Mantenimiento de la identidad visual, paleta cromática y estructura HTML.
- Ajustes responsive en las cinco páginas del portafolio.
- Corrección del centrado responsive de los controles del carrusel de proyectos.
- CSS final generado a partir de SCSS.

---

## 📖 Tabla de Contenidos

- [🌐 Portafolio Profesional — Daniela Romero](#-portafolio-profesional--daniela-romero)
    - [**Desarrolladora Web y de Aplicaciones**](#desarrolladora-web-y-de-aplicaciones)
    - [🔗 **VER SITIO EN VIVO →**](#-ver-sitio-en-vivo-)
  - [📌 Pre-entrega 8 — Animaciones y Full Responsive](#-pre-entrega-8--animaciones-y-full-responsive)
    - [Objetivos alcanzados](#objetivos-alcanzados)
  - [📖 Tabla de Contenidos](#-tabla-de-contenidos)
  - [🔗 Sitio en Producción](#-sitio-en-producción)
  - [🎯 Objetivo del Proyecto](#-objetivo-del-proyecto)
  - [✨ Características Principales](#-características-principales)
  - [🎬 Animaciones e Interactividad](#-animaciones-e-interactividad)
    - [1. Animación nativa](#1-animación-nativa)
    - [2. Librería AOS](#2-librería-aos)
    - [3. Carrusel de proyectos](#3-carrusel-de-proyectos)
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
  - [♿ Accesibilidad](#-accesibilidad)
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

El proyecto consiste en un **portafolio profesional de desarrollo web y aplicaciones**, diseñado para presentar de forma clara la identidad profesional, formación, proyectos, servicios y medios de contacto.

La Pre-entrega 8 parte de la versión desarrollada en módulos anteriores y profundiza especialmente en tres áreas:

1. **Animación e interacción visual.**
2. **Uso avanzado de SCSS.**
3. **Responsividad integral mediante una estrategia Mobile First.**

El criterio central de esta etapa es mejorar la experiencia de interacción sin alterar la identidad visual previamente construida.

---

## ✨ Características Principales

- **📱 Diseño Mobile First:** la estructura parte de dispositivos móviles y escala progresivamente hacia tablet y escritorio.
- **🧭 Navegación responsive:** menú adaptable a distintos tamaños de pantalla.
- **🎠 Carruseles interactivos:** navegación mediante controles e indicadores, con adaptación responsive.
- **🎬 Animaciones nativas:** transiciones y transformaciones aplicadas de manera sutil a elementos interactivos.
- **✨ Animaciones AOS:** incorporación de animaciones al desplazarse por determinadas secciones.
- **🧩 Arquitectura SCSS modular:** estilos separados por responsabilidad.
- **🎨 Identidad visual preservada:** se mantienen la paleta cromática, tipografías, componentes y lenguaje visual del proyecto.
- **♿ Consideraciones de accesibilidad:** atributos descriptivos y estructura semántica.
- **🌐 Publicación online:** despliegue mediante GitHub Pages.

---

## 🎬 Animaciones e Interactividad

La Pre-entrega 8 incorpora dos mecanismos de animación, de acuerdo con los requisitos del módulo.

### 1. Animación nativa

Se utilizan recursos propios de CSS/SCSS, principalmente:

- `transition`
- `transform`
- `:hover`
- `:focus`
- `:active`

Las transiciones tienen como objetivo acompañar la interacción del usuario sin interferir con la navegación ni generar movimientos innecesarios.

Los `transform` existentes del proyecto se conservan como parte de la identidad interactiva desarrollada anteriormente.

### 2. Librería AOS

Se integra **AOS (Animate On Scroll)** para incorporar animaciones asociadas al desplazamiento de la página.

Los documentos HTML incluyen:

- hoja de estilos de AOS;
- biblioteca JavaScript de AOS;
- atributos `data-aos` en los elementos seleccionados;
- inicialización mediante `AOS.init()`.

La animación se utiliza como recurso complementario y no como sustituto de la estructura visual del sitio.

### 3. Carrusel de proyectos

El carrusel de `proyectos.html` conserva sus controles interactivos y cuenta con un ajuste específico para garantizar su **centrado vertical en diferentes tamaños de pantalla**.

Este ajuste se incorporó dentro del partial correspondiente de componentes, evitando modificar innecesariamente el resto del diseño.

---

## 🎨 Arquitectura SCSS

La hoja de estilos se encuentra completamente organizada mediante **SCSS**, utilizando `scss/main.scss` como único punto de entrada.

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

Esta organización permite mantener el código separado por responsabilidades y facilita futuras modificaciones.

---

## 🧩 Recursos Avanzados de SCSS

La Pre-entrega 8 profundiza el uso de las funcionalidades del preprocesador.

### Mixin con parámetros

Se utilizan **mixins parametrizados** para evitar repetir declaraciones y permitir reutilizar estilos con diferentes valores.

Conceptualmente:

```scss
@mixin ejemplo($fondo, $color, $radio) {
  background-color: $fondo;
  color: $color;
  border-radius: $radio;
}
```

Los valores se reciben como parámetros y pueden adaptarse según el componente que utilice el mixin.

### `@extend`

Se utiliza `@extend` para compartir un conjunto de propiedades entre componentes relacionados, evitando duplicación innecesaria de estilos.

### Operadores SCSS

También se incorporan operaciones con variables, por ejemplo:

```scss
$spacing-unit: 10px;

padding: $spacing-unit * 2;
```

El operador permite construir valores a partir de variables y mantener una lógica de espaciado reutilizable.

### Nesting y `&`

Se mantiene el uso de nesting y del selector padre `&` para organizar estados y relaciones entre elementos:

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

La responsividad de la Pre-entrega 8 sigue estrictamente una metodología **Mobile First**.

### Base — Mobile

Los estilos principales se aplican sin media query y están pensados inicialmente para pantallas pequeñas.

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

La estrategia evita depender de media queries descendentes y permite ampliar progresivamente la interfaz.

### Verificación responsive

Las cinco páginas fueron contempladas para los siguientes escenarios:

| Vista | Mobile | Tablet | Escritorio |
|---|---:|---:|---:|
| Inicio | ✅ | ✅ | ✅ |
| Sobre mí | ✅ | ✅ | ✅ |
| Proyectos | ✅ | ✅ | ✅ |
| Servicios | ✅ | ✅ | ✅ |
| Contacto | ✅ | ✅ | ✅ |

El objetivo de esta etapa es evitar:

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
│   ├── logo.png
│   ├── hero_section.png
│   ├── Perfil.jpeg
│   ├── Proyectos/
│   └── Servicios/
│
└── pages/
    ├── sobre_mi.html
    ├── proyectos.html
    ├── servicios.html
    └── contacto.html
```

La separación de recursos facilita la lectura del proyecto, el mantenimiento y la incorporación de futuras funcionalidades.

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
| Animaciones | CSS3 / SCSS | Transiciones y transformaciones nativas |
| Animaciones externas | AOS | Animaciones al desplazarse |
| Interactividad | JavaScript / Bootstrap Bundle | Navbar y carruseles |
| Tipografía | Google Fonts | Identidad tipográfica |
| Versionado | Git & GitHub | Control de versiones |
| Despliegue | GitHub Pages | Publicación del sitio |

---

## 🎨 Sistema de Diseño

La Pre-entrega 8 mantiene deliberadamente el sistema visual construido durante las etapas anteriores.

### Identidad cromática

No se reemplaza la paleta existente. Los colores se mantienen centralizados en las variables SCSS correspondientes para asegurar consistencia entre las distintas vistas.

### Tipografía

Se mantienen las familias tipográficas utilizadas anteriormente:

- **Google Sans Flex**
- **Roboto**
- **Stack Sans Headline**

### Componentes

La interfaz conserva:

- tarjetas;
- botones;
- navegación;
- carruseles;
- secciones informativas;
- pie de página.

Las animaciones agregadas funcionan como **micro-interacciones**, sin modificar la composición visual original.

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

Esto genera el archivo:

```text
css/style.css
```

### 5. Compilación automática durante el desarrollo

```bash
npm run watch
```

### 6. Visualización local

Se recomienda utilizar **Live Server** desde Visual Studio Code para ejecutar correctamente las rutas relativas y visualizar los cambios durante el desarrollo.

> `css/style.css` es el archivo CSS generado a partir de `scss/main.scss`. Los cambios de estilos deben realizarse dentro de los partials SCSS y posteriormente compilarse.

---

## 🌐 Despliegue en GitHub Pages

El proyecto se publica mediante GitHub Pages.

### Sitio publicado

https://desarollo-web-coder-house.github.io/Mi-Portafolio/

### Flujo de actualización

```bash
git add .
git commit -m "Actualización Pre-entrega 8"
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
- **📝 Nomenclatura clara:** las clases mantienen nombres descriptivos.
- **🔗 Rutas relativas consistentes:** permiten mantener la navegación entre las distintas páginas.
- **🎯 Animaciones con propósito:** los efectos visuales acompañan la interacción y no reemplazan la funcionalidad.
- **📐 Breakpoints ascendentes:** se utiliza `min-width` para ampliar progresivamente la interfaz.

---

## ♿ Accesibilidad

Se mantienen prácticas orientadas a mejorar la accesibilidad:

- textos alternativos en imágenes;
- etiquetas descriptivas para controles;
- atributos `aria-label`, `aria-controls` y `aria-expanded` cuando corresponden;
- jerarquía de encabezados;
- configuración adecuada del viewport;
- estados `:focus` para elementos interactivos.

---

## ⚡ Rendimiento

El proyecto prioriza una estructura liviana y organizada:

- Bootstrap se incorpora mediante CDN;
- las animaciones se mantienen sutiles;
- los estilos se generan desde una arquitectura SCSS modular;
- se evita duplicar reglas innecesariamente;
- el sitio mantiene una estructura estática y de fácil despliegue.

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

**Pre-entrega 8 · Animaciones · SCSS avanzado · Full Responsive**

</div>
