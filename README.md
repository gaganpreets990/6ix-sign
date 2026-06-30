# 6ix Sign - Professional Sign Installation

A modern, responsive landing page for 6ix Sign, a professional sign installation company serving the Greater Toronto Area (GTA).

## Features

- **Responsive Design**: Fully responsive layout that works on mobile, tablet, and desktop devices
- **Modern UI**: Clean, professional design with smooth animations and transitions
- **Service Showcase**: Organized grid layout displaying all services offered
- **Why Choose Us**: Highlights key differentiators and business advantages
- **Contact Form**: Functional form for quote requests with client information
- **Smooth Navigation**: Sticky navigation bar with smooth scroll functionality
- **Performance Optimized**: Fast loading with optimized CSS and minimal JavaScript

## Project Structure

```
6ix-sign/
├── index.html          # Main HTML file with page structure
├── styles.css          # Complete styling and responsive design
├── script.js           # Interactive features and form handling
└── README.md          # Project documentation
```

## Key Sections

### 1. Navigation Bar
- Sticky header with logo and navigation links
- Quick access to all page sections
- Contact CTA buttons

### 2. Hero Section
- Eye-catching headline and tagline
- Call-to-action buttons for quotes and phone
- Gradient background for visual appeal

### 3. Services
- 5 key service offerings with icons
- Hover effects for interactivity
- Grid layout that adapts to screen size

### 4. Why Choose Us
- 3 key business differentiators
- Professional icons and descriptions
- Trust-building content

### 5. Contact Form
- Name, email, phone, and job details fields
- Client-side validation
- Smooth form interactions

### 6. Footer
- Copyright information
- Service area mention

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Advanced styling with CSS Grid, Flexbox, and animations
- **JavaScript (Vanilla)**: No dependencies - pure JavaScript for interactivity
- **Responsive Design**: Mobile-first approach with media queries

## Getting Started

### Prerequisites
- Web browser (Chrome, Firefox, Safari, Edge)
- Text editor or code editor (VS Code, Sublime, etc.)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/gaganpreets990/6ix-sign.git
cd 6ix-sign
```

2. Open in browser:
```bash
# Simply open index.html in your browser
open index.html
# or
start index.html
```

3. Or use a local server (recommended):
```bash
# Using Python 3
python -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js (with http-server package)
npx http-server
```

Then navigate to `http://localhost:8000` (or the port shown in your terminal).

## Customization

### Update Business Information
Edit these values in `index.html`:
- Phone number in the "Call" button
- Contact form fields
- Service descriptions
- Company name and branding

### Color Scheme
Modify CSS variables in `styles.css`:
```css
:root {
    --primary-color: #1e3a8a;        /* Main blue */
    --accent-color: #dc2626;         /* Red accent */
    --secondary-color: #f3f4f6;      /* Light gray background */
    /* ... other colors */
}
```

### Fonts
Default font family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif
Change in `styles.css` under `body` selector

## Form Submission

Currently, the form displays a success message. To integrate with a backend:

1. Update the form submission handler in `script.js`
2. Send data to your server/email service (e.g., Firebase, Netlify Forms, EmailJS)
3. Example backend integration needed for:
   - Email notifications
   - Database storage
   - Lead management

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Metrics

- Lightweight: Single CSS file, minimal JavaScript
- Fast load times: Optimized for quick rendering
- SEO-friendly: Semantic HTML structure
- Accessibility: WCAG-compliant markup

## Responsive Breakpoints

- Desktop: 1200px+
- Tablet: 768px - 1199px
- Mobile: < 768px
- Small Mobile: < 480px

## Future Enhancements

- [ ] Image gallery/portfolio section
- [ ] Customer testimonials
- [ ] Pricing calculator
- [ ] Blog/case studies
- [ ] Multi-language support
- [ ] Email integration
- [ ] Backend API for form submissions
- [ ] Chat widget for instant support
- [ ] Google Analytics integration
- [ ] SEO optimization

## License

This project is open source and available under the MIT License.

## Support

For questions or support, please contact:
- Email: info@6ixsign.com
- Phone: (416) XXX-XXXX

---

Built with ❤️ for 6ix Sign | Serving the GTA with precision and pride