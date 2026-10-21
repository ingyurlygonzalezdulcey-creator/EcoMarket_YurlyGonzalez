<div align="center">
  <img src="img/logo/logo.png" width="280">
  <h1>EcoMarket - Yurly Gonzalez</h1>
</div>

# 🌿 EcoMarket — Tienda de productos sostenibles

## 1. Descripción del proyecto

EcoMarket es una propuesta académica de tienda en línea dedicada a productos ecológicos, reutilizables y sostenibles. El sitio presenta un catálogo de productos, información sobre la propuesta de marca y una página de contacto, con una interfaz adaptable a dispositivos móviles, tabletas y computadores.

El proyecto está desarrollado con HTML5 semántico y CSS3 puro, sin JavaScript ni frameworks.

## 2. Objetivos

- Presentar productos sostenibles de manera clara y atractiva.
- Practicar HTML semántico y hojas de estilo externas.
- Aplicar CSS Grid, Flexbox, variables, selectores, pseudoclases y animaciones.
- Diseñar con enfoque Mobile First.
- Documentar el proyecto y controlar sus versiones mediante Git y GitHub.

## 3. Estructura de carpetas

```text
EcoMarket_YurlyGonzalez/
├── css/
│   ├── main.css
│   ├── layout.css
│   ├── components.css
│   └── animations.css
├── img/
│   ├── products/
│   ├── icons/
│   ├── hero/
│   ├── testimonials/
│   └── maps/
├── views/
│   ├── productos.html
│   ├── sobre-nosotros.html
│   └── contacto.html
├── capturas/
├── index.html
└── README.md
```

## 4. Tecnologías utilizadas

- **HTML5:** estructura semántica y contenido.
- **CSS3:** estilos, distribución responsive, estados visuales y animaciones.
- **Git:** control de versiones.
- **GitHub:** alojamiento del repositorio.

No se utilizan JavaScript ni frameworks.

## 5. Sistema visual

La paleta se basa en los colores solicitados en la actividad:

| Uso | Color |
|---|---|
| Verde principal | `#2ecc71` |
| Verde secundario | `#27ae60` |
| Fondo beige suave | `#f5f5dc` |
| Verde oscuro para contraste | `#052e16` |

Las variables reutilizables se encuentran en `css/main.css`. Las tipografías Inter y Fraunces se cargan mediante Google Fonts; si no hay conexión, se utilizan fuentes alternativas del sistema.

## 6. Páginas incluidas

- **Inicio (`index.html`):** banner principal, mensaje de bienvenida y seis productos destacados.
- **Productos (`views/productos.html`):** catálogo de 20 tarjetas, categorías, controles visuales y paginación demostrativa.
- **Sobre nosotros (`views/sobre-nosotros.html`):** historia de la propuesta, principios ecológicos y testimonios de ejemplo.
- **Contacto (`views/contacto.html`):** formulario con validación visual CSS, datos de contacto, mapa ilustrativo y redes sociales.

## 7. Diseño responsive y CSS

El sitio comienza con una distribución para pantallas pequeñas y utiliza media queries para adaptar las tarjetas y secciones a pantallas más amplias. El catálogo se organiza en una columna en móvil, dos en tableta y cuatro en escritorio.

Entre los recursos CSS utilizados se encuentran:

- Variables personalizadas con `:root`.
- CSS Grid y Flexbox.
- Selectores de clase, atributos y combinadores.
- Pseudoclases como `:hover`, `:focus-visible`, `:checked`, `:valid`, `:invalid`, `:target` y `:focus-within`.
- Pseudoelementos `::before` y `::after`.
- Transiciones, `@keyframes` y media queries.
- Preferencia de movimiento reducido.

**Nota funcional:** las categorías y los favoritos se representan con CSS. El buscador, el rango de precios, la disponibilidad y la paginación son elementos demostrativos y no realizan búsquedas o filtrados dinámicos completos, porque el proyecto no utiliza JavaScript. El formulario utiliza `mailto:` y depende de que el dispositivo tenga una aplicación de correo configurada.

## 8. Imágenes pendientes de agregar

Las rutas de imágenes se dejaron definidas en el código para que los archivos puedan agregarse posteriormente. Los nombres deben coincidir exactamente con los siguientes:

### `img/products/` — fotografías de productos

- `botella-reutilizable.jpg`
- `jabon-artesanal.jpg`
- `envolturas-reutilizables.jpg`
- `cepillo-bambu.jpg`
- `kit-cero-desperdicio.jpg`
- `compostera-casera.jpg`
- `bolsa-tela.jpg`
- `champu-solido.jpg`
- `cuchara-madera.jpg`
- `esponja-vegetal.jpg`
- `pitillos-reutilizables.jpg`
- `tapas-reutilizables.jpg`
- `desodorante-natural.jpg`
- `envoltura-multiusos.jpg`
- `tazon-reutilizable.jpg`
- `jabonera-bambu.jpg`
- `bolsas-mercado.jpg`
- `lonchera-reutilizable.jpg`
- `pasta-dental-solida.jpg`
- `kit-higiene-ecologica.jpg`

