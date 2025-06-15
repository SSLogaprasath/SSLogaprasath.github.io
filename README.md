# S S Loga Prasath - Portfolio Website

A modern, responsive portfolio website showcasing my skills, projects, and experience as a B.Tech AI & ML student and aspiring Software Developer.

## 🌟 Features

- **Responsive Design**: Fully responsive layout that works seamlessly across desktop, tablet, and mobile devices
- **Dark/Light Theme**: Automatic theme switching based on user's system preference
- **Interactive Contact Form**: Functional contact form with EmailJS integration
- **Smooth Animations**: Engaging animations and scroll effects for better user experience
- **Modern UI**: Clean, professional design with glassmorphism and gradient effects
- **Performance Optimized**: Lightweight and fast-loading website

## 🚀 Live Demo

[View Live Portfolio](https://sslogaprasath.github.io/portfolio) <!-- Replace with your actual GitHub Pages URL -->

## 📸 Screenshots

### Desktop View
![Desktop View](screenshots/desktop-view.png) <!-- Add screenshots when available -->

### Mobile View
![Mobile View](screenshots/mobile-view.png) <!-- Add screenshots when available -->

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with CSS custom properties, Grid, Flexbox
- **JavaScript (ES6+)**: Interactive functionality and animations
- **EmailJS**: Contact form email integration
- **Font Awesome**: Icons and visual elements
- **GitHub Pages**: Hosting and deployment

## 📂 Project Structure

```
portfolio/
├── index.html              # Main HTML file
├── images/                 # Image assets
│   └── profile.jpg        # Profile image
├── screenshots/           # Screenshots for README
├── README.md             # Project documentation
└── LICENSE               # MIT License
```

## 🎨 Sections

1. **Hero Section**: Introduction with profile image and social links
2. **About Me**: Personal information and contact details
3. **Projects**: Showcase of key projects with GitHub links
4. **Skills**: Technical skills organized by categories
5. **Certifications**: Academic achievements and professional certifications
6. **Contact**: Interactive contact form with EmailJS integration

## 🔧 Setup & Installation

### Prerequisites
- Web browser (Chrome, Firefox, Safari, Edge)
- Text editor (VS Code, Sublime Text, etc.)
- Git (for version control)

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/SSLogaprasath/portfolio.git
   cd portfolio
   ```

2. **Open in browser**
   - Simply open `index.html` in your preferred web browser
   - Or use a local server (recommended):
   
   **Using Python:**
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Python 2
   python -m SimpleHTTPServer 8000
   ```
   
   **Using Node.js (http-server):**
   ```bash
   npx http-server
   ```
   
   **Using VS Code Live Server extension:**
   - Install Live Server extension
   - Right-click on `index.html`
   - Select "Open with Live Server"

3. **Access locally**
   - Open `http://localhost:8000` in your browser

## ⚙️ Configuration

### EmailJS Setup (Contact Form)

1. Create an account at [EmailJS](https://www.emailjs.com/)
2. Create a new email service
3. Create an email template
4. Update the configuration in `index.html`:

```javascript
// Replace these IDs with your actual EmailJS configuration
emailjs.init("YOUR_PUBLIC_KEY");

emailjs.send('YOUR_SERVICE_ID', 'YOUR_TEMPLATE_ID', {
    from_name: name,
    from_email: email,
    subject: subject,
    message: message,
    to_email: 'your-email@gmail.com'
})
```

### Customization

#### Personal Information
Update the following sections in `index.html`:
- Profile image: Replace `images/profile.jpg`
- Name and title in hero section
- About me content
- Contact information
- Social media links

#### Projects
Add/modify projects in the projects section:
```html
<div class="project-card">
    <div class="project-icon">
        <i class="fas fa-your-icon"></i>
    </div>
    <h3>Your Project Title</h3>
    <p>Project description</p>
    <a href="your-github-link" class="project-link" target="_blank">
        View on GitHub <i class="fas fa-external-link-alt"></i>
    </a>
</div>
```

#### Skills
Update the skills section with your technologies:
```html
<div class="skill-tags">
    <span class="skill-tag">Your Skill</span>
    <!-- Add more skills -->
</div>
```

## 🎨 Color Scheme

The website uses CSS custom properties for easy theme customization:

```css
:root {
    --accent-primary: #1976d2;    /* Primary blue */
    --accent-secondary: #42a5f5;  /* Secondary blue */
    --bg-primary: linear-gradient(135deg, #e3f2fd 0%, #ffffff 100%);
    /* ... other colors */
}
```

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px
- **Small Mobile**: Below 480px

## 🚀 Deployment

### GitHub Pages

1. **Push to GitHub**
   ```bash
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```

2. **Enable GitHub Pages**
   - Go to repository Settings
   - Scroll to Pages section
   - Select source branch (usually `main`)
   - Your site will be available at `https://your-username.github.io/repository-name`

### Other Hosting Options

- **Netlify**: Drag and drop the folder or connect GitHub repository
- **Vercel**: Import GitHub repository
- **Firebase Hosting**: Use Firebase CLI to deploy

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 About the Developer

**S S Loga Prasath**
- 🎓 B.Tech AI & ML Student (2026 Graduate)
- 💼 Aspiring Software Developer
- 🌍 Tamil Nadu, India
- 📧 logaprasathss@gmail.com

### Connect with me:
- [GitHub](https://github.com/SSLogaprasath)
- [LinkedIn](https://www.linkedin.com/in/loga-prasath-s-s-51ab21363/)

## 🙏 Acknowledgments

- Font Awesome for the beautiful icons
- EmailJS for contact form functionality
- Google Fonts for typography
- All the open-source community for inspiration

---

⭐ Star this repository if you found it helpful!

**Made with ❤️ by Loga Prasath**
