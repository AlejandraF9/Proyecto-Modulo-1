# Restaurant To Go

Restaurant To Go is a website, replicated and designed as a project of Module 1 of the Her-Tech Javascript Bootcamp. It represents a web space for a fast food restaurant with home delivery service.

## Main sections:

- Hero with slogan and featured image
- Restaurant statistics (impact)
- About Us’ section
- Our Mission’ section
- Contact form
- Subscription to offers
- Footer with links and contact information

## Technologies Used:

- HTML:
  General structure by sections:

  - header: includes the top bar with logo, menu and contact (search icon and telephone)

  - main: groups the main content of the website divided into different sections:
    hero-section: featured section with slogan and a main image
    impact-section: statistics of the restaurant's impact in figures
    about-section: general information about the restaurant, including title, text and image
    mission-section: explanation of the restaurant's mission with structured content in title, text and image
    contact-section: contact form with name, email and message fields
    subscribe-section: subscription form to follow up the offers

  - footer: holds contact information, logo, links and copyright notice

- CSS:
  Selectors used:

  - Universal: \* to define the base source of the project.
  - Tag: footer, form, textarea, to apply general styles according to the type of element.
  - Class: .topbar, .hero-text, .link, etc., to group semantic styles.
  - Combined: .topnav a, .footer-links ul li a to apply styles to elements within specific classes
  - Grouped: .about-text, .mission-text, .contact-text to avoid duplication of rules

    Pseudo-classes and pseudo-elements:

  - :hover on links (.link:hover, .topnav a:hover, .footer-links ul li a:hover) for interactive effects
  - ::before in .icon-text::before to add visual decorations (yellow circles)

    Flexbox:
    Display: flex is used in structures such as:

  - .topbar for the header
  - .hero-content, .about-content, .mission-content, .contact-content, .footer-content to distribute content
  - Use of properties such as justify-content, align-items, gap, flex-wrap and flex: 1 to manage layout and adaptation

- Google Fonts (Poppins)

- SVG Icons

- Visual Studio Code
