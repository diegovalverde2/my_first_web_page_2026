# Diego Valverde · Página web personal

Proyecto individual de la asignatura **Fundamentos de Ingeniería Informática** (FII), realizado durante el primer curso del Grado en Ingeniería Informática de la Universidad Francisco de Vitoria (curso 2025/2026).

🔗 **Sitio web:** https://diegovalverde2.github.io/my_first_web_page_2026/
📁 **Repositorio:** https://github.com/diegovalverde2/my_first_web_page_2026

Este `README.md` también sirve como Documento Detallado de Diseño (DDD) del proyecto.

---

# 1. Objetivo

El objetivo de este proyecto ha sido crear y publicar una página web personal utilizando únicamente **HTML5** y **CSS3**. En ella presento quién soy, qué estoy estudiando, uno de mis hobbies (el motocross) y una página con los enlaces a los sitios web de mis compañeros.

Además, este trabajo también me ha servido para aprender a utilizar **Git** y **GitHub**, organizando el desarrollo mediante commits a medida que iba completando cada parte de la página.

# 2. Desarrollo

## 2.1 Estructura del proyecto

```text
my_first_web_page_2026/
├── index.html
├── README.md
├── LICENSE
├── .gitignore
├── css/
│   └── style.css
├── documents/
│   └── cv-diego-valverde.pdf
├── images/
│   ├── seal.svg
│   ├── foto mia.jpeg
│   ├── foto con la moto.jpeg
│   ├── foto motocross 1.jpeg
│   ├── foto motocross 2.jpeg
│   └── equipacion motocross.jpeg
└── public/
    ├── about.html
    ├── topic.html
    ├── degree.html
    ├── fii.html
    ├── net.html
    └── contact.html
```

He seguido la estructura propuesta en la práctica: la página principal está en la raíz del proyecto, el resto de páginas HTML se encuentran en `public/`, los estilos en `css/` y las imágenes en `images/`.

## 2.2 Diseño

Quería que la web tuviera un aspecto relacionado con la informática, pero sin usar el típico fondo negro con texto verde.

Las principales decisiones fueron:

* Utilizar un granate inspirado en los colores de la UFV como color principal, combinado con un verde azulado para algunos detalles.
* Emplear tres tipografías diferentes: una para los títulos, otra para el texto y una monoespaciada para elementos como el menú o el bloque de "terminal" de la portada.
* Mostrar el menú como si fueran archivos HTML (`about.html`, `topic.html`, etc.), ya que toda la web está formada por páginas independientes.
* Diseñar un logotipo propio en formato SVG inspirado en un sello académico y una placa de circuito.

## 2.3 Imágenes

Todas las imágenes están guardadas en la carpeta `images/` e incluyen fotografías personales y relacionadas con el motocross.

El currículum se encuentra en `documents/cv-diego-valverde.pdf` y puede descargarse desde la página **About**.

## 2.4 Control de versiones

He intentado que el historial de commits refleje el proceso de desarrollo del proyecto. Primero preparé la estructura y la portada y, después, fui añadiendo cada página mediante un commit independiente.

# 3. Resultado final

El resultado es una página web compuesta por siete archivos HTML (la portada y seis páginas adicionales), una única hoja de estilos compartida y un diseño adaptable a distintos tamaños de pantalla. No utiliza JavaScript, únicamente HTML y CSS.

# 4. Problemas encontrados

Durante el desarrollo aparecieron varios problemas:

* **Rutas relativas:** al crear las páginas dentro de `public/`, el CSS y las imágenes dejaron de cargarse porque las rutas ya no eran las mismas que en `index.html`. Tuve que entender cómo funcionan las rutas relativas y utilizar `../` cuando era necesario.
* **Uso de Git:** al principio hacía muchos cambios sin comprobar el estado del repositorio y terminaba mezclando modificaciones distintas en un mismo commit. Después empecé a organizar mejor el trabajo haciendo un commit por cada cambio importante.
* **Diseño responsive:** en la página "Sobre mí" la cuadrícula con las imágenes y el texto no se veía bien en pantallas pequeñas. Lo solucioné utilizando una media query para colocar los elementos uno debajo del otro.
* **Tabla demasiado ancha:** la tabla de asignaturas ocupaba más espacio que la pantalla del móvil. Reduje el tamaño de la letra y simplifiqué su diseño para mejorar la visualización.

# 5. Conclusiones

Este proyecto me ha ayudado a perder el miedo a trabajar con archivos HTML, CSS y con Git desde la terminal. También me ha servido para entender la importancia de mantener el proyecto organizado separando el contenido, el diseño y los distintos archivos en carpetas. Aunque la página es sencilla, seguir esa organización hace que sea mucho más fácil de mantener.

# 6. Colaboradores

* **Autor:** Diego Valverde (@diegovalverde2)
* **Colaborador añadido según la normativa:** @hectormolgar

# 7. Licencia

Este proyecto se distribuye bajo licencia MIT. Consulta el archivo `LICENSE` para más información.
