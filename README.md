# FitZone - Premium Gym & Fitness Website

A professional, modern, and fully responsive gym management website built with HTML, CSS, and JavaScript.

## 🎯 Features

### 📱 Responsive Design
- Fully responsive layout that works on desktop, tablet, and mobile devices
- Professional UI/UX with smooth animations and transitions
- Mobile-friendly navigation with hamburger menu

### 🏋️ Pages Included

1. **Home (index.html)**
   - Hero section with call-to-action buttons
   - Features showcase (6 key benefits)
   - Statistics section
   - Professional footer with contact info

2. **Classes (classes.html)**
   - 12 different fitness classes
   - Filterable class categories (Cardio, Strength, Flexibility, Mind & Body)
   - Class details including trainer names, schedules, and descriptions
   - "Book Now" functionality for each class

3. **Membership (membership.html)**
   - 6 different membership tiers:
     - Basic: $29/month
     - Standard: $59/month (Most Popular)
     - Premium: $99/month
     - Corporate: $25/month
     - Student: $19/month
     - Day Pass: $15/day
   - Features comparison table
   - Additional services (Personal Training, Nutrition Consultation, etc.)
   - Monthly/Annual billing toggle
   - FAQ section

4. **Contact (contact.html)**
   - Contact form with validation
   - Complete contact information
   - Embedded Google Map
   - FAQ section with expandable answers
   - Social media links
   - Business hours

### 🎨 Design Features

- **Color Scheme:**
  - Primary: #ff6b35 (Orange)
  - Secondary: #004e89 (Dark Blue)
  - Accent: #f77f00 (Golden)
  - Dark Background: #0a0e27

- **Typography:**
  - Segoe UI, Tahoma, Geneva for modern feel
  - Professional hierarchy with varied font sizes

- **Interactive Elements:**
  - Smooth scroll navigation
  - Hover effects on buttons and cards
  - Mobile menu toggle animation
  - Form validation
  - Counter animations for statistics
  - Back-to-top button

### 💻 Technical Stack

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with flexbox and grid
- **JavaScript (Vanilla)** - Interactive features without dependencies

### 🔧 Key JavaScript Features

- Mobile menu toggle with hamburger animation
- Smooth scrolling for all anchor links
- Intersection Observer for scroll animations
- Form validation and submission handling
- Counter animations for statistics
- Class filtering functionality
- Navbar shadow on scroll
- Auto-generating back-to-top button
- Lazy loading image support

### 📦 Files Structure

```
gym-system/
├── index.html          # Home page
├── classes.html        # Classes page
├── membership.html     # Membership & pricing page
├── contact.html        # Contact & information page
├── styles.css          # All styling
└── script.js           # All JavaScript functionality
```

## 🚀 Quick Start

1. Clone the repository:
```bash
git clone https://github.com/yasmin-fayyad/gym-system.git
```

2. Navigate to the folder:
```bash
cd gym-system
```

3. Open `index.html` in your web browser or use a local server:
```bash
# Using Python 3
python -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js (if installed)
npx http-server
```

4. Visit `http://localhost:8000` in your browser

## 📱 Responsive Breakpoints

- **Desktop:** 1200px and above
- **Tablet:** 768px to 1199px
- **Mobile:** Below 768px
- **Small Mobile:** Below 480px

## 🎯 Features Breakdown

### Navigation
- Sticky navigation bar with gradient background
- Smooth hover effects with underline animation
- Mobile hamburger menu with animated icon
- Logo with brand styling

### Hero Section
- Full-width background with gradient overlay
- Animated content using CSS keyframes
- Dual call-to-action buttons
- Professional typography

### Feature Cards
- 6-card grid layout
- Hover animations with elevation effect
- Icon emoji support
- Responsive grid collapse on mobile

### Membership Cards
- Featured/popular plan highlighting
- Feature lists with checkmarks
- Price display with billing period
- Call-to-action buttons

### Forms
- Input validation
- Email format checking
- Visual feedback on focus
- Error handling

### Footer
- Multi-column layout
- Quick links
- Contact information
- Copyright notice

## 🔐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Android)

## 📊 Performance Features

- Optimized CSS with minimal repaints
- Smooth animations using transform and opacity
- Lazy loading support for images
- Mobile-optimized bundle size
- No external dependencies

## 🎓 Learning Resources

This project demonstrates:
- Semantic HTML5 structure
- CSS Grid and Flexbox layouts
- CSS custom properties (variables)
- Modern JavaScript (ES6+)
- Intersection Observer API
- Form handling and validation
- Responsive web design principles
- Accessibility considerations

## 📝 Customization Guide

### Change Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #ff6b35;
    --secondary-color: #004e89;
    --accent-color: #f77f00;
    /* ... more variables */
}
```

### Modify Content
Simply edit the HTML files in any text editor and replace:
- Text content
- Contact information
- Pricing
- Class details

### Add Classes
Add new `.class-card` elements to `classes.html` with appropriate `data-category` attributes

### Customize Membership Plans
Edit the `.pricing-card` elements in `membership.html`

## 🐛 Known Issues & Future Improvements

- Map embedding uses placeholder coordinates (update with actual location)
- Form submissions are simulated (integrate with backend for real submissions)
- Consider adding:
  - Backend API integration
  - Database for class schedules
  - User authentication
  - Booking system
  - Payment gateway integration

## 📄 License

This project is open source and available under the MIT License.

## 👤 Author

Created by Yasmin Fayyad

## 🤝 Contributing

Feel free to fork this project and submit pull requests for any improvements!

## 📞 Support

For questions or support, please contact:
- Email: info@fitzone.com
- Phone: +1 (555) 123-4567
- Address: 123 Fitness Ave, New York, NY 10001

---

**Last Updated:** June 2026

**Version:** 1.0.0