### `img/icons/` — logotipo e iconos

- `logo-ecomarket.svg`
- `icono-busqueda.svg`
- `icono-carrito.svg`
- `icono-instagram.svg`
- `icono-facebook.svg`

### `img/hero/` — imágenes grandes

- `banner-ecologico.jpg` — fondo del banner principal.
- `imagen-historia-ecomarket.jpg` — imagen de la sección de historia.

### Carpetas complementarias

- `img/testimonials/cliente-ana.jpg`
- `img/testimonials/cliente-carlos.jpg`
- `img/testimonials/cliente-maria.jpg`
- `img/maps/mapa-bucaramanga.jpg`

**Importante:** mientras no agregues los archivos con esos nombres, los espacios de imagen correspondientes no mostrarán fotografías. Puedes usar tus propias imágenes siempre que conserves los nombres indicados o actualices las rutas del HTML/CSS.

## 9. Capturas de pantalla

Agregar capturas reales después de revisar la página en el navegador. Guardarlas en `capturas/` con estos nombres para que aparezcan en GitHub:

### Inicio — escritorio

![Captura de inicio en escritorio](capturas/01-inicio-escritorio.png)

### Inicio — móvil

![Captura de inicio en móvil](capturas/02-inicio-movil.png)

### Catálogo — escritorio

![Captura del catálogo en escritorio](capturas/03-catalogo-escritorio.png)

### Catálogo — móvil

![Captura del catálogo en móvil](capturas/04-catalogo-movil.png)

### Sobre nosotros

![Captura de sobre nosotros](capturas/05-sobre-nosotros.png)

### Contacto

![Captura de contacto](capturas/06-contacto.png)

### Evidencia responsive

![Captura responsive adicional](capturas/07-responsive.png)

## 10. Cómo visualizar el proyecto

1. Descarga o clona el repositorio.
2. Abre la carpeta del proyecto en Visual Studio Code.
3. Abre `index.html` en un navegador, o utiliza la extensión Live Server si está disponible.
4. Navega a las otras páginas desde el menú principal.

No se requiere instalación de paquetes ni dependencias.

## 11. Repositorio y publicación

**Repositorio público de GitHub:**  
[Pegar aquí el enlace del repositorio]

`PENDIENTE: agregar URL del repositorio`

**Sitio web publicado:**  
[Pegar aquí el enlace cuando se publique en Vercel, Netlify u otro servicio]

`PENDIENTE DE PUBLICACIÓN`

![Captura del sitio publicado](capturas/08-sitio-publicado.png)

## 12. Control de versiones

La actividad solicita al menos ocho commits con mensajes descriptivos y uso de ramas de trabajo. Agrega aquí las evidencias o capturas de GitHub que demuestren los commits y las ramas utilizadas.

## 13. Autoría

- **Autor/a:** Yurly González
- **Proyecto:** EcoMarket
- **Tecnologías:** HTML5 y CSS3
- **Estado:** pendiente de agregar imágenes, capturas y enlace de publicación.








# 🌿 EcoMarket — Tienda de productos sostenibles

## 1. Descripción del proyecto

EcoMarket es un sitio web desarrollado como proyecto académico para una tienda virtual de productos sostenibles. Su objetivo es presentar un catálogo de productos ecológicos mediante una interfaz clara, atractiva y adaptable a diferentes dispositivos.

El sitio permite visualizar productos, conocer la información de la empresa y consultar los datos de contacto. Está desarrollado utilizando HTML5 y CSS3, sin JavaScript ni frameworks.

## 2. Objetivos del proyecto

- Diseñar una página web organizada y visualmente atractiva.
- Aplicar etiquetas semánticas de HTML5.
- Utilizar CSS3 para la distribución, los estilos y las animaciones.
- Implementar un diseño responsive con enfoque Mobile First.
- Organizar los archivos mediante una estructura clara de carpetas.
- Utilizar Git y GitHub para el control de versiones y la entrega del proyecto.

## 3. Estructura del proyecto

```text
EcoMarket/
├── css/
│   ├── main.css
│   ├── layout.css
│   ├── components.css
│   └── animations.css
├── img/
│   ├── products/
│   ├── icons/
│   └── hero/
├── views/
│   ├── productos.html
│   ├── sobre-nosotros.html
│   └── contacto.html
├── index.html
└── README.md
```

*Nota: la estructura se verificará y ajustará con los archivos definitivos del proyecto.*

## 4. Tecnologías utilizadas

- **HTML5:** estructura y contenido de las páginas.
- **CSS3:** estilos, distribución, diseño responsive, efectos visuales y animaciones.
- **Git:** control de versiones.
- **GitHub:** almacenamiento y entrega del repositorio.

## 5. Diseño y sistema visual

El diseño de EcoMarket utiliza una identidad visual relacionada con la naturaleza y la sostenibilidad.

- **Verde principal:** `#22c55e`
- **Verde oscuro:** `#15803d`
- **Verde profundo:** `#052e16`
- **Fondo claro:** `#ffffff`
- **Fondo suave:** `#f0fdf4`

