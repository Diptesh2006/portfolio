# Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. Designed to showcase your projects, skills, and professional experience.

## Features

- 🎨 Modern and clean design
- 📱 Fully responsive (mobile, tablet, desktop)
- ⚡ Smooth animations and transitions
- 🎯 Easy to customize
- 🚀 Optimized for performance
- ♿ Accessible design

## Sections

1. **Hero** - Introduction with your name, title, and social links
2. **About** - Personal information and technologies you work with
3. **Skills** - Technical skills organized by category
4. **Projects** - Featured projects with descriptions and links
5. **Contact** - Get in touch section with social media links

## Customization

### Personal Information

1. **Name and Title**: Update in `index.html`
   - Line ~40: Change "Your Name" to your actual name
   - Line ~41: Change "Full Stack Developer" to your title
   - Line ~42-45: Update the description

2. **Social Links**: Update in `index.html`
   - Replace placeholder URLs with your actual social media profiles
   - Update email address: `your.email@example.com`

3. **About Section**: Update in `index.html`
   - Modify the about text (lines ~95-105)
   - Update the technology list to match your skills

4. **Skills**: Update in `index.html`
   - Modify skill categories and items to match your expertise

5. **Projects**: Update in `index.html`
   - Replace project titles, descriptions, and technologies
   - Update project links (GitHub and live demo URLs)

6. **Colors**: Customize in `styles.css`
   - Modify CSS variables in `:root` (lines ~2-15)
   - Primary color, background colors, text colors, etc.

### Profile Image

Replace the placeholder icons with your actual profile images:
- Hero section: Add an `<img>` tag in the `.hero-image` div
- About section: Add an `<img>` tag in the `.image-wrapper` div

Example:
```html
<img src="path/to/your/image.jpg" alt="Your Name" />
```

## Deployment to GitHub Pages

### Method 1: Using GitHub Web Interface

1. Create a new repository on GitHub (or use an existing one)
2. Upload all files to the repository
3. Go to **Settings** → **Pages**
4. Under **Source**, select the branch (usually `main` or `master`)
5. Select the folder (usually `/ (root)`)
6. Click **Save**
7. Your site will be available at `https://yourusername.github.io/repository-name`

### Method 2: Using Git Command Line

1. Initialize git repository (if not already):
   ```bash
   git init
   ```

2. Add all files:
   ```bash
   git add .
   ```

3. Commit files:
   ```bash
   git commit -m "Initial commit: Portfolio website"
   ```

4. Add remote repository:
   ```bash
   git remote add origin https://github.com/yourusername/repository-name.git
   ```

5. Push to GitHub:
   ```bash
   git branch -M main
   git push -u origin main
   ```

6. Enable GitHub Pages:
   - Go to repository **Settings** → **Pages**
   - Select branch and folder
   - Save

### Custom Domain (Optional)

1. Add a `CNAME` file in the root directory with your domain name
2. Configure DNS settings with your domain provider
3. Update GitHub Pages settings to use custom domain

## File Structure

```
portfolio/
│
├── index.html          # Main HTML file
├── styles.css          # All styles and animations
├── script.js           # JavaScript for interactivity
├── .nojekyll          # Disable Jekyll processing
├── README.md          # This file
└── resume (1).pdf     # Your resume (optional)
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance Tips

- Optimize images before uploading (use WebP format when possible)
- Minimize custom fonts if loading time is a concern
- Consider using a CDN for external resources
- Enable GitHub Pages caching for faster load times

## License

This portfolio template is free to use for personal and commercial projects.

## Credits

- Fonts: [Google Fonts - Inter](https://fonts.google.com/specimen/Inter)
- Icons: [Font Awesome](https://fontawesome.com/)

---

Made with ❤️ for showcasing your work

