# Numidia Consulting

> Professional support for quality, food safety, environmental, and
> occupational health and safety management systems.

[![Live website](https://img.shields.io/badge/website-live-0066AE)](https://numidia-consulting.vercel.app/)
[![Built with HTML](https://img.shields.io/badge/built%20with-HTML5-E34F26)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Built with CSS](https://img.shields.io/badge/built%20with-CSS3-1572B6)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Built with JavaScript](https://img.shields.io/badge/built%20with-JavaScript-F7DF1E)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

Numidia Consulting is a responsive corporate website for an Algerian
consulting firm specializing in international management and quality
standards. It presents the firm's expertise, certifications, sectors of
intervention, field experience, client references, and contact information in
a clear, conversion-focused experience.

**Live website:** [numidia-consulting.vercel.app](https://numidia-consulting.vercel.app/)

## What the website presents

- **Company introduction:** communicates Numidia Consulting's mission,
  experience, and value proposition.
- **Certification expertise:** explains consulting support for ISO 9001,
  ISO 22000, ISO 14001, ISO 45001, HACCP, IFS, and BRC frameworks.
- **Four-step consulting journey:** presents the path from initial diagnosis
  through training, implementation, and certification.
- **Industry coverage:** highlights services for food and beverage, industry,
  construction, healthcare, and other service organizations.
- **Client references:** displays a visual collection of organizations that
  have worked with the firm.
- **Field experience gallery:** showcases consulting and audit activities on
  site.
- **Leadership profile:** introduces the firm's managing director and
  professional qualifications.
- **Contact actions:** provides direct contact options, email, address, and a
  link to the firm's Facebook page.

## Design and user experience

- Responsive layout for desktop, tablet, and mobile screens.
- Full-screen hero section with image slides and clear calls to action.
- Sticky navigation that adapts as the visitor scrolls.
- Mobile navigation menu for smaller screens.
- Animated client-logo marquee.
- Bento-style field-work gallery with a mobile-friendly horizontal layout.
- Consistent visual identity using Numidia Consulting's blue and gold palette.
- Smooth scrolling, hover states, transitions, and accessible link targets.

## Technology

- Semantic HTML5
- Modern CSS3 with responsive media queries
- Vanilla JavaScript
- Font Awesome icons
- Google Fonts: Inter and Space Grotesk
- Vercel for deployment

The website is intentionally lightweight and does not require a frontend
framework, package manager, or build step.

## Project structure

```text
Numidia_Consulting/
├── index.html              # Main website and page content
├── css/
│   └── style.css           # Theme, layout, responsive styles, animations
├── js/
│   └── main.js             # Navigation, hero slider, and interactions
└── assets/
    ├── logo.png            # Company branding
    ├── manager.jpg         # Leadership profile image
    ├── 1.jpg ... 10.jpg    # Field-work gallery
    └── marques/            # Client and partner logos
```

## Run locally

Because this is a static website, it can be opened directly in a browser.
For a more reliable local experience, serve the repository with a small HTTP
server:

```powershell
python -m http.server 8080
```

Open [http://localhost:8080](http://localhost:8080) in a browser.

Alternatively, use the **Live Server** extension in VS Code and open
`index.html`.

## Deployment

The site can be deployed to any static hosting provider. The current
production deployment uses Vercel:

1. Import the repository into Vercel.
2. Select the project root as the deployment directory.
3. Leave the build command empty.
4. Deploy the static files.

The same files can also be hosted with GitHub Pages, Netlify, or a
traditional web server.

## Business information

**Numidia Consulting**

20, Rue Akmoun Akli, Cité Berchiche
El-Kseur, Wilaya de Béjaïa, Algeria

- Phone: [+213 (0) 5 55 55 28 64](tel:+213555552864)
- Email: [consultingnumidia@gmail.com](mailto:consultingnumidia@gmail.com)
- Facebook: [Numidia Consulting Béjaïa](https://www.facebook.com/Numidia.consulting.Bejaia)

## License

This repository contains the website created for Numidia Consulting. Contact
the repository owner before reusing its branding, photographs, client logos,
or business content.