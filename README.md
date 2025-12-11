# 🎵 Tyler, The Creator - Web Discography Tribute

![Project Banner](Media/Pictures/Logo.png)

> **Proyecto de Desarrollo Web** > Una experiencia web inmersiva que recorre la evolución artística y visual de Tyler, The Creator.

## 📖 Descripción

Este proyecto es una aplicación web estática diseñada para explorar la discografía de **Tyler, The Creator**, adaptando la interfaz de usuario (UI) a la estética única de cada uno de sus álbumes. Desde los colores pasteles y nostálgicos de *Call Me If You Get Lost* hasta el brutalismo de *IGOR* y el tono sepia militar de *Chromakopia*.

El objetivo principal ha sido demostrar el dominio de **HTML5 y CSS3**, utilizando arquitecturas de estilos modulares y variables CSS para cambiar radicalmente el "look & feel" de la web sin alterar la estructura semántica base.

**Autor:** Estudiante de 1º de DAM (Desarrollo de Aplicaciones Multiplataforma)  
**Institución:** Institut Vidal i Barraquer (Tarragona)

## ✨ Características Principales

* **Diseño Temático Adaptativo:** Cada página de álbum carga un archivo CSS específico que sobrescribe las variables globales (`global.css`), alterando paletas de colores, tipografías, bordes y espaciados para coincidir con el arte del álbum.
    * 🌻 **Flower Boy:** Tonos cálidos, bordes redondeados y estética de atardecer.
    * 🩷 **IGOR:** Estilo brutalista, alto contraste (negro/rosa), bordes cuadrados y tipografía impactante.
    * 🪪 **CMIYGL:** Estilo documento/pasaporte, tipografía `Courier` y texturas de papel.
    * 👺 **Cherry Bomb:** Colores saturados, rotaciones "punk" y diseño caótico controlado.
    * 🪖 **Chromakopia:** Escala de grises/verdes, estética militar y monocromática.
* **Navegación Intuitiva:** Menú de navegación consistente que permite viajar entre las diferentes "eras" del artista.
* **Contenido Multimedia:** Integración de reproductores de Spotify, iframes de YouTube y galerías de imágenes optimizadas (`webp`).
* **Formularios Estilizados:** Sección de contacto al pie de página que se adapta visualmente al tema de cada álbum.
* **Diseño Responsivo (Flexbox):** Maquetación flexible que se adapta a diferentes resoluciones.

## 🛠️ Tecnologías Utilizadas

* **HTML5:** Estructura semántica (Header, Nav, Main, Article, Aside, Footer).
* **CSS3:**
    * **CSS Variables (Custom Properties):** Para la gestión eficiente de temas (Theming).
    * **Flexbox:** Para la alineación y distribución de elementos.
    * **Efectos:** Hover, transiciones, filtros de imagen (sepia, grayscale) y transformaciones (skew, rotate).

## 📂 Estructura del Proyecto

```text
/Proyecto
├── /Albums             # Páginas HTML individuales por álbum
│   ├── callmeif.html
│   ├── cherrybomb.html
│   ├── chromakopia.html
│   ├── flowerboy.html
│   └── igor.html
├── /css                # Hojas de estilo
│   ├── global.css      # Estilos base y variables por defecto
│   ├── index.css       # Estilos específicos para la Home
│   ├── igor.css        # Tema IGOR
│   ├── ...             # (Otros temas específicos)
├── /Media              # Recursos gráficos
│   └── /Pictures       # Imágenes optimizadas en formato .webp y .png
└── index.html          # Página de aterrizaje (Home)
