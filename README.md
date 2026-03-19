# Media Production Website

## Overview
This project is a professional media production website built using advanced HTML5 and CSS3 techniques. The website showcases services such as video production, audio recording, and photography. It includes four main pages: Home, About, Media, and Contact. The goal was to transform an incomplete starter codebase into a fully functional, responsive, and visually appealing website without using JavaScript.

---

## Issues Found
The starter code had several problems:
- Overuse of `<div>` instead of semantic HTML elements
- Missing metadata such as viewport and charset
- No Flexbox or CSS Grid layouts
- Missing media elements (audio, second video, iframe)
- Incomplete and inaccessible form (no labels, no validation)
- Images lacked `<figure>` and `<figcaption>`
- No animations, transitions, or transforms
- Limited CSS selectors and no pseudo-classes
- Poor responsiveness and layout structure
- Inconsistent code formatting and lack of comments

---

## Fixes and Implementations

### Semantic HTML & Metadata
- Replaced `<div>` elements with semantic tags (`header`, `nav`, `main`, `section`, `article`, `footer`, `figure`)
- Added proper metadata including `charset`, `viewport`, and `description`
- Ensured consistent structure across all pages

---

### Media Integration
- Added two video elements with controls and fallback content
- Implemented an audio player with controls
- Embedded a Google Maps iframe
- Updated images using `<figure>` and `<figcaption>` for better accessibility

---

### Advanced Forms & Validation
- Created a fully functional contact form with:
  - 7+ input types (text, email, tel, url, date, number, radio, checkbox, select)
  - Proper `<label>` elements for accessibility
  - Grouping using `<fieldset>` and `<legend>`
  - HTML5 validation (`required`, `pattern`, `min`, `max`, `minlength`, `maxlength`)

---

### Flexbox Layouts
- Implemented Flexbox for:
  - Navigation bar (horizontal responsive layout)
  - Services section (responsive cards layout)
  - Footer alignment
- Used properties such as `justify-content`, `align-items`, and `flex-wrap`

---

### CSS Grid Layout
- Created a responsive grid layout for:
  - Portfolio section (About page)
  - Testimonials section (Media page)
- Used `grid-template-columns`, `gap`, and `minmax()` with `auto-fit` for responsiveness

---

### Selectors & Pseudo-classes
- Expanded CSS selectors to include:
  - Element, class, ID, attribute, descendant, child, and sibling selectors
- Implemented pseudo-classes:
  - `:hover`, `:focus`, `:nth-child()`, `:first-child`, `:last-child`, `:not()`, `:valid`, `:invalid`

---

### Animations, Effects, and Transforms
- Added text effects such as `text-shadow` and gradient text
- Implemented transforms: `scale`, `translate`, and `rotate`
- Added transitions for smooth hover effects
- Created a keyframe animation (`fadeIn`) for page elements
- Included an optional loading animation

---

### Accessibility Improvements
- Added labels for all form inputs
- Used semantic HTML for better screen reader support
- Included `alt` attributes for all images
- Structured content logically for usability

---

### Cross-Browser Compatibility
- Tested website on Chrome and Firefox
- Ensured consistent layout and styling across browsers
- Fixed minor rendering differences using standard CSS practices

---

## How to View the Website
1. Download or clone the repository
2. Open the project folder
3. Open `index.html` in any modern web browser

---

## Limitations
- No backend functionality for form submission (HTML only)
- Minor visual differences may occur on older browsers

---

## Reflection
One of the main challenges was identifying and fixing all structural and styling issues in the incomplete code. Implementing Flexbox and Grid layouts required careful planning to ensure responsiveness. Adding advanced CSS features like animations and pseudo-classes improved user experience significantly. Debugging validation errors and improving accessibility also helped create a more professional and user-friendly website.

---