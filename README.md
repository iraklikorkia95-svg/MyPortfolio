# Irakli Korkia Photography Portfolio

A minimalist and elegant photography portfolio website designed to showcase travel and architectural photography with a focus on performance and user experience.

## Features

- **Dynamic Navigation**: A sleek navigation bar that adapts on scroll, revealing gallery descriptions and titles.
- **Interactive Album Grid**: The landing page features high-impact album covers with hover effects and smooth reveal animations.
- **Masonry Gallery Layout**: Responsive grid system for viewing photos in their natural aspect ratios.
- **Custom Infinite Lightbox**: An immersive "camera roll" style lightbox for full-screen viewing, featuring:
  - Infinite scrolling loop.
  - Keyboard navigation (Arrows/Escape).
  - Mouse wheel support for fast browsing.
  - Smooth CSS-driven transitions and blurs.
- **Scroll Reveal**: Uses the `IntersectionObserver` API for high-performance entry animations as the user scrolls.

## Technologies Used

- **HTML5**: Semantic structure.
- **CSS3**: Custom layouts using Grid and Flexbox, along with advanced transitions and backdrop filters.
- **Vanilla JavaScript**: Lightweight, custom-built logic for the lightbox and scroll interactions (no heavy libraries).
- **Google Fonts**: Montserrat for bold, clean typography.

## Project Structure

- `index.html`: The main entry point and portfolio selection page.
- `strasbourg.html`, `vosges.html`, `corsica.html`: Individual gallery pages.
- Assets: Photography organized by location folders.

## How to Run
Simply open `index.html` in any modern web browser.