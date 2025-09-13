# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static HTML portfolio website for "Skapece", a 3D animator. The portfolio showcases animations and backgrounds through a modern, responsive web interface.

## Architecture

- **Static HTML Portfolio**: Single-page application built with vanilla HTML, CSS, and JavaScript
- **Dual Structure**: Contains two main HTML files:
  - `index.html` (root) - Main portfolio page
  - `main/index.html` - Alternative/development version
- **Asset Organization**:
  - `images/` - Portfolio media assets organized by category:
    - `animations/` - Animation showcases
    - `backgrounds/` - Background artwork
    - `extra/` - Favicon, meta tags images, etc.
    - `home/` - Homepage assets
  - `main/` - Contains alternative version and additional assets

## Development

This is a static website with no build process or package management. Development involves:

1. **Local Development**: Open HTML files directly in browser or use a local server
2. **File Structure**: All styling is embedded within HTML files using `<style>` tags
3. **Dependencies**: External resources loaded via CDN:
   - Google Fonts (Inter font family)
   - Font Awesome icons
4. **Language**: Content is in Italian ("it" lang attribute)

## Design System

- **CSS Variables**: Uses custom properties for theming:
  - `--font-principale`: Inter font
  - `--colore-testo-primario`: Primary text (#212529)
  - `--colore-testo-secondario`: Secondary text (#6c757d)
  - `--colore-sfondo`: Background (#f8f9fa)
  - `--colore-sidebar`: Sidebar background (#ffffff)
  - `--colore-accento`: Accent color (#007bff)
  - `--larghezza-sidebar`: Sidebar width (280px)

## Key Features

- Responsive design with sidebar navigation
- Portfolio gallery for 3D animations and backgrounds
- Social media integration
- Italian language content
- Meta tags optimized for social sharing

## File Management

When editing this portfolio:
- Images should be placed in appropriate subdirectories of `images/`
- Styling changes should be made within the `<style>` tags in HTML files
- Both `index.html` files may need updates depending on which is the primary version
- No build or compilation steps required - changes are immediately visible