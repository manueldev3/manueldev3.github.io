# ManuelDeveloper.com

Portafolio personal de Manuel, ingeniero de software especializado en el desarrollo web y multiplataforma, la creación de interfaces dinámicas y la construcción de soluciones escalables.

El sitio está construido como una página única estática y presenta la experiencia profesional, las habilidades, los proyectos y los canales de contacto de Manuel.

## Contenido

- **Inicio:** presentación, especialidades y enlaces a LinkedIn, GitHub y WhatsApp.
- **Habilidades:** automatización con IA, desarrollo de aplicaciones, desarrollo web, diseño UI/UX, backend y DevOps.
- **Portafolio:** proyecto de comercio para Star Citizen desarrollado con Next.js y Firebase.
- **CV:** experiencia, habilidades profesionales y formación académica.
- **Contacto:** acceso directo a WhatsApp.

## Tecnologías

- HTML5, CSS3 y JavaScript.
- Bootstrap 5 para la estructura responsive y los componentes visuales.
- jQuery para interacciones y navegación.
- Feather Icons para la iconografía.
- AOS y WOW.js para animaciones al desplazarse.
- Slick para carruseles.
- SCSS como fuente organizada de los estilos del proyecto.

Las dependencias están incluidas localmente en `assets/`; no se requiere Node.js ni un proceso de instalación para visualizar el sitio.

## Ejecutar localmente

Puedes abrir `index.html` directamente en el navegador. Para evitar restricciones del navegador con recursos locales y obtener una experiencia más parecida a producción, utiliza un servidor HTTP local:

```bash
python3 -m http.server 8000
```

Después visita [http://localhost:8000](http://localhost:8000).

También puedes servir la carpeta con cualquier servidor estático, como Live Server, Apache o Nginx.

## Estructura principal

```text
.
├── index.html             # Página principal del portafolio
└── assets/
	├── css/               # Estilos compilados y plugins CSS
	├── fonts/             # Tipografías locales
	├── images/            # Logos, banners, iconos y proyectos
	├── js/                # Código del sitio y librerías JavaScript
	├── maps/              # Recursos de mapas
	└── scss/              # Fuentes SCSS organizadas por módulos
```

## Personalización

1. Edita el contenido, enlaces y secciones en `index.html`.
2. Modifica los estilos compilados en `assets/css/style.css` para cambios rápidos.
3. Para cambios estructurales de estilos, actualiza los archivos de `assets/scss/` y recompila el SCSS hacia `assets/css/style.css`.
4. Sustituye imágenes y logotipos dentro de `assets/images/`, conservando las rutas utilizadas por el HTML.

## Notas de mantenimiento

- El enlace de navegación de **Clientes** apunta actualmente a `http://localhost:3000/#clients`; debe actualizarse si esa sección se publica en otra URL.
- El código JavaScript incluye una integración genérica con `mail.php` para formularios, pero ese endpoint no está incluido en este repositorio.
- El título y algunos textos heredados de la plantilla original todavía pueden personalizarse en `index.html`.

## Autor

**Manuel**

- GitHub: [@manueldev3](https://github.com/manueldev3)
- LinkedIn: [manueldev3](https://linkedin.com/in/manueldev3)
- WhatsApp: [Contactar](https://wa.me/573024833281)