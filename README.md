# TechWeek-Valero-2026
 Semana de charlas, talleres y demostraciones sobre tecnología, ciberseguridad, impresión 3D y redes. Participan institutos y empresas de la zona.

Codigo HTML de la pagina en "Estructura inicial


## 🛠️ Tecnologías y Sistema de Rejilla (Grid)

El proyecto está maquetado principalmente con **Bootstrap 5.3** y CSS personalizado para adaptar los colores corporativos (azul San Valero) y la tipografía (Google Fonts: *Inter*). 

Para estructurar el contenido, he utilizado el sistema de columnas de Bootstrap en las siguientes secciones:

* **Sección "Sobre el evento" (`#about`):** * Utiliza una fila (`.row`) dividida en dos bloques simétricos en pantallas grandes mediante la clase **`col-lg-6`**. Una columna contiene el texto explicativo y la otra la imagen representativa.
* **Sección "Talleres Destacados" (`#talleres`):** * Utiliza una cuadrícula que se adapta al dispositivo. He usado **`col-md-6 col-lg-4`** para cada tarjeta. Esto hace que en móviles se vea una columna (100%), en tablets se divida en dos columnas (50%), y en escritorio se muestren tres columnas perfectas (33.3%).

---

## 🧩 Componentes de Bootstrap Utilizados

Para acelerar el desarrollo y mantener una interfaz coherente, he integrado los siguientes componentes prediseñados de Bootstrap:

* **Navbar (`.navbar`):** Barra de navegación fijada en la parte superior (`fixed-top`) con menú hamburguesa que colapsa en dispositivos móviles (`navbar-toggler`).
* **Cards (`.card`):** Utilizadas en la sección de talleres para encapsular la imagen (`card-img-top`), el título (`card-title`) y la descripción del taller de forma visualmente limpia.
* **Accordion (`.accordion-flush`):** Implementado en la sección de ponentes (`#ponentes`) para ahorrar espacio en pantalla. Permite desplegar y ocultar la información de cada experto al hacer clic.
* **Buttons (`.btn .btn-primary`):** Botón de llamada a la acción (CTA) en la sección principal (*Hero*) para invitar al usuario a descubrir más sobre el evento.

---

## 📝 Historial de Commits y Mejoras Implementadas

A continuación, se detalla la evolución del proyecto a través de sus *commits* principales:

1.  **`init: estructura básica y configuración del entorno`**
    * *Mejora:* Creación del archivo `index.html`, configuración del `<head>` (metadatos, título) y enlace a las librerías externas (Bootstrap por CDN y tipografía Inter de Google Fonts).
2.  **`feat: añade cabecera Navbar y Hero section`**
    * *Mejora:* Implementación del menú de navegación *responsive* y maquetación de la primera vista (Hero) con imagen de fondo oscurecida, titular principal y botón de anclaje.
3.  **`feat: implementa grid de Bootstrap para sección About y Talleres`**
    * *Mejora:* Construcción de la estructura de filas y columnas. Inserción del componente *Card* para los tres talleres principales, asegurando que se adapten correctamente a diferentes tamaños de pantalla.
4.  **`feat: integra Acordeón para ponentes y Footer`**
    * *Mejora:* Añadida la lista de ponentes usando paneles colapsables (*Accordion*) para mejorar la experiencia de usuario. Creación del pie de página con información de copyright y contacto.
5.  **`style: personalización CSS, colores corporativos y animaciones`**
    * *Mejora:* Sobrescritura de estilos de Bootstrap mediante CSS puro (variables `:root`). Añadidos efectos de transición suaves (*hover*) en los enlaces, botones y una animación de elevación en las tarjetas de los talleres.




# Mayor dificulatad encontrada

Me resultó complejo configurar GitHub en general. Aspectos como la gestión de ramas y la creación de directorios me presentaron ciertas dificultades.
Además, tuve algunos inconvenientes al intentar descargar GitHub Desktop, ya que en un primer intento instalé el programa equivocado.
