# TecniGuía Escolar

Sitio web informativo sobre las 6 técnicas que ofrece la **Institución Educativa Eustorgio Colmenares Baptista** (Cúcuta, Norte de Santander) en articulación con el SENA.

Trabajo elaborado para un grupo de estudiantes de **grado once** de la institución. La página está pensada para que los estudiantes de octavo y noveno conozcan cada técnica y elijan su camino académico con más claridad.

## Funcionalidades

- **Carrusel de fondos en el inicio**, con tiempos distintos por imagen (la foto del grupo de estudiantes dura más).
- **Tarjetas de las 6 técnicas** con imagen propia y animaciones: aparición al hacer scroll, imagen flotante, zoom y destello al pasar el mouse.
- **Identidad de color por técnica**: cada técnica tiene su paleta, aplicada en su tarjeta y en toda su página de detalle mediante variables CSS.
- **Páginas de detalle** organizadas en tarjetas (¿Qué es?, Perfil del estudiante, Competencias, Campo laboral y Proyección).
- **Diseño responsive** con menú hamburguesa para celular.
- **Accesibilidad**: respeta la preferencia del sistema de reducir movimiento (`prefers-reduced-motion`).

## Técnicas incluidas

| Técnica | Página |
| --- | --- |
| Desarrollo de Software | `desarrollo_software.html` |
| Asistencia Administrativa | `asistencia_administrativa.html` |
| Recursos Humanos | `recursos_humanos.html` |
| Contabilización de Operaciones | `contabilidad.html` |
| Sistemas Teleinformáticos | `sistemas.html` |
| Animación Turística | `animacion_turistica.html` |

## Tecnologías

- **HTML5** semántico
- **CSS3**: variables, Grid, Flexbox, `@keyframes`, animaciones ligadas al scroll (`animation-timeline`) y media queries
- **Google Fonts** (Poppins)

El sitio no usa JavaScript: todas las animaciones, el carrusel y el menú para celular están hechos solo con CSS, para que los estudiantes puedan entender y mantener el código con lo visto en clase.

## Estructura

```
├── index.html                  # Inicio: carrusel, institución, SENA, técnicas, orientación y contacto
├── *.html                      # Una página de detalle por técnica
├── styles.css                  # Todos los estilos del sitio
└── img/                        # Logos, fondos e imágenes de cada técnica
```

## Cómo verlo

No necesita instalación ni servidor. Clona el repositorio y abre `index.html` en el navegador:

```bash
git clone https://github.com/brandonn18/Tecniguia-Escolar.git
```

## Autor

Desarrollado por **Brandon Martínez** ([@brandonn18](https://github.com/brandonn18)).
