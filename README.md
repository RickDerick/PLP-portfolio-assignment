# Derick Haron's Portfolio

A modern, responsive personal portfolio website showcasing my skills, projects, and professional experience as a Full Stack Software Developer.

## 🌟 Overview

This portfolio website presents my professional journey, technical skills, and notable projects in web development. Built with clean HTML5, CSS3, and responsive design principles, it demonstrates my expertise in front-end development and user experience design. here is the link to the live site after hosting it on netlify
https://plp-derickharon-portfolio.netlify.app/

## 🚀 Features

- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Modern Layout**: Clean, professional design with intuitive navigation
- **Accessibility**: ARIA labels and semantic HTML for screen reader compatibility
- **Performance Optimized**: Lightweight and fast-loading
- **Contact Form**: Integrated contact form using Formspree
- **Project Showcase**: Detailed presentation of key projects with live links
- **CV Download**: Direct download link for resume/CV

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with Flexbox and responsive design
- **Formspree**: Contact form handling
- **Responsive Design**: Mobile-first approach with media queries

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # External CSS stylesheet
├── my_Revamped_CV.pdf  # Downloadable CV/Resume
└── README.md           # Project documentation
```

## 🎨 Design Features

### Color Scheme
- Primary: `#1a3c34` (Dark Green)
- Accent: `#e67e22` (Orange)
- Background: `#f4f4f4` (Light Gray)
- Text: `#333` (Dark Gray)

### Layout Sections
1. **Header**: Name and title with professional branding
2. **Navigation**: Smooth scrolling navigation menu
3. **About**: Professional summary and background
4. **Skills**: Technical skills showcase
5. **Education**: Academic background
6. **Interests**: Professional interests and goals
7. **Projects**: Featured project portfolio with live links
8. **Contact**: Contact form and information
9. **Footer**: Copyright and additional info

## 🚀 Getting Started

### Prerequisites
- Web browser (Chrome, Firefox, Safari, Edge)
- Text editor (VS Code, Sublime Text, etc.) for modifications

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/RickDerick/PLP-portfolio-assignment.git
   ```

2. **Navigate to project directory**
   ```bash
   cd portfolio
   ```

3. **Open in browser**
   - Double-click `index.html`, or
   - Open with Live Server extension in VS Code, or
   - Serve with any local web server

### Local Development

For development with live reload:

1. **Using VS Code Live Server**
   - Install Live Server extension
   - Right-click `index.html` → "Open with Live Server"

2. **Using Python HTTP Server**
   ```bash
   python -m http.server 8000
   ```
   Then visit `http://localhost:8000`

3. **Using Node.js HTTP Server**
   ```bash
   npx http-server
   ```

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

## 🌐 Featured Projects

### 1. Membership Portal
- **Tech Stack**: Vue.js, Laravel
- **Features**: User authentication, profile management, subscription handling
- **Live Demo**: [member.ihrm.kinetics.solutions](https://member.ihrm.kinetics.solutions/)

### 2. Employee Self-Service (ESS) System
- **Tech Stack**: Vue.js, Laravel, Microsoft Dynamics
- **Features**: HR management, payroll integration, leave management
- **Live Demo**: [self.kinetics.technology](https://self.kinetics.technology/)

### 3. Football Tryouts Management System
- **Tech Stack**: Web-based platform
- **Features**: Player registration, performance tracking, mobile-friendly
- **Live Demo**: [soccernet.gojjoapps.com](https://soccernet.gojjoapps.com/)

### 4. AI-Powered Learning Platform
- **Tech Stack**: Vue.js, AI integration
- **Features**: YouTube video lessons, AI-generated questions, progress tracking
- **Live Demo**: [coursarium.com](https://coursarium.com/)

## 📧 Contact Form Setup

The contact form uses [Formspree](https://formspree.io/) for form handling. To set up:

1. Sign up at [formspree.io](https://formspree.io/)
2. Create a new form
3. Replace `your-form-id` in the form action URL with your actual form ID:
   ```html
   <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```

## 🎯 Performance Optimizations

- **Minimal Dependencies**: No external frameworks for faster loading
- **Optimized Images**: (Add when implementing)
- **CSS Optimization**: Efficient selectors and minimal redundancy
- **Semantic HTML**: Better SEO and accessibility

## 🔧 Customization

### Updating Content
1. **Personal Information**: Edit the header and about sections in `index.html`
2. **Skills**: Modify the skills section to reflect your technologies
3. **Projects**: Update project details and links
4. **Styling**: Customize colors and layout in `styles.css`

### Adding New Sections
1. Add new section HTML in `index.html`
2. Add corresponding navigation link
3. Style the new section in `styles.css`
4. Ensure responsive design considerations

## 📈 Future Enhancements

- [ ] Add animations and transitions
- [ ] Implement dark/light theme toggle
- [ ] Add blog section
- [ ] Include testimonials section
- [ ] Add image gallery for projects
- [ ] Implement JavaScript interactions
- [ ] Add progressive web app features

## 🤝 Contributing

While this is a personal portfolio, suggestions and improvements are welcome:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -am 'Add some improvement'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Derick Haron**
- Full Stack Software Developer
- Location: Nairobi, Kenya
- Portfolio: [Your Portfolio URL]
- GitHub: [@RickDerick](https://github.com/RickDerick)

## 🙏 Acknowledgments

- Inspired by modern web design principles
- Built during PLP Web Development Hackathon
- Thanks to the open-source community for tools and resources

---

⭐ If you found this portfolio helpful, please consider giving it a star!
