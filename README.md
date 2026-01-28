# Personal Portfolio Website

A modern, visually striking portfolio website for a cloud-first software engineer with immersive UI design.

## Features

- **Dark Theme**: Clean dark design with vibrant gradient accents
- **Responsive**: Fully responsive for desktop, tablet, and mobile devices
- **Smooth Animations**: Subtle scroll animations and hover effects
- **Modern Design**: Gradient text, rounded cards, and contemporary typography
- **Sections**:
  - Hero with greeting and CTA buttons
  - Skills & Expertise with progress bars
  - Featured Projects with tech stacks
  - Blog/Articles section
  - Contact form

## Setup

1. Open `index.html` in your browser
2. Customize the content:
   - Replace `[Your Name]` with your actual name
   - Update `[email]` with your email address
   - Update GitHub and LinkedIn URLs
   - Modify project details and links
   - Adjust skill percentages

## Adding Your AI-Generated Portrait

To replace the placeholder with your Gemini AI-generated portrait:

1. Generate your portrait using Gemini AI
2. Save the image in the project folder (e.g., `portrait.jpg`)
3. In `script.js`, uncomment and update the line:
   ```javascript
   updatePortrait('portrait.jpg');
   ```

Or manually update the HTML in `index.html`:
```html
<div class="image-placeholder" id="portrait">
    <img src="portrait.jpg" alt="Professional Portrait" style="width: 100%; height: 100%; object-fit: cover; border-radius: 50%;">
</div>
```

## Customization

- **Colors**: Edit CSS variables in `styles.css` under `:root`
- **Content**: Update text in `index.html`
- **Animations**: Modify animation timings in `styles.css`
- **Form Backend**: Connect the contact form to your backend in `script.js`

## Technologies Used

- HTML5
- CSS3 (Custom Properties, Grid, Flexbox)
- Vanilla JavaScript
- Font Awesome Icons

## Browser Support

Works on all modern browsers (Chrome, Firefox, Safari, Edge)
