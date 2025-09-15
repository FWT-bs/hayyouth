# HAY Youth Website

A modern, responsive multi-page website for HAY Youth non-profit organization with animations and mobile-friendly design.



## Pages

### 1. Home Page (`index.html`)
- Hero section with animated background icons
- Feature tabs (Youth Mentorship, Educational Programs, Community Service, Leadership Development)
- Impact statistics with animated counters
- Call-to-action sections

### 2. Our Team Page (`team.html`)
- Leadership team profiles with hover effects
- Program staff showcase
- Social media links for team members
- Join our team section

### 3. Events Page (`events.html`)
- Upcoming events with featured event highlighting
- Workshop tabs (Life Skills, Technology, Arts & Creativity, Health & Wellness)
- Community outreach programs
- Volunteer opportunities

### 4. Donate Page (`donate.html`)
- Impact showcase showing donation amounts and their effects
- Interactive donation form with multiple payment options
- Success stories from program participants
- Additional giving options sidebar

## Key Features

### Navigation
- **Sticky navbar** that stays visible while scrolling
- **Dropdown menu** under "Events" with smooth animations
- **Mobile hamburger menu** for smaller screens
- **Logo placeholder** (replace `logo.png` with your actual logo)

### Animations
- **Smooth scroll effects** when navigating between sections
- **Fade-in animations** for content as you scroll
- **Hover effects** on cards, buttons, and images
- **Floating background icons** in hero section
- **Animated counters** for statistics

### Mobile Responsiveness
- **Responsive grid layouts** that adapt to screen size
- **Mobile-optimized navigation** with hamburger menu
- **Touch-friendly buttons** and interactive elements
- **Optimized typography** for different screen sizes

## How to Customize

### Changing Content
1. **Text Content**: Edit the HTML files directly to update text, headings, and descriptions
2. **Images**: Replace placeholder images with your own (maintain similar dimensions)
3. **Logo**: Replace `logo.png` with your organization's logo
4. **Colors**: Modify the CSS color variables in `styles.css`
5. **Contact Information**: Update footer links and contact details

### Adding New Pages
1. Create a new HTML file following the existing structure
2. Copy the navigation and footer from existing pages
3. Add the new page link to all navigation menus
4. Add corresponding styles to `styles.css` if needed

### Modifying Styles
- **Colors**: Update the color scheme in `styles.css`
- **Fonts**: Change Google Fonts import and font-family declarations
- **Spacing**: Adjust padding and margin values
- **Animations**: Modify animation durations and effects in CSS and JavaScript

### Form Integration
The donation form currently shows a demo. To integrate with a real payment processor:
1. Replace the form submission JavaScript in `donate.html`
2. Integrate with services like Stripe, PayPal, or your preferred payment processor
3. Add server-side processing for form data

## File Structure
```
hayyouth/
├── index.html          # Home page
├── team.html           # Our Team page
├── events.html         # Events page
├── donate.html         # Donate page
├── styles.css          # All CSS styles
├── script.js           # JavaScript functionality
├── logo.png           # Logo placeholder (replace with your logo)
└── README.md          # This file
```

## Browser Support
- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile browsers (iOS Safari, Chrome Mobile)
- Responsive design works on all screen sizes

## Getting Started
1. Replace `logo.png` with your organization's logo
2. Update all text content with your organization's information
3. Replace placeholder images with real photos
4. Customize colors and styling to match your brand
5. Test on different devices and browsers

## Technical Notes
- Uses modern CSS Grid and Flexbox for layouts
- JavaScript handles smooth scrolling, animations, and interactive elements
- Font Awesome icons for consistent iconography
- Google Fonts (Inter) for modern typography
- No external dependencies beyond CDN resources

## Support
For questions about customizing this website, refer to the inline comments in the code or consult web development resources for HTML, CSS, and JavaScript.
