# Simple Personal Portfolio Website

A clean, modern, and responsive personal portfolio website built with HTML, CSS, and JavaScript. Features a professional blue and white color scheme with smooth animations and mobile-friendly design.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Clean Navigation**: Fixed navigation bar with smooth scrolling
- **Modern UI**: Professional blue and white color scheme
- **Interactive Elements**: Hover effects, smooth animations, and transitions
- **Contact Form**: Functional contact form (demo mode)
- **Easy to Customize**: Simple HTML/CSS structure for easy editing

## Sections

1. **Home/Hero**: Name, title, introduction, and call-to-action buttons
2. **About Me**: Personal introduction and basic information
3. **Skills**: Skill cards with icons and proficiency levels
4. **Projects**: Project showcase with descriptions and tech stack
5. **Education**: Timeline of educational background
6. **Contact**: Contact information and contact form

## File Structure

```
simple-portfolio/
├── index.html      # Main HTML file
├── styles.css      # All styling
├── script.js       # JavaScript functionality
└── README.md       # This file
```

## How to Use

1. **Download or clone** the files to your computer
2. **Open `index.html`** in your web browser
3. **Customize** the content with your information (see below)

## Customization Guide

### Personal Information

Replace the placeholder text throughout the files with your actual information:

#### In `index.html`:

**Hero Section (Line ~45-55):**
- Replace "Your Name" with your actual name
- Update the subtitle "BIM Student | Python & Django Developer"
- Edit the description paragraph
- Update the page title in `<title>` tag (Line 8)

**About Section (Line ~65-85):**
- Replace the introduction paragraphs with your own
- Update education details
- Change location and email

**Skills Section (Line ~95-130):**
- Add, remove, or modify skill cards
- Change skill icons (emojis) and proficiency levels

**Projects Section (Line ~135-175):**
- Replace the placeholder project with your actual projects
- Update project descriptions
- Change technology tags
- Add GitHub and live demo links
- Duplicate the project card div to add more projects

**Education Section (Line ~180-220):**
- Update education details
- Add or remove timeline items
- Change institution names and dates

**Contact Section (Line ~225-270):**
- Update your email, phone, and location
- Add your actual LinkedIn and GitHub links
- The contact form is in demo mode - you'll need to integrate it with a backend service like Formspree or Netlify Forms

#### In `styles.css`:

**Color Theme (Lines 10-17):**
```css
:root {
    --primary-color: #2563eb;      /* Main blue color */
    --primary-dark: #1d4ed8;        /* Darker blue for hover */
    --primary-light: #3b82f6;       /* Lighter blue */
    --secondary-color: #1e40af;     /* Secondary blue */
    --text-color: #1f2937;          /* Main text color */
    --text-light: #6b7280;          /* Light text color */
    --bg-white: #ffffff;            /* White background */
    --bg-light: #f3f4f6;            /* Light gray background */
    --bg-alt: #e5e7eb;              /* Alternative background */
}
```

Change these color values to match your preferred color scheme.

**Fonts (Line 23):**
```css
font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
```
Replace with your preferred font family.

#### In `script.js`:

**Contact Form (Lines 35-45):**
The contact form currently shows an alert. To make it functional:

1. **Option 1 - Formspree:**
   - Sign up at [formspree.io](https://formspree.io)
   - Replace the form action with your Formspree endpoint
   - Update the form tag in HTML: `<form action="YOUR_FORMSPREE_URL" method="POST">`

2. **Option 2 - Netlify Forms:**
   - Host on Netlify
   - Add `netlify` attribute to form tag
   - Update form: `<form name="contact" method="POST" data-netlify="true">`

3. **Option 3 - Custom Backend:**
   - Replace the JavaScript form handler with your own backend integration

## Adding Images

To add your own images:

1. Create an `images` folder in the project directory
2. Add your images (profile photo, project screenshots, etc.)
3. Replace placeholder divs with `<img>` tags:

```html
<!-- Replace this -->
<div class="placeholder-image">🏥</div>

<!-- With this -->
<img src="images/your-image.jpg" alt="Project Screenshot" class="project-img">
```

4. Add corresponding CSS for the images if needed

## Deployment

### GitHub Pages (Free)

1. Create a GitHub repository
2. Upload the files
3. Go to Settings > Pages
4. Select the main branch as source
5. Your site will be live at `yourusername.github.io/repository-name`

### Netlify (Free)

1. Drag and drop the project folder to [netlify.com](https://netlify.com)
2. Or connect your GitHub repository for automatic deployments

### Vercel (Free)

1. Import the project in [vercel.com](https://vercel.com)
2. Deploy with one click

### Traditional Hosting

1. Upload all files to your web host's public directory
2. Access via your domain

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Features Breakdown

### Responsive Design
- Mobile-first approach
- Hamburger menu for mobile navigation
- Flexible grid layouts
- Optimized for all screen sizes

### Animations
- Smooth scroll navigation
- Fade-in effects on scroll
- Hover effects on cards and buttons
- Smooth transitions throughout

### Accessibility
- Semantic HTML structure
- Proper heading hierarchy
- Keyboard navigation support
- Readable color contrast

## Support

For issues or questions, feel free to open an issue on the repository or contact the developer.

## License

This project is open source and available for personal and commercial use.

---

**Note**: Remember to replace all placeholder content with your actual information before deploying your portfolio!
