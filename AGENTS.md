# Repository Guidelines

This repository contains a simple, single-page static website for **مؤوسسة اصل السياج** (Asl Al-Siyaj Foundation), specializing in fencing and palm tree cultivation.

## Project Structure & Module Organization
The project follows a standard flat structure for static assets:
- [./index.html](./index.html): The main entry point, featuring Arabic (RTL) localization and semantic HTML5.
- [./style.css](./style.css): Contains all layout and theme styling, utilizing CSS Variables for consistent color management.
- [./script.js](./script.js): Handles client-side interactivity, including the mobile navigation toggle, smooth scrolling, and scroll-triggered animations via `IntersectionObserver`.

## Build, Test, and Development Commands
The project is purely static and does not require a build process or package manager.
- **Development**: Open [./index.html](./index.html) directly in any modern web browser or use a local development server (e.g., Live Server) for hot-reloading.
- **Deployment**: Upload all three files (`index.html`, `style.css`, `script.js`) to any static hosting provider.

## Coding Style & Naming Conventions
- **HTML**: Uses semantic elements and descriptive class names (e.g., `hero-overlay`, `service-card`).
- **CSS**: Employs CSS custom properties for theme colors (`--primary-color`, `--secondary-color`). Responsive design is implemented via media queries at the bottom of the file.
- **JavaScript**: Uses modern ES6+ syntax (`const`, arrow functions). DOM manipulation is kept minimal and performant.

## Testing Guidelines
- **Manual Verification**: Test the site across different screen widths (min-width: 320px) to ensure responsiveness.
- **RTL Support**: Verify that all content aligns correctly for Right-to-Left (RTL) reading.
- **Interactions**: Ensure the mobile menu functions correctly and smooth scrolling anchors target the correct offsets.
