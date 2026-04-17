#pv_tp1_grupo4
-Quispe Pablo Arturo - PabloArt2303
-Miranda Martinez Francisco Ariel - Fran-Mir21

index.html
Corresponde a la página principal de la plataforma de gestión de proyectos educativos. Presenta un encabezado con navegación hacia las distintas secciones del sitio y un panel central organizado en bloques. Incluye una sección de estadísticas que resume información relevante (como cantidad de proyectos, tareas y mensajes), junto con apartados de tareas, mensajes y novedades que reflejan la actividad reciente del sistema. Su función es ofrecer una visión general y facilitar el acceso al resto de las páginas.

proyectos.html
Contiene el listado de proyectos disponibles en la plataforma. Incorpora una barra de filtros (no funcional en esta versión estática) y una visualización de proyectos mediante bloques que incluyen título, imagen, descripción, categoría y acceso a su vista detallada.

detalle.html
Representa la vista individual de un proyecto. Incluye información específica como título, fecha de inicio, autores y una descripción extendida. Además, presenta una lista de recursos asociados y una sección que identifica a los integrantes del equipo junto con sus respectivos roles.

perfil.html
Muestra la información del desarrollador o de los integrantes del proyecto. Incluye datos personales relevantes y puede incorporar una imagen de perfil, organizando la información de manera clara mediante el uso de estructuras semánticas.

styles.css
Se implementó una hoja de estilos externa (styles.css) vinculada a todas las páginas del sitio, con el objetivo de mantener una apariencia visual consistente y facilitar la gestión del diseño.

Se utilizaron variables CSS (:root) para definir colores y tipografías, permitiendo una estandarización estética en toda la plataforma. Asimismo, se aplicó un reset básico para eliminar estilos predeterminados del navegador y lograr mayor control sobre el diseño.

La estructura general del sitio fue organizada mediante CSS Grid, distribuyendo los elementos principales como encabezado, navegación y contenido. Para la disposición de componentes internos, como la barra de navegación y las tarjetas de proyectos, se utilizó Flexbox, facilitando la alineación y adaptación de los elementos en pantalla.

Se diseñaron estilos específicos para secciones como estadísticas, proyectos, detalle y perfil, empleando clases CSS para una mejor reutilización y organización del código. En particular, se implementó un diseño tipo “card” para los proyectos y perfiles, mejorando la presentación visual de la información.

Además, se incorporaron estados de interactividad mediante pseudo-clases como :hover, :active y :focus, brindando una mejor experiencia de usuario al interactuar con enlaces y elementos del sitio.

Finalmente, se añadieron estilos para el pie de página (footer) y se organizaron los contenidos mediante el uso de espaciados, bordes redondeados y alineaciones, logrando un diseño limpio, moderno y coherente con los objetivos del sistema.