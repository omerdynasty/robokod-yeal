# AI Agent Instructions for Robokod YEAL Website

## Project Overview
This is a single-page promotional website for the Robokod YEAL robotics team from Yunus Emre Anadolu High School. The site showcases the team's achievements, competitions, and team members.

## Project Structure
- `index.html` - Main and only HTML file containing the site structure
- `style.css` - All styling rules and responsive design implementations
- Image assets:
  - `logo.png` - Team logo
  - Competition images: `yerel.jpeg`, `ulusal.jpeg`, `wro.jpeg`, `slovenya.webp`
  - `favicon.ico` - Site favicon

## Key Design Patterns

### Styling Conventions
- The site uses lowercase text transformation throughout (`text-transform: lowercase`)
- Color scheme:
  - Primary background: `#1a337b` (dark blue)
  - Secondary backgrounds: `#111` (dark gray)
  - Text colors: `#fff` (white), `#eee` (light gray), `#888` (medium gray)
- Responsive breakpoints:
  - Mobile layout triggers at max-width: 500px
  - Grid layouts adjust from 4 columns to 2 columns on mobile

### Component Structure
- Fixed header banner with team application link
- Centered container with max-width of 480px
- Grid-based layouts for:
  - Competition showcase (2x2 grid)
  - Team members (4x1 grid, converts to 2x2 on mobile)

### Content Updates
When updating content:
1. Team member changes should be made in the `.team-grid` section
2. Competition updates go in the `.yarismalar` section
3. Contact information is in the `.social` and email sections
4. Main description text is in the `.summary` class

## Development Workflow
This is a static website with no build process. Changes can be made directly to the HTML and CSS files.

## Contact & Links
- Team email: robokodyeal@gmail.com
- Instagram: @robokodyeal
- Maintained by: [dyna](https://github.com/omerdynasty)