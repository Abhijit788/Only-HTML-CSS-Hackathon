# STRIKE - Premium Online Courses Platform

## Project Overview

This is a complete website built for a hackathon using **HTML and CSS only** (no JavaScript). The website features a modern design with advanced CSS-only interactions.

## Features Implemented

### ✅ Completed Features

1. **Responsive Navigation** - Mobile-friendly with hamburger menu
2. **Hero Section** - Animated background with call-to-action
3. **Course Grid** - Showcase of available courses
4. **Featured Courses Carousel** - Horizontally scrollable course cards
5. **About Page** - Complete company information and team
6. **Contact Page** - Contact form with FAQ accordion
7. **Footer** - Enhanced glassmorphism design
8. **Limited Time Offer Section** - Advanced promotional section with:
   - Countdown timer animation
   - CSS-only tabs (using radio buttons)
   - CSS-only expandable curriculum sections
   - Student reviews section
   - Instructor profile
   - Pricing sidebar with discount

### 🎨 CSS Architecture

The project uses a modular CSS approach:

- `css/base.css` - Base styles and CSS variables
- `css/navbar.css` - Navigation components
- `css/hero.css` - Hero section styling
- `css/courses.css` - Course grid and cards
- `css/footer.css` - Footer with glassmorphism effects
- `css/about-contact.css` - About and Contact pages
- `css/limited-offer.css` - Limited Time Offer section (CSS-only interactions)
- `style.css` - Main utilities and layout

### 🚀 Advanced CSS Techniques Used

1. **CSS-only Tabs** - Using radio buttons and sibling selectors
2. **CSS-only Accordion** - Expandable content without JavaScript
3. **CSS Grid & Flexbox** - Modern layout techniques
4. **CSS Animations** - Smooth hover effects and transitions
5. **CSS Variables** - Consistent theming and easy customization
6. **Responsive Design** - Mobile-first approach
7. **Glassmorphism Effects** - Modern UI design trend

### 📁 File Structure

```
htmlonly/
├── landingpage.html          # Main entry point
├── about.html               # About page
├── contact.html             # Contact page
├── course-detail.html       # Course details page
├── logo.png                 # STRIKE logo
├── style.css               # Main stylesheet
└── css/
    ├── base.css            # Base styles
    ├── navbar.css          # Navigation
    ├── hero.css            # Hero section
    ├── courses.css         # Course components
    ├── footer.css          # Footer styling
    ├── about-contact.css   # About/Contact pages
    └── limited-offer.css   # Limited Time Offer section
```

### 🎯 CSS-Only Interactive Features

#### Limited Time Offer Section

- **Class Prefix**: `lto-` (to avoid conflicts)
- **Tabs**: Radio button approach for content switching
- **Accordion**: Checkbox-based expandable curriculum
- **Animations**: Pure CSS countdown and hover effects

#### Key CSS-Only Techniques

```css
/* CSS-only tabs using radio buttons */
.lto-tab-radio:checked ~ .lto-tab-content .lto-tab-overview {
  display: block;
}

/* CSS-only accordion using checkboxes */
.lto-section-checkbox:checked ~ .lto-section-lessons {
  max-height: 500px;
}

/* Hover animations */
.lto-play-button:hover {
  transform: scale(1.1);
}
```

### 🎨 Design Features

- **Modern Color Scheme** - Professional blue and gold palette
- **Typography** - Clean, readable font hierarchy
- **Spacing System** - Consistent spacing using CSS variables
- **Responsive Breakpoints** - Mobile, tablet, desktop optimization
- **Accessibility** - ARIA labels and keyboard navigation support

### 🔧 Browser Compatibility

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Internet Explorer 11+ (basic support)

### 📱 Responsive Design

- Mobile: 320px - 768px
- Tablet: 768px - 1024px
- Desktop: 1024px+

## Usage Instructions

### Running the Website

1. Open `landingpage.html` in any modern web browser
2. Navigate using the top navigation menu
3. Test responsive design using browser developer tools

### Customization

1. Modify CSS variables in `css/base.css` for theming
2. Update content in HTML files
3. Add new components using the established CSS architecture

## Technical Highlights

### No JavaScript Required

All interactive features are implemented using:

- CSS `:hover` and `:focus` pseudo-classes
- CSS `:checked` selector for state management
- CSS `transition` and `animation` properties
- CSS Grid and Flexbox for layout

### Performance Optimized

- Minimal CSS file sizes
- Efficient selectors
- Optimized animations using `transform` and `opacity`
- Lazy loading friendly structure

### Accessibility Features

- Semantic HTML structure
- ARIA labels where needed
- Keyboard navigation support
- Screen reader friendly
- High contrast ratios

## Future Enhancements

1. Add more course categories
2. Implement dark mode toggle (CSS-only)
3. Add more interactive components
4. Enhance mobile animations
5. Add course filtering system

---

**Built for Hackathon** - Pure HTML & CSS Implementation
**Company**: STRIKE - Premium Online Education Platform
