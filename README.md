# PixelCode

*El blog donde la cultura friki se vuelve mainstream*

---

## Sobre el proyecto

**PixelCode** nace como proyecto para la asignatura de **Entornos de Desarrollo**, pero rápidamente se convirtió en algo más que una práctica. Somos cuatro compañeros de clase que compartimos la misma obsesión: los **videojuegos**, los **cómics**, el **cine de ciencia ficción** y, en general, toda la cultura que durante años fue llamada "friki" y que hoy forma parte del día a día de millones de personas.

El sitio web reúne artículos, curiosidades, lore, noticias y próximos lanzamientos de algunas de las franquicias más queridas por la comunidad.

---

## Secciones del sitio

| Sección | Descripción | Archivo |
|---------|-------------|---------|
| **Blog principal** | Página de bienvenida con la presentación del proyecto y del equipo | `blog.html` |
| **Noticias** | Últimas novedades del mundo gamer y de la cultura friki | `Noticias/noticias.html` |
| **Eventos** | Calendario con los eventos más importantes del sector | `eventos.html` |
| **Próximos lanzamientos** | Lista de juegos y estrenos previstos por mes | `Proximos/proximos.html` |
| **Curiosidades de Pokémon** | Datos, historia y *easter eggs* de la franquicia | `Pokemon/pokemon.html` |
| **League of Legends** | Rivalidades, lore y secretos del juego | `LOL.html` |
| **Portal** | Enciclopedia dedicada al universo de Portal | `Portal_Tomi/portal/portal.html` |
| **JoJo's Bizarre Adventure** | Enciclopedia completa sobre la obra de Hirohiko Araki | `jojos1.html` |

---

## Estructura del proyecto

```
Proyecto-de-Entorno-main/
│
├── blog.html                  # Página principal del blog
├── estilos-blog.css           # Hoja de estilos principal
├── LOL.html                   # Sección de League of Legends
├── eventos.html               # Calendario de eventos
├── jojos1.html                # Enciclopedia de JoJo's
│
├── Noticias/
│   ├── noticias.html
│   └── estilos-noticias.css
│
├── Pokemon/
│   ├── pokemon.html
│   └── estilos-pokemon.css
│
├── Proximos/
│   ├── proximos.html
│   └── estilos-proximos.css
│
├── Portal_Tomi/
│   └── portal/
│       ├── portal.html
│       ├── style.css
│       └── (imágenes: GLaDOS, Chell, Cave Johnson…)
│
└── README.md
```

---

## Tecnologías utilizadas

- **HTML5** — Estructura semántica del contenido
- **CSS3** — Estilos, diseño responsive y maquetación
- **SVG** — Iconografía vectorial e ilustraciones (el logo *PixelCode* está hecho 100 % en SVG inline)
- **Google Fonts** — Tipografía personalizada en algunas secciones

La identidad visual del proyecto combina un fondo oscuro (`#1a1a2e`) con acentos en amarillo (`#ffcc33`), evocando una estética *pixel art* retro.

---

## Cómo ejecutarlo en local

No requiere instalación ni dependencias. Solo necesitas un navegador moderno.

```bash
# 1. Clona el repositorio
git clone https://github.com/<usuario>/Proyecto-de-Entorno.git

# 2. Entra en la carpeta del proyecto
cd Proyecto-de-Entorno

# 3. Abre la página principal en tu navegador
#    (haz doble clic sobre el archivo, o utiliza un servidor local)
open blog.html
```

### Alternativa con servidor local

Si prefieres servirlo con un servidor estático (recomendado para evitar problemas con rutas relativas):

```bash
# Con Python
python3 -m http.server 8000

# Con Node.js
npx serve .
```

Después abre [http://localhost:8000/blog.html](http://localhost:8000/blog.html) en tu navegador.

---

## Equipo

El proyecto está desarrollado por cuatro estudiantes, cada uno con su propia área de pasión:

| Integrante | Rol / Área |
|------------|------------|
| **Cristian Guillén Niño** | Coordinación del grupo · apasionado de los RPG |
| **Raúl Sánchez Andrade** | Defensor del retro · coleccionista de consolas clásicas |
| **Sergio Reyes Caravaca** | Cinéfilo del grupo · análisis de cine y ciencia ficción |
| **Tomás Bernal Montalbán** | Experto en cómics y manga |

---

## Estado del proyecto

**En desarrollo.** Se siguen añadiendo nuevas secciones, artículos y mejoras de estilo. Cualquier sugerencia es bienvenida.

---

## Contexto académico

Este proyecto forma parte de la asignatura **Entornos de Desarrollo** y tiene como objetivos:

- Aplicar conocimientos de HTML5 y CSS3 en un proyecto real
- Trabajar la **estructura semántica** de un sitio web multipágina
- Practicar el flujo de trabajo colaborativo con **Git** y **GitHub**
- Diseñar una identidad visual coherente entre todas las secciones

---

## Licencia

Proyecto desarrollado con fines **educativos**. Las marcas, personajes e imágenes referenciados (League of Legends, Pokémon, Portal, JoJo's Bizarre Adventure, etc.) son propiedad de sus respectivos dueños y se usan únicamente con fines divulgativos y sin ánimo de lucro.

---

© 2023–2026 PixelCode — *Cristian · Raúl · Sergio · Tomás*
