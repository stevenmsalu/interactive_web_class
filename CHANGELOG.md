# CHANGELOG

All notable changes to this project will be documented here.

## [Unreleased]

### Fixes
- Moved `logo.svg` into the `assets/` folder.
- Relocated `preview.html` to the correct directory.
- Fixed overlapping text and copy button issues in code boxes.

### Lessons
- Added 2 new HTML lessons.
- Added 3 new CSS lessons.
- Added 3 new JavaScript lessons.

### Quizzes
- Added 6 new quizzes to the quiz page.

### CSS Overhaul
- Refined color palette in `:root` for better contrast and softer surfaces.
- Introduced `.text-link` class for clear blue navigation links.
- Set `body` background to solid white instead of gradient.
- Updated header (`.site-header`) with higher z-index and new background color.
- Scoped hero background image to the home page only (`.home .hero`).
- Simplified gradient text styles to solid accessible blue.
- Improved preview card layout:
  - Contained iframe (`.demo-card`, `.mock`).
  - Stabilized size and spacing.
- Unified UI surfaces (`.code`, `.details`, `textarea`) with card background.
- Added responsive tweaks:
  - Smaller preview on mobile.
  - Subtle radial gradient background on ultra-wide screens.
- Added `<body class="home">` in `index.html` to target home-only styles.

### Project Structure
- Organized into modular directories:
  - `pages/` for HTML files.
  - `js/` for JavaScript files.
- Kept `index.html` and `styles.css` in the project root.
