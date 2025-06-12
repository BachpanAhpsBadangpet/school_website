# Greenwood Academy Website - User Guide

## Deployment Information
**Live Website URL:** https://qvkcxugw.manus.space

Your school website has been successfully deployed and is now publicly accessible at the above URL.

## Website Features

### 1. Homepage
- **Hero Section:** Eye-catching banner with school mission and call-to-action buttons
- **Quick Links:** Easy access to important resources (Calendar, Parent Portal, Library, Lunch Menu)
- **Navigation:** Smooth scrolling navigation to all sections

### 2. About Us Section
- School mission and values
- Key statistics (850 students, 65 teachers, 98% graduation rate, 25 years of excellence)
- Professional presentation of school information

### 3. Academic Programs
- STEM Education
- Arts & Humanities
- Athletics & Wellness
- Global Studies
Each program has detailed descriptions and attractive icons.

### 4. Admissions
- 4-step application process clearly outlined
- Interactive contact form for prospective families
- Grade level selection from Kindergarten to 12th Grade

### 5. News & Events
- Latest school announcements
- Event calendar integration
- Easy-to-read date formatting

### 6. Contact Information
- Complete contact details
- Office hours
- Contact form for inquiries

## Technical Features
- **Responsive Design:** Works perfectly on desktop, tablet, and mobile devices
- **Modern Styling:** Professional color scheme with blue (#0056b3) and green (#28a745) accents
- **Interactive Elements:** Hover effects, smooth animations, form validation
- **Accessibility:** Clean typography and good contrast ratios
- **Performance:** Optimized loading and smooth scrolling

## File Structure
```
school_website/
├── index.html          # Main website file
├── styles.css          # All styling and responsive design
├── script.js           # Interactive functionality
└── assets/
    ├── hero_image.jpg  # Homepage hero image
    └── school_logo.png # School logo
```

## Customization Guide

### Updating Content
1. **School Information:** Edit the text content in `index.html`
2. **Contact Details:** Update address, phone, and email in both the contact section and footer
3. **News & Events:** Modify the news cards with current announcements
4. **Statistics:** Update the numbers in the About section as needed

### Styling Changes
1. **Colors:** Modify the CSS variables in `styles.css` for the color scheme
2. **Fonts:** Change the Google Fonts imports and font-family declarations
3. **Layout:** Adjust grid layouts and spacing in the CSS file

### Adding New Sections
1. Add new HTML sections following the existing structure
2. Update the navigation menu to include new sections
3. Add corresponding CSS styles for consistency

### Form Integration
The contact forms are currently set up with JavaScript validation and demo functionality. To integrate with a real backend:
1. Replace the form submission handlers in `script.js`
2. Add proper form action URLs
3. Implement server-side form processing

## Maintenance Recommendations
1. **Regular Updates:** Keep content fresh with new news and events
2. **Image Optimization:** Compress images for faster loading
3. **Security:** If adding backend functionality, implement proper security measures
4. **Analytics:** Consider adding Google Analytics for visitor tracking
5. **SEO:** Add meta descriptions and optimize for search engines

## Browser Compatibility
The website is compatible with all modern browsers including:
- Chrome
- Firefox
- Safari
- Edge

## Support
For technical support or modifications, refer to the source code files provided. The website is built with standard HTML, CSS, and JavaScript, making it easy to maintain and modify.

