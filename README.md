# TechWeek-Valero-2026
 Semana de charlas, talleres y demostraciones sobre tecnología, ciberseguridad, impresión 3D y redes. Participan institutos y empresas de la zona.

Codigo HTML de la pagina en "Estructura inicial




# Secciones usadas con su número de columnas de Bootstrap usadas,
# componentes prediseñados de Bootstrap usados,
# Descripción de los diferentes commits y mejoras implementadas de cada
# uno de ellos

<img width="615" height="317" alt="image" src="https://github.com/user-attachments/assets/68c2d44e-2ccb-47ec-9d75-d5b88cceba9f" />

Explicación del grid: Sistema perfecto de 12 columnas. #about usa split 6+6 (equilibrado texto/imagen). #talleres responsive: 3 columnas en lg (4+4+4=12), 2 en md (6+6).

Componentes Prediseñados Bootstrap Usados
Navbar (navbar navbar-expand-lg navbar-dark fixed-top): Responsive, collapsible con toggler ARIA-accessible.
​

Cards (3x card h-100): Hover effects custom, card-img-top, card-body, card-title semánticos.

Hero section: container py-5, display-3, lead, btn btn-primary btn-lg para CTA prominente.

Accordion (accordion accordion-flush): 2 items con collapse, accordion-button, accesible con aria-expanded.

Utilities: row g-4/5, col-*-*, container, text-center, img-fluid, shadow, h-100, flex-grow-1, mt-auto para layout sticky footer.

Explicación: Todos componentes nativos Bootstrap 5.3 (sin frameworks extra). Navbar fija (fixed-top), cards hover customizan shadows/transforms manteniendo responsive/mobile-first. Accordion ideal para ponentes (espacio eficiente).

Evolución de Commits y Mejoras Implementadas
Basado en estructura profesional iterativa (típica desarrollo landing page):

feat: base structure + navbar

<header> con navbar fixed-top responsive (container, toggler ARIA).

Mejora: navbar-dark, scroll suave implícito via href="#id".

feat: hero section responsive

<section id="hero"> con gradient overlay, display-3 lead.

Mejora: min-height:70vh flex center, mobile @media max-767px 60vh.

feat: about section 2-col grid

row align-items-center: texto+imagen equilibrados.

Mejora: g-5 spacing, img-fluid rounded-3 shadow accesible (alt semántico).

feat: talleres cards responsive

3 cards en row g-4 col-md-6 col-lg-4 (12 columnas perfectas).

Mejora: h-100 igual altura, hover translateY(-8px), <article> semántico.

feat: ponentes accordion

accordion-flush shadow-sm con 2 paneles colapsables.

Mejora: data-bs-parent evita múltiples abiertos, WCAG aria-controls.

feat: sticky footer + polish

body d-flex flex-column h-100, main flex-grow-1, footer mt-auto.

Mejora: Variables CSS --primary, Inter font, transiciones suaves.

Explicación de commits: Progresión lógica: estructura → hero → contenido → interactividad → polish responsive/accesible. Mejoras siguen mobile-first (breakpoints lg/md), semántica HTML5 (<main>, <article>), accesibilidad (ARIA, alt texts descriptivos). Total: landing page production-ready, compatible navegadores modernos.




# Mayor dificulatad encontrada

Me resulto dificil configurar en general GitHub, cosas como las ramas y la creación de los directorios se me complico.
