# Sami Abu Raaed - Portfolio Website

A modern, responsive portfolio website showcasing my skills, projects, and experience as a Junior Software Developer.

## 🚀 Features

- **Modern UI/UX Design**: Clean, professional design with smooth animations
- **Dark/Light Theme**: Toggle between dark and light modes with persistent preference
- **Fully Responsive**: Optimized for all devices (desktop, tablet, mobile)
- **Smooth Animations**: Scroll-triggered animations and interactive elements
- **Contact Form**: Functional contact form with validation
- **SEO Optimized**: Proper meta tags and semantic HTML
- **Performance Optimized**: Fast loading times and smooth interactions

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with CSS variables, Grid, and Flexbox
- **JavaScript (Vanilla)**: Interactive functionality without dependencies
- **Font Awesome**: Icons
- **Google Fonts**: Inter font family

## 📂 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # All CSS styles
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🎨 Sections

1. **Hero Section**: Introduction with name, title, and call-to-action buttons
2. **About Section**: Professional summary with stats and highlights
3. **Skills Section**: Technical skills organized by category with progress bars
4. **Projects Section**: Featured projects with descriptions and tech stacks
5. **Experience & Education**: Timeline of work experience and education
6. **Contact Section**: Contact information and form

## 🚀 Getting Started

### Option 1: Open Directly
Simply open `index.html` in your web browser.

### Option 2: Use Live Server (Recommended)
1. Install [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension in VS Code
2. Right-click on `index.html` and select "Open with Live Server"

### Option 3: Use Python HTTP Server
```bash
# Python 3
python -m http.server 8000

# Then open http://localhost:8000 in your browser
```

### Option 4: Use Node.js HTTP Server
```bash
# Install http-server globally
npm install -g http-server

# Run server
http-server

# Then open http://localhost:8080 in your browser
```

## 🎯 Customization

### Update Personal Information
Edit `index.html` to update:
- Name and title in the hero section
- About me text
- Skills and proficiency levels
- Projects and descriptions
- Work experience
- Contact information

### Change Colors
Edit CSS variables in `styles.css`:
```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #8b5cf6;
    --accent-color: #ec4899;
    /* ... more colors */
}
```

### Add/Remove Sections
Simply add or remove section blocks in `index.html` and update the navigation menu accordingly.

## 📧 Contact Form Integration

The contact form currently simulates submission. To make it functional, you can integrate with:

### Option 1: EmailJS (Recommended - Free)
1. Sign up at [EmailJS](https://www.emailjs.com/)
2. Create an email service and template
3. Uncomment and configure the EmailJS code in `script.js`
4. Add EmailJS SDK to `index.html`:
```html
<script src="https://cdn.jsdelivr.net/npm/@emailjs/browser@3/dist/email.min.js"></script>
```

### Option 2: Formspree
1. Sign up at [Formspree](https://formspree.io/)
2. Update the form action in `index.html`:
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

### Option 3: Backend API
Create your own backend API to handle form submissions.

## 🌐 Deployment

### GitHub Pages (Free)
1. Create a GitHub repository
2. Push your code to the repository
3. Go to Settings > Pages
4. Select the main branch as source
5. Your site will be live at `https://yourusername.github.io/repository-name`

### Netlify (Free)
1. Sign up at [Netlify](https://www.netlify.com/)
2. Drag and drop your project folder
3. Your site will be live instantly with a custom URL

### Vercel (Free)
1. Sign up at [Vercel](https://vercel.com/)
2. Import your GitHub repository
3. Deploy with one click

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## ⚡ Performance Tips

- Images are optimized for web
- CSS and JavaScript are minified for production
- Lazy loading for images
- Debounced scroll events
- Efficient animations using CSS transforms

## 🔧 Future Enhancements

- [ ] Add blog section
- [ ] Integrate with GitHub API to show live repositories
- [ ] Add testimonials section
- [ ] Create downloadable PDF resume
- [ ] Add more interactive animations
- [ ] Multi-language support
- [ ] Add analytics (Google Analytics)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Contact

**Sami Abu Raaed**
- Email: samiaburaed42@gmail.com
- Phone: +972 50-815-0047
- GitHub: [@sami1507](https://github.com/sami1507)
- LinkedIn: [Sami Abu Raaed](https://linkedin.com/in/sami-abu-raaed-89277b307)
- Location: Umm al-Fahm, Israel

---

**Built with ❤️ by Sami Abu Raaed**

*Last Updated: February 2026*
