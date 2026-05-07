[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/uFImwIHI)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=23177343&assignment_repo_type=AssignmentRepo)
# Media Production Website Starter Code

This is the starter codebase for your media production website project. The code is approximately 70% complete but contains errors, omissions, and areas that need significant improvement.

## What's Included

- `index.html` - Home page (incomplete, semantic issues)
- `about.html` - About/Services page (incomplete, missing flexbox/grid layouts)
- `media.html` - Media gallery page (incomplete, missing media elements)
- `contact.html` - Contact page (incomplete form with validation issues)
- `css/styles.css` - Stylesheet (incomplete, missing advanced features)
- `images/` folder - Placeholder folder for your images
- `media/` folder - Placeholder folder for video/audio files

## Your Task

Review the provided code carefully and:
1. Identify and fix all HTML and CSS errors
2. Complete all missing advanced requirements
3. Add required media elements (video, audio, iframe)
4. Implement flexbox and CSS Grid layouts
5. Add CSS effects, transforms, transitions, and animations
6. Expand selector usage and add pseudo-classes
7. Improve code quality and organisation
8. Test across multiple browsers and validate all code

## Getting Started

1. Review all HTML and CSS files thoroughly
2. Run HTML through W3C Validator to identify errors
3. Run CSS through W3C CSS Validator
4. Identify missing advanced features (flexbox, grid, animations, etc.)
5. Test in multiple browsers
6. Fix all issues and complete missing requirements

## Notes

- You will need to add your own video and audio files to the `media/` folder
- You will need to add images to the `images/` folder
- The starter code intentionally has issues for you to discover and fix
- Advanced features like flexbox, grid, animations are missing or incomplete
- Refer to the project requirements document for all specifications

Good luck!
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
- No backend functionality for form submission
- Minor visual differences may occur on older browsers

---

## Reflection
One of the main challenges was identifying and fixing all structural and styling issues in the incomplete code. Implementing Flexbox and Grid layouts required careful planning to ensure responsiveness. Adding advanced CSS features like animations and pseudo-classes improved user experience significantly. Debugging validation errors and improving accessibility also helped create a more professional and user-friendly website.

---
