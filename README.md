# Media Production Website

## Overview

This project is a professional media production website built using advanced HTML5 and CSS3 techniques. The website showcases services such as video production, audio recording, and photography. It includes four main pages: Home, About, Media, and Contact. The goal was to transform an incomplete starter codebase into a fully functional, responsive, and visually appealing website without using JavaScript.

---

## What's Included

* `index.html` - Home page
* `about.html` - About/Services page
* `media.html` - Media gallery page
* `contact.html` - Contact page
* `css/styles.css` - Main stylesheet
* `images/` folder - Website images and gallery assets
* `media/` folder - Video and audio files
* `screenshots/` folder - Evidence of functionality, responsiveness, and browser testing
* `design/` folder - Wireframe and issues identification documents
* `README.md` - Project documentation

---

## Issues Found

The starter code had several problems:

* Overuse of `<div>` instead of semantic HTML elements
* Missing metadata such as viewport and charset
* No Flexbox or CSS Grid layouts
* Missing media elements (audio, second video, iframe)
* Incomplete and inaccessible form (no labels, no validation)
* Images lacked `<figure>` and `<figcaption>`
* No animations, transitions, or transforms
* Limited CSS selectors and no pseudo-classes
* Poor responsiveness and layout structure
* Inconsistent code formatting and lack of comments

---

## Fixes and Implementations

### Semantic HTML & Metadata

* Replaced generic `<div>` elements with semantic tags such as:

  * `<header>`
  * `<nav>`
  * `<main>`
  * `<section>`
  * `<article>`
  * `<footer>`
  * `<figure>`
  * `<figcaption>`
* Added metadata including:

  * UTF-8 charset
  * Responsive viewport settings
  * Meta description
* Ensured a consistent semantic structure across all pages.

---

### Media Integration

* Added two video elements with controls and fallback content.
* Added an audio player with controls and fallback support.
* Embedded a Google Maps iframe for location information.
* Updated image sections using `<figure>` and `<figcaption>` to improve accessibility and semantics.

---

### Advanced Forms & Validation

The contact page was redesigned to include:

* Labels for all form inputs
* Fieldsets and legends for logical grouping
* Multiple HTML5 input types:

  * Text
  * Email
  * Telephone
  * URL
  * Date
  * Number
  * Select dropdown
  * Radio buttons
  * Checkboxes
* Validation attributes:

  * required
  * pattern
  * minlength
  * maxlength
  * min
  * max

These improvements increased accessibility and ensured proper form validation without JavaScript.

---

### Flexbox Layouts

Flexbox was implemented in multiple areas:

#### Navigation Bar

* Horizontal responsive layout
* Proper alignment using:

  * justify-content
  * align-items

#### Services Section

* Responsive service cards
* Flex wrapping for smaller screens

#### Footer Layout

* Improved spacing and alignment

---

### CSS Grid Layout

CSS Grid was used to create responsive layouts including:

#### Portfolio Gallery

* Responsive image gallery
* Uses:

  * grid-template-columns
  * gap
  * minmax()
  * auto-fit

#### Testimonials Section

* Structured and responsive content layout

---

### Selectors & Pseudo-classes

The stylesheet was expanded to include multiple selector types:

#### Selector Types

* Element selectors
* Class selectors
* ID selectors
* Attribute selectors
* Descendant selectors
* Child selectors
* Adjacent sibling selectors

#### Pseudo-classes

* :hover
* :focus
* :nth-child()
* :first-child
* :last-child
* :not()
* :valid
* :invalid

These selectors were used to improve interactivity, form feedback, and visual styling.

---

### Animations, Effects, and Transforms

Several advanced CSS techniques were added:

#### Text Effects

* Text shadows
* Gradient text styling

#### Transforms

* Scale
* Translate
* Rotate

#### Transitions

* Smooth hover effects
* Form focus transitions
* Interactive button effects

#### Animations

* Fade-in animation using @keyframes
* Optional loading animation

These additions improved user engagement while maintaining a professional appearance.

---

### Accessibility Improvements

Accessibility was improved through:

* Semantic HTML structure
* Labels for all form controls
* Alt text on images
* Logical content hierarchy
* Improved readability and navigation
* Better support for screen readers

