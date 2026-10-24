# Web Engineering Assignment — Viva & Explanation Guide

## Project objective
Build a modern, responsive 15-page e-commerce front end named Shopora using HTML and CSS.

## How to explain the project
**HTML:** HTML5 provides semantic structure. `<header>` contains branding/navigation, `<nav>` groups menu links, `<main>` holds page-specific content, `<section>` groups related content, `<article>` is used for product cards, `<form>` gathers demo input, and `<footer>` provides secondary navigation.

**CSS:** The shared stylesheet defines design tokens in `:root` (colors, radius, shadow). CSS Grid creates product/category grids and two-column layouts. Flexbox aligns navigation, buttons, and price rows. Hover transitions add feedback. Media queries at 980px, 760px, and 480px adapt layout to tablet and mobile screens.

**Navigation:** Each page links to other local `.html` files. The common header/footer keep the experience consistent.

**JavaScript:** The assignment is HTML/CSS-focused. The small optional `script.js` only opens the mobile menu, changes the product quantity field, and shows a demo message after a form submit. It does not connect to a backend.

## Likely viva questions
1. **What is HTML?** HTML is a markup language used to define the structure and meaning of web content.
2. **What is CSS?** CSS controls presentation such as colors, fonts, layout, spacing, and responsive behavior.
3. **What is responsive design?** A design approach that adapts the layout to different screen sizes using flexible layouts and media queries.
4. **What is the difference between Grid and Flexbox?** Grid is useful for two-dimensional rows and columns; Flexbox is useful for arranging items along one axis.
5. **Why use an external CSS file?** It centralizes styles, reduces duplication, and keeps all pages visually consistent.
6. **What is semantic HTML?** Elements such as `header`, `nav`, `main`, and `footer` describe the role of content and improve structure/accessibility.
7. **Does this project process real orders?** No. It is a front-end prototype. Real orders require backend logic, database storage, validation, and a secure payment provider.
8. **How does mobile navigation work?** CSS hides the menu at small widths; a small JavaScript event toggles the `open` class.
9. **How can accessibility be improved?** Keep labels for form fields, use descriptive link text, ensure keyboard access, maintain color contrast, and add meaningful alt text to real images.
10. **How would you add a database?** Build a backend/API, store products and orders in a database, validate data on the server, and connect checkout to a secure payment service.

## Before submitting
- Replace student/course details in a cover page if your teacher requires them.
- Test all navigation links.
- Open the site on a mobile screen.
- Be ready to explain which files contain HTML, CSS, and the optional JavaScript.
- Confirm whether your instructor permits JavaScript; if not, the HTML/CSS pages still display, but the mobile menu toggle and demo feedback will not work.
