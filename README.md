# Tsewang Lhamo - Personal Portfolio Website

A modern, responsive personal portfolio website showcasing my skills, experience, and projects as a Computer Science student and Product Management enthusiast.

## 🌟 Features

- **Modern Design**: Clean, professional design with smooth animations
- **Fully Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **Interactive Elements**: Smooth scrolling, hover effects, and form validation
- **Professional Sections**: Hero, About, Experience, Projects, Skills, and Contact
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Contact Form**: Functional contact form with validation
- **SEO Optimized**: Proper meta tags and semantic HTML

## 📁 File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
├── README.md           # This file
└── resume_text.txt     # Extracted resume content
```

## 🚀 Getting Started

1. **Open the website**: Simply open `index.html` in your web browser
2. **Local Development**: Use a local server for best experience:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Using PHP
   php -S localhost:8000
   ```

## 🎨 Customization

### Personal Information
Update the following sections in `index.html`:

- **Hero Section**: Name, title, and description
- **About Section**: Personal bio and statistics
- **Experience Section**: Work history and achievements
- **Projects Section**: Featured projects with descriptions
- **Skills Section**: Technical skills and tools
- **Contact Section**: Contact information

### Styling
Modify `styles.css` to customize:

- **Colors**: Update CSS variables for brand colors
- **Fonts**: Change font families and sizes
- **Layout**: Adjust spacing, grid layouts, and responsive breakpoints
- **Animations**: Modify transition effects and timing

### Functionality
Enhance `script.js` to add:

- **Form Integration**: Connect contact form to email service
- **Analytics**: Add Google Analytics or other tracking
- **Additional Animations**: Custom scroll effects and interactions
- **Dynamic Content**: Load content from external APIs

## 📱 Responsive Design

The website is fully responsive with breakpoints at:
- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and accessibility
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript (ES6+)**: Interactive functionality
- **Font Awesome**: Icons for visual elements
- **Google Fonts**: Inter font family for typography

## 📋 Sections Overview

### 1. Hero Section
- Eye-catching introduction with call-to-action buttons
- Gradient background with professional styling
- Profile placeholder (replace with your photo)

### 2. About Section
- Personal introduction and background
- Key statistics and achievements
- Education information card

### 3. Experience Section
- Timeline layout for work experience
- Detailed role descriptions and achievements
- Company information and dates

### 4. Projects Section
- Featured projects with descriptions
- Technology tags for each project
- Hover effects and animations

### 5. Skills Section
- Categorized skills (Programming, Tools, Core Skills)
- Interactive skill tags
- Professional presentation

### 6. Contact Section
- Contact information with icons
- Functional contact form
- Form validation and user feedback

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📈 Performance

- Optimized images and assets
- Minified CSS and JavaScript (for production)
- Efficient animations using CSS transforms
- Lazy loading for better performance

## 🚀 Deployment

### GitHub Pages
1. Create a new repository
2. Upload all files
3. Enable GitHub Pages in repository settings
4. Your site will be available at `https://username.github.io/repository-name`

### Netlify
1. Drag and drop the folder to Netlify
2. Your site will be deployed instantly
3. Custom domain can be added in settings

### Vercel
1. Connect your GitHub repository
2. Vercel will automatically deploy your site
3. Updates are deployed automatically on push

## 📞 Contact Form Setup

To make the contact form functional:

1. **EmailJS** (Recommended for beginners):
   ```javascript
   // Add EmailJS script to HTML
   <script src="https://cdn.jsdelivr.net/npm/@emailjs/browser@3/dist/email.min.js"></script>
   
   // Initialize EmailJS
   emailjs.init("YOUR_USER_ID");
   ```

2. **Formspree**:
   ```html
   <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```

3. **Netlify Forms**:
   ```html
   <form name="contact" netlify>
   ```

## 🎯 SEO Optimization

The website includes:
- Proper meta tags
- Semantic HTML structure
- Alt text for images
- Open Graph tags for social sharing
- Structured data markup

## 🔒 Privacy & Security

- No external tracking scripts (unless added)
- Form data handled securely
- HTTPS recommended for production
- GDPR compliant structure

## 📝 License

This portfolio template is free to use and modify for personal and commercial projects.

## 🤝 Contributing

Feel free to fork this project and customize it for your needs. If you make improvements, consider sharing them back!

## 📞 Support

If you need help customizing this portfolio or have questions, feel free to reach out!

---

**Built with ❤️ for showcasing professional achievements and skills** 