---

### Cross-Browser Compatibility

The website was tested on:

* Google Chrome
* Edge

Results:

* Consistent layout rendering
* Responsive behaviour maintained
* Media elements functioning correctly
* Form validation working as expected

---

## Validation and Testing

### HTML Validation

All HTML pages were validated using the W3C Markup Validation Service.

Validated files:

* index.html
* about.html
* media.html
* contact.html

Results:

* No HTML validation errors
* No missing required attributes
* Semantic HTML structure verified

### CSS Validation

The stylesheet was validated using the W3C CSS Validator.

Results:

* No CSS syntax errors
* All selectors validated successfully
* Flexbox and Grid properties validated successfully

### Form Testing

The contact form was tested to ensure:

* Required fields prevent submission when empty
* Email validation works correctly
* Telephone field pattern validation functions correctly
* Number fields enforce minimum values
* Radio buttons function properly
* Checkboxes function properly
* Select dropdown displays correctly

### Media Testing

Verified functionality of:

* Video playback controls
* Audio playback controls
* Embedded iframe
* Image gallery
* Figure and figcaption implementation

### Responsive Testing

Tested at:

* Desktop
* Mobile

Results:

* Navigation remains accessible
* Flexbox layouts adapt correctly
* Grid layouts resize automatically
* Forms remain usable on smaller screens

---

## Detailed Issues Log

| Issue Identified              | Solution Implemented                          |
| ----------------------------- | --------------------------------------------- |
| Excessive use of div elements | Replaced with semantic HTML5 elements         |
| Missing metadata              | Added charset, viewport, and description tags |
| Navigation not using Flexbox  | Implemented responsive Flexbox navigation     |
| Missing Grid layout           | Created responsive gallery grid               |
| Missing audio element         | Added audio player with controls              |
| Missing second video          | Added second video showcase                   |
| Missing iframe                | Embedded Google Maps iframe                   |
| Images lacked captions        | Added figure and figcaption elements          |
| Form missing labels           | Added labels for all inputs                   |
| No validation                 | Added HTML5 validation attributes             |
| No animations                 | Added fade-in animation using keyframes       |
| No transitions                | Added hover and focus transitions             |
| Limited selectors             | Expanded selector usage and pseudo-classes    |
| Poor responsiveness           | Added media queries and responsive layouts    |

---

## Design Decisions

Several design decisions were made to improve usability, accessibility, and maintainability:

* Semantic HTML was prioritised to improve accessibility and SEO.
* Flexbox was selected for navigation and services because it simplifies responsive alignment.
* CSS Grid was selected for gallery sections because it provides better control over image layouts.
* A clean, professional colour scheme was used to suit a media production company.
* Animations and effects were kept subtle to avoid distracting from content.
* Mobile responsiveness was considered throughout development.

---

## Browser Compatibility Results

| Browser         | Result |
| --------------- | ------ |
| Google Chrome   | Pass   |
| Edge            | Pass   |

### Observations

* No major rendering issues detected.
* Minor font rendering differences were observed but did not affect usability.
* Media and form validation behaved consistently across browsers.

---

## Project Structure

media-production-website/

├── index.html

├── about.html

├── media.html

├── contact.html

├── css/

│ └── styles.css

├── images/

│ └── image assets

├── media/

│ └── video and audio assets

├── screenshots/

│ └── validation and browser screenshots

├── design/

│ ├── wireframe.pdf

│ └── issues-identified.pdf

└── README.md

---

## Screenshot Evidence

The following screenshots are included in the screenshots folder:

1. Home Page (Desktop)
2. Home Page (Mobile)
3. Media Page
4. Form Validation Example
5. Flexbox Layout Demonstration
6. CSS Grid Layout Demonstration
7. Media Elements Functioning
8. Animation Demonstration
9. Chrome Browser Test
10. Edge Browser Test

---

## How to View the Website

1. Download or clone the repository.
2. Open the project folder.
3. Open `index.html` in any modern web browser.
4. Navigate using the website menu.

---

## Limitations

* No backend functionality for form submission.
* Some media content may require replacement with production-quality assets.
* Minor visual differences may occur in older browsers.

