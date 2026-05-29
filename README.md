# Bakers Delight - Website Project

## Project Description
For my website development module, I have built a multi-page site for a bakery called Bakers Delight. I wanted to create a professional look where customers can easily find our bread prices and get in touch with us through an enquiry form.

## Student Details
- **Name:** Kopano Kearabetsoe Maboi
- **Student Number:** ST10522631

## Project Overview
This project involved developing a responsive, multi-page website for a local bakery. The primary goal was to implement a clean, user-friendly interface that adapts to various screen sizes while maintaining consistent branding throughout all pages.

## Technical Features
- **Semantic HTML:** Used tags like `header`, `nav`, `main`, and `footer` to organize the code properly.
- **External CSS Stylesheet:** A single `style.css` file linked to all pages for consistent styling.
- **Typography:** Applied font-family, font-size, font-weight, line-height, and letter-spacing throughout.
- **Flexbox Layout:** Used Flexbox for the navigation bar and overall page layout structure.
- **Responsive Design:** Media queries implemented for desktop, tablet (1024px), mobile (768px), and small mobile (480px).
- **Tables:** Used on the Services page to display the bakery products and prices.
- **Forms:** Created an Enquiry page so customers can send us messages.
- **Pseudo-Classes:** Applied `:hover`, `:focus`, and `:active` states on navigation links, images, form inputs, and buttons.
- **Media:** All bakery images are organized in a dedicated `images/` folder.

## File Structure
```
Bakers Delight-Final Project/
├── css/
│   └── style.css
├── images/
│   ├── images-logo.jpg
│   ├── bakery-shop.jpg
│   ├── bakery-z.jpg
│   ├── a.jpg
│   └── image-b.webp
├── index.html
├── about.html
├── services.html
├── contact.html
├── enquiry.html
└── README.md
```

## How to View
1. Clone this repository to your local machine.
2. Open `index.html` in any modern web browser to view the home page.
3. Use the browser's "Inspect" (F12) tool to test different mobile device dimensions.

## Technologies Used
- HTML5
- CSS3 (Flexbox for layout and responsive design)

---

## Changelog

### Part 2 Changes (CSS Styling & Responsive Design)

- **External Stylesheet Created:** Created a single external `style.css` file and linked it to all five HTML pages using the `<link>` tag in each page's `<head>` section.
- **CSS Reset Added:** Added a universal `* { margin: 0; padding: 0; box-sizing: border-box; }` reset to ensure consistent styling across all browsers.
- **Base Styles Applied:** Set default `font-family`, `font-size`, `line-height`, `color`, and `background-color` on the `body` element to establish a cohesive warm bakery aesthetic.
- **Typography Styles:** Styled all heading levels (h1, h2, h3) with appropriate font sizes, weights, and letter-spacing. Paragraph line-height set to 1.8 for readability.
- **Layout Structure:** Used Flexbox on the `header` and `nav` elements to create a structured, aligned layout. Set `max-width` and `margin: auto` on `main` to centre content on larger screens.
- **Colour Scheme & Decoration:** Applied a consistent warm colour palette (coral pink `#e8a598`, warm beige `#f5ebe0`, deep brown `#4a3728`) across header, footer, and content areas. Added `box-shadow` and `border-radius` to images and tables.
- **Pseudo-Classes Implemented:** Added `:hover`, `:focus`, and `:active` states to navigation links, images, form inputs, submit button, and table rows for interactivity.
- **Responsive Design — Tablet (1024px):** Header stacks vertically, navigation gap reduced, table width set to 100%.
- **Responsive Design — Mobile (768px):** Navigation menu stacks vertically with full-width links, font sizes reduced, images set to 100% width, form padding adjusted.
- **Responsive Design — Small Mobile (480px):** Further font size reduction, tighter padding on header and main content area.
- **Services Table Styled:** Added `thead` background colour, row hover effect, cell padding, and `box-shadow` to the product table.
- **Form Styled:** Applied consistent padding, border, border-radius, and focus states to all form inputs, selects, and textarea elements.
- **Footer Styled:** Applied deep brown background with beige text, centred alignment, and margin-top spacing.

### Part 1 Corrections (Based on Feedback)
- **Fixed broken viewport meta tag** on `about.html` — changed `width=,` to `width=device-width`.
- **Fixed duplicate tags** on `services.html` — removed extra `</main>` and duplicate `<footer>` tags.
- **Removed inline styles** from `index.html` — moved logo image and span styling to the external stylesheet.
- **Fixed title typo** on `contact.html` — corrected "DElight" to "Delight".

---

#### Responsive Design Screenshots

> Screenshots taken using browser DevTools (F12) to simulate different screen sizes.

### Desktop View
![Desktop View](images/Screenshot%202026-05-28%20123241.png)

### Tablet View
![Tablet View](images/Screenshot%202026-05-28%20124221.png)

### Mobile View
![Mobile View](images/Screenshot%202026-05-28%20124419.png)

---




## References

- MDN Web Docs. (2024). *CSS: Cascading Style Sheets*. Mozilla. https://developer.mozilla.org/en-US/docs/Web/CSS
- MDN Web Docs. (2024). *Using media queries*. Mozilla. https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_media_queries/Using_media_queries
- MDN Web Docs. (2024). *Flexbox*. Mozilla. https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox
- W3Schools. (2024). *CSS Tutorial*. https://www.w3schools.com/css/
- W3Schools. (2024). *Responsive Web Design*. https://www.w3schools.com/css/css_rwd_intro.asp
- Google Fonts. (2024). *Segoe UI font reference*. https://fonts.google.com
- The Independent Institute of Education. (2026). *WEDE5020 Module Guide*. IIE.
