# TriasWear Bootstrap Landing Page

## Project Overview

This project is a responsive single-page website for TriasWear, a real streetwear brand that I am helping build.

I chose **Option B — Recraft the Structure** for this assignment. I kept the required Bootstrap structure and responsive layout, but changed the content, colors, products, and branding to match TriasWear.

## About TriasWear

TriasWear is a real clothing brand built by a small team. We work on the designs, product development, website, content, marketing, and business decisions ourselves.

Instead of creating a fictional company for this project, I used the real TriasWear brand and products.

## Website Features

- Responsive Bootstrap navigation bar
- Mobile hamburger menu using Bootstrap collapse
- Intro section with a headline, supporting text, and call-to-action button
- Three-product responsive grid
- Individual Bootstrap carousels for product images
- Front, back, and additional product photos
- Three-item business highlights section
- About section
- Quality section
- Brand process section
- Call-to-action section
- Responsive footer

## Bootstrap

This project uses Bootstrap 5.3.8 through the official Bootstrap CDN.

Bootstrap is used for:

- Responsive grid layouts
- Navbar and mobile collapse
- Buttons
- Carousels
- Spacing utilities
- Typography utilities
- Flexbox utilities
- Responsive column classes

## Custom CSS

Custom styles are located in:

`css/custom.css`

The custom stylesheet extends Bootstrap and gives the website its TriasWear visual style.

Some Bootstrap elements that were customized include:

- Navbar colors and spacing
- Primary buttons
- Carousel controls
- Product cards
- Responsive typography and spacing

The CSS was written mobile-first and uses responsive breakpoints for tablet and desktop layouts.

## Responsive Testing

The website was tested at approximately:

- 375px mobile width
- 768px tablet width
- 1200px desktop width

The layout stacks correctly on smaller screens and expands into multiple columns on larger screens.

The navbar, product carousels, buttons, and links were also tested at different screen sizes.

## Accessibility

The website includes:

- Descriptive alt text for product images
- An accessible navbar toggle label
- Logical heading order
- Keyboard-accessible links and buttons
- High-contrast text and backgrounds
- Hidden accessibility text for carousel controls

## Validation

The HTML was validated using the W3C Markup Validation Service.

The custom CSS was validated using the W3C CSS Validation Service.

Screenshots of the successful validation results are included in the `docs` folder:

- `docs/html-validation.png`
- `docs/css-validation.png`

## Image Credits

All TriasWear product images used on this website are original TriasWear product images.

## Known Issues

No known issues at this time.

## Project Structure

```text
project-folder/
├── index.html
├── css/
│   └── custom.css
├── images/
│   ├── samurai/
│   ├── trias-bold/
│   └── utah/
├── docs/
│   ├── html-validation.png
│   └── css-validation.png
└── README.md