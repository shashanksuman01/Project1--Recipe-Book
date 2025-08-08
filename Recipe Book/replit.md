# The Family Recipe Book

## Overview

The Family Recipe Book is a static HTML website that serves as a digital collection of family recipes. The site presents recipes organized by categories (Appetizers, Main Courses, and Desserts) with a clean, modern design focused on readability and ease of navigation. The project aims to preserve and share traditional family recipes in an accessible digital format, featuring individual recipe pages with detailed information including cooking time, serving size, and difficulty level.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
The application uses a traditional multi-page HTML structure with static files. The design follows a hierarchical organization where the main index page serves as the hub, with category pages organizing recipes by type, and individual recipe pages providing detailed information.

**Navigation Structure:**
- Root level: Main homepage (`index.html`)
- Category level: Organized recipe collections (`categories/`)
- Recipe level: Individual recipe details (`recipes/`)

**Styling Approach:**
The site uses a single CSS file (`styles.css`) for consistent styling across all pages. The design system incorporates:
- Typography: Combination of Playfair Display (serif) for headings and Inter (sans-serif) for body text
- Color scheme: Warm orange accent colors (#e67e22, #d35400) with neutral grays
- Layout: Container-based responsive design with CSS Grid for recipe cards
- Visual elements: Font Awesome icons for enhanced user interface

**Content Organization:**
Recipes are categorized into three main sections:
- Appetizers (salads, small plates)
- Main Courses (pasta, meat dishes, stir-fries)
- Desserts (cakes, pies, sweet treats)

Each recipe page includes structured information such as preparation time, serving size, and difficulty level with consistent iconography.

### Static Asset Management
Images are sourced from external services (Pixabay) rather than being stored locally, which reduces repository size but creates dependencies on external image hosting.

### Responsive Design
The CSS architecture supports mobile-first responsive design with flexible container widths and scalable typography, though specific breakpoints are not visible in the provided files.

## External Dependencies

### Font Services
- **Google Fonts**: Provides Playfair Display and Inter font families
- **Font Awesome CDN**: Supplies iconography for navigation, recipe metadata, and visual elements

### Image Hosting
- **Pixabay**: External image hosting service for recipe photography and visual content

### Browser Dependencies
- Modern CSS features including CSS Grid, Flexbox, and CSS Custom Properties
- Font loading optimization with preconnect directives
- Smooth scrolling behavior for enhanced user experience

The architecture prioritizes simplicity and maintainability through static file serving, making it suitable for basic web hosting without requiring server-side processing or database management.