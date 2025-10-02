# Vizzual Consult Website

A professional, responsive website for Vizzual Consult - a leading provider of consultancy and training services.

## Overview

This website showcases Vizzual Consult's expertise in professional consultancy and training services, featuring:

- **Consultancy Services**: Information Systems Control and Auditing, IT Project Management, Business Analysis, Data Analytics, and Financial Auditing
- **Training Courses**: Microsoft Excel, Power BI, ITIL Foundation, Project Management, Tally Accounting, and more
- **Professional Design**: Clean, corporate aesthetic with violet, gold, and black branding
- **Responsive Layout**: Optimized for desktop, tablet, and mobile devices

## Features

### Design Elements
- **Color Scheme**: Professional violet, gold, and black branding
- **Typography**: Clean, readable Inter font family
- **Logo Integration**: Official Vizzual Consult logo prominently displayed
- **Visual Hierarchy**: Clear sections and organized content layout

### Navigation
- **Responsive Hamburger Menu**: Mobile-friendly navigation
- **Dropdown Menus**: Organized service and course categories
- **Smooth Scrolling**: Enhanced user experience
- **Active States**: Clear indication of current page

### Pages
1. **Home Page**: Hero section, about overview, services preview
2. **Consultancy Services Page**: Overview of all consultancy services with detailed cards
3. **Training Courses Page**: Overview of all training courses with comprehensive information
4. **Service Pages**: Detailed information for each consultancy service (5 pages)
5. **Training Pages**: Comprehensive course details with modules and duration (7 pages)
6. **Contact Page**: Contact form, business information, and location

### Interactive Features
- **Contact Form**: Functional form with validation
- **Mobile Navigation**: Smooth hamburger menu animation
- **Hover Effects**: Enhanced user interaction
- **Responsive Design**: Adapts to all screen sizes

## File Structure

```
/
├── index.html                 # Home page
├── contact.html              # Contact page
├── consultancy-services.html # Overview of all consultancy services
├── training-courses.html     # Overview of all training courses
├── information-systems-control.html  # Information Systems Control service
├── it-project-management.html       # IT Project Management service
├── business-analysis.html           # Business Analysis service
├── data-analytics.html              # Data Analytics service
├── financial-auditing.html          # Financial Auditing service
├── excel-accountants.html           # Excel for Accountants training
├── advanced-excel.html              # Advanced Excel training
├── power-bi.html                    # Microsoft Power BI training
├── business-data-analytics.html     # Business Data Analytics training
├── itil-foundation.html             # ITIL 4 Foundation training
├── project-management.html          # Project Management training
├── tally-accounting.html            # Tally Accounting Software training
├── styles.css               # Main stylesheet
├── script.js                # JavaScript functionality
├── VizzualConsult.jpg       # Company logo
└── README.md               # This file
```

## Setup Instructions

1. **Local Development**: Simply open `index.html` in a web browser
2. **Local Server** (recommended): Use any local server for best experience
   ```bash
   # Using Python
   python3 -m http.server 8000
   
   # Using PHP
   php -S localhost:8000
   ```
3. **Access**: Navigate to `http://localhost:8000` in your browser

## Customization

### Colors
The color scheme is defined in CSS variables at the top of `styles.css`:
```css
:root {
    --primary-violet: #6b46c1;
    --gold: #f59e0b;
    --black: #1f2937;
    /* ... other colors */
}
```

### Content
- Update company information in HTML files
- Modify service descriptions and course details
- Replace placeholder contact information with actual details

### Google Maps Integration
To enable the interactive map on the contact page:
1. Get a Google Maps API key from Google Cloud Console
2. Replace `YOUR_API_KEY` in `contact.html` with your actual API key
3. Ensure the Maps JavaScript API is enabled in your Google Cloud project

## Browser Compatibility

- **Modern Browsers**: Chrome, Firefox, Safari, Edge (latest versions)
- **Mobile Browsers**: iOS Safari, Chrome Mobile, Samsung Internet
- **Features Used**: CSS Grid, Flexbox, ES6 JavaScript

## Performance Features

- **Optimized Images**: Properly sized logo and graphics
- **Efficient CSS**: Organized stylesheets with minimal redundancy
- **Clean JavaScript**: Modern, efficient code structure
- **Fast Loading**: Minimal external dependencies

## Accessibility

- **Semantic HTML**: Proper heading structure and landmarks
- **Keyboard Navigation**: Full keyboard accessibility
- **Screen Reader Friendly**: Descriptive alt text and labels
- **Color Contrast**: WCAG compliant color combinations

## Support

For technical support or customization requests, please contact the development team.

## License

© 2025 Vizzual Consult. All rights reserved.