# Restaurant To Go

Restaurant To Go es una página web, replicada y diseñada como proyecto del Módulo 1 del Bootcamp Her-Tech Javascript. Representa un espacio web para un restaurante de comida rápida con servicio de entrega a domicilio.

## Secciones principales:

- Hero con eslogan e imagen destacada
- Estadísticas del restaurante (impacto)
- Sección "About Us"
- Sección "Our Mission"
- Formulario de contacto
- Suscripción a ofertas
- Footer con enlaces e información de contacto

## Tecnologías Utilizadas:

- HTML:
  Estructura general por secciones:
  header: incluye la barra superior con logo, menú y contacto (icono de búsqueda y teléfono)

  main: agrupa el contenido principal de la web dividido en distintas secciones:
  hero-section: sección destacada con eslogan y una imagen principal
  impact-section: estadísticas de impacto del restaurante en cifras
  about-section: información general sobre el restaurante, incluyendo título, texto e imagen
  mission-section: explicación de la misión del restaurante con contenido estructurado en título, texto e imagen
  contact-section: formulario de contacto con campos para nombre, correo y mensaje
  subscribe-section: formulario de suscripción para seguir las ofertas

  footer: ocupa la información de contacto, logo, enlaces y aviso de derechos de autor

- CSS:
  Selectores utilizados:

  - Universales: \* para definir la fuente base del proyecto.
  - De etiqueta: footer, form, textarea, para aplicar estilos generales según el tipo de elemento
  - De clase: .topbar, .hero-text, .link, etc., para agrupar estilos semánticos
  - Combinados: .topnav a, .footer-links ul li a para aplicar estilos a elementos dentro de clases específicas
  - Agrupados: .about-text, .mission-text, .contact-text para evitar duplicación de reglas

    Pseudoclases y pseudoelementos:

  - :hover en enlaces (.link:hover, .topnav a:hover, .footer-links ul li a:hover) para efectos interactivos
  - ::before en .icon-text::before para añadir decoraciones visuales (círculos amarillos)

    Flexbox:
    Se emplea display: flex en estructuras como:

  - .topbar para el encabezado
  - .hero-content, .about-content, .mission-content, .contact-content, .footer-content para distribuir el contenido
  - Uso de propiedades como justify-content, align-items, gap, flex-wrap y flex: 1 para gestionar distribución y adaptación

- Google Fonts (Poppins)

- SVG Icons

- Visual Studio Code
