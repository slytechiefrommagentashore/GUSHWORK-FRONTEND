# Gushwork Front-End Developer Assignment
## Overview
This repository contains the front-end implementation for the Gushwork Web Development Assignment. The goal was to build a fully responsive, pixel-perfect web page based on the provided Figma design using strictly Vanilla HTML, CSS, and JavaScript (no external frameworks or libraries).

## Live Demo
(Optional: If you deployed it using GitHub Pages, Netlify, or Vercel, add the link here!)
View Live Site Here

# Technologies Used
HTML5: Semantic markup for accessibility and structure.

CSS3: Modern CSS including Flexbox, CSS Grid, and custom media queries for responsive design.

Vanilla JavaScript: DOM manipulation, event handling, and complex scroll/hover logic without the use of libraries like jQuery or React.

## Key Features Implemented
1. Pixel-Perfect & Responsive Design
Followed the Figma specifications closely for layout, colors, and typography.

Built a fully responsive layout that adapts seamlessly across mobile (480px), tablet (768px), and desktop (1024px+) screens.

Implemented a mobile-friendly hamburger navigation menu.

2. Custom Sticky Header
Engineered a sticky header that remains hidden until the user scrolls past the first fold.

Smoothly transitions into view above the navigation bar and hides itself when scrolling back up to the top.

3. Interactive Image Carousel with Zoom
Built a custom image carousel from scratch with left/right navigation and thumbnail selection.

Hover-to-Zoom: Implemented complex JavaScript math to calculate cursor coordinates (xPercent, yPercent) to dynamically update the background position of a zoomed preview box, creating a smooth magnifying glass effect.

## How to Run Locally
Since this project uses vanilla web technologies, no build tools or package managers (like npm) are required.

Clone this repository: git clone <your-repo-link>

Navigate to the project folder.

Simply open the index.html file in your preferred web browser, or use an extension like VS Code's Live Server for the best experience.

## File Structure
index.html - The main semantic HTML structure.

styles.css - All styling, grid layouts, and responsive media queries.

script.js - Contains logic for the sticky header, mobile menu, carousel functionality, and zoom preview.

assets/ - Contains all exported SVGs and images used in the project.