Se utilizan variables CSS definidas en `:root` para mantener la coherencia de los colores, las sombras, los bordes y las transiciones.

### Captura del diseño general

**Vista de escritorio**

![Espacio reservado para captura de escritorio](img/capturas/01-inicio-escritorio.png)

> Reemplazar este espacio por la captura real de la página principal en escritorio. Guardar la imagen en la ruta indicada o actualizar la ruta según la carpeta definitiva.

**Vista móvil**

![Espacio reservado para captura móvil](img/capturas/02-inicio-movil.png)

> Reemplazar este espacio por la captura real de la página principal vista desde un dispositivo móvil.

## 6. Páginas del sitio

### 6.1 Página principal — `index.html`

Presenta la identidad de EcoMarket, una sección principal de bienvenida, productos destacados y enlaces para navegar por el sitio.

**Captura de pantalla:**

![Espacio reservado para la página principal](img/capturas/03-pagina-principal.png)

### 6.2 Catálogo — `views/productos.html`

Presenta el catálogo de productos, organizado visualmente por categorías, con información sobre los productos y sus precios.

**Captura de pantalla:**

![Espacio reservado para el catálogo](img/capturas/04-catalogo-productos.png)

### 6.3 Sobre nosotros — `views/sobre-nosotros.html`

Expone la información de la empresa, su historia, sus principios y otros elementos visuales relacionados con la identidad del negocio.

**Captura de pantalla:**

![Espacio reservado para la página sobre nosotros](img/capturas/05-sobre-nosotros.png)

### 6.4 Contacto — `views/contacto.html`

Incluye los elementos visuales destinados a mostrar información de contacto y un formulario de consulta.

**Captura de pantalla:**

![Espacio reservado para la página de contacto](img/capturas/06-contacto.png)

## 7. Diseño responsive

El proyecto utiliza un enfoque Mobile First para adaptar la presentación del contenido a diferentes tamaños de pantalla.

Se emplean reglas CSS y media queries para organizar las secciones y las tarjetas de productos en dispositivos móviles, tabletas y computadores.

**Capturas de adaptación responsive:**

- **Móvil:** `img/capturas/07-responsive-movil.png`
- **Tableta:** `img/capturas/08-responsive-tableta.png`
- **Escritorio:** `img/capturas/09-responsive-escritorio.png`

![Espacio reservado para evidencia responsive](img/capturas/07-responsive-movil.png)

## 8. Recursos y características de CSS

Durante el desarrollo se aplican recursos de CSS3, entre ellos:

- Variables personalizadas mediante `:root`.
- Selectores de elementos, clases y atributos.
- Flexbox y CSS Grid para la distribución de contenido, según corresponda.
- Pseudoclases para estados e interacción visual.
- Pseudoelementos para detalles decorativos.
- Transiciones y animaciones CSS.
- Media queries para la adaptación a distintos dispositivos.
- Indicadores de enfoque para mejorar la navegación mediante teclado.

*Las características definitivas se confirmarán al revisar el código completo.*

## 9. Instalación y visualización local

Para visualizar el proyecto en un equipo local:

1. Descargar o clonar el repositorio.
2. Abrir la carpeta del proyecto en Visual Studio Code.
3. Abrir el archivo `index.html` en un navegador.
4. Navegar por las diferentes páginas mediante los enlaces del sitio.

No se requiere instalar frameworks ni dependencias de JavaScript.

## 10. Capturas adicionales

En esta sección se pueden agregar otras evidencias solicitadas por la actividad o por el docente.

| Evidencia | Ruta sugerida |
|---|---|
| Catálogo en móvil | `img/capturas/10-catalogo-movil.png` |
| Formulario de contacto | `img/capturas/11-formulario-contacto.png` |
| Efectos y animaciones | `img/capturas/12-efectos-css.png` |
| Estructura de carpetas | `img/capturas/13-estructura-proyecto.png` |

## 11. Repositorio y publicación

### Repositorio de GitHub

**Enlace:** [Pegar aquí el enlace del repositorio público de GitHub]

`https://github.com/USUARIO/NOMBRE-DEL-REPOSITORIO`

### Sitio web publicado

**Enlace:** [Agregar aquí la URL definitiva cuando se publique la página]

`PENDIENTE DE PUBLICACIÓN`

### Evidencia de publicación

![Espacio reservado para captura del sitio publicado](img/capturas/14-sitio-publicado.png)

> Agregar esta captura después de publicar el sitio y comprobar que las páginas y las imágenes carguen correctamente.

## 12. Limitaciones conocidas

EcoMarket se desarrolla utilizando HTML5 y CSS3, sin JavaScript ni frameworks. Por esta razón, las funcionalidades que requieren procesamiento dinámico o almacenamiento de información pueden ser únicamente visuales.

Las limitaciones definitivas se documentarán después de revisar y probar el proyecto completo.

## 13. Autoría

**Autor/a:** [Escribir nombre completo]  
**Proyecto:** EcoMarket  
**Tecnologías:** HTML5 y CSS3  
**Repositorio:** [Agregar enlace de GitHub]  
**Sitio publicado:** [Agregar enlace cuando esté disponible]
