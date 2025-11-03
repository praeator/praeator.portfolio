# Portfolio Website

A modern, responsive portfolio website to showcase your projects, skills, and experience.

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Clean and professional design with smooth animations
- **Interactive Elements**: Smooth scrolling, mobile navigation, and scroll animations
- **Sections Included**:
  - Hero/Landing section with social links
  - About section with personal information
  - Skills section organized by categories
  - Projects showcase with descriptions and links
  - Contact form with contact information
  - Footer with social links

## Quick Start

1. **View Your Portfolio**: Simply open `index.html` in your web browser
2. **Customize Content**: Edit the HTML file to add your personal information
3. **Modify Styling**: Adjust colors and styles in `styles.css`
4. **Add Functionality**: Extend features in `script.js`

## Customization Guide

### Personal Information

Edit the following sections in `index.html`:

- **Name**: Replace "Your Name" in the hero section
- **Title**: Update "Full Stack Developer | Designer | Problem Solver"
- **Description**: Modify the hero description text
- **About**: Update the about section with your background
- **Location, Experience, Education**: Update in the about info items
- **Contact Details**: Update email, phone, and location in the contact section

### Social Links

Update the `href` attributes in social links:
```html
<a href="https://github.com/yourusername" class="social-link">
<a href="https://linkedin.com/in/yourusername" class="social-link">
<a href="https://twitter.com/yourusername" class="social-link">
<a href="mailto:your.email@example.com" class="social-link">
```

### Skills

Add or remove skills in the skills section by editing the skill tags:
```html
<span class="skill-tag">Your Skill</span>
```

### Projects

For each project, update:
- Project title
- Project description
- Technologies used (tags)
- Live demo link
- Source code link
- Replace the placeholder icon with actual project images

### Color Scheme

Modify the color variables in `styles.css`:
```css
:root {
    --primary-color: #3b82f6;
    --secondary-color: #8b5cf6;
    --dark-color: #1e293b;
    --light-color: #f8fafc;
}
```

## Deployment

### GitHub Pages

1. Go to your repository settings
2. Navigate to "Pages" section
3. Select the branch (usually `main`) and folder (root `/`)
4. Click "Save"
5. Your portfolio will be available at `https://yourusername.github.io/repository-name`

### Netlify

1. Sign up at [Netlify](https://www.netlify.com/)
2. Click "New site from Git"
3. Connect your GitHub repository
4. Deploy!

### Vercel

1. Sign up at [Vercel](https://vercel.com/)
2. Import your GitHub repository
3. Deploy with one click

## File Structure

```
praeator.portfolio/
├── index.html      # Main HTML file with all content
├── styles.css      # All styling and responsive design
├── script.js       # Interactive features and animations
└── README.md       # This file
```

## Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- Vanilla JavaScript
- Font Awesome Icons (CDN)

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

Feel free to use this template for your personal portfolio. No attribution required.

## Contact Form Integration

The contact form currently shows a success message. To make it functional, integrate with:
- [Formspree](https://formspree.io/)
- [EmailJS](https://www.emailjs.com/)
- Your own backend API

Example with Formspree:
```html
<form action="https://formspree.io/f/your-form-id" method="POST">
```

## Tips

- Add real project screenshots to replace placeholder icons
- Customize the color scheme to match your brand
- Add your actual projects with real descriptions
- Include links to live demos and source code
- Test on multiple devices before deploying
- Update the favicon for a professional touch

## Support

If you encounter any issues or have questions, feel free to open an issue in this repository.

---

Made with ❤️ for showcasing your awesome work!
