# Avinash Shinde - Portfolio Website

A modern, responsive portfolio website showcasing professional experience, skills, and projects. Built with clean HTML, CSS, and JavaScript featuring a premium dark/light theme toggle and smooth animations.

![Portfolio Preview](SA.png)

## 🌟 Features

- **Responsive Design**: Fully responsive layout that works seamlessly across all devices (desktop, tablet, mobile)
- **Dark/Light Theme Toggle**: Smooth theme switching with persistent user preference
- **Modern UI/UX**: Premium design with gradient accents, glassmorphism effects, and micro-animations
- **Interactive Elements**: Hover effects, smooth scrolling, and animated transitions
- **Project Showcase**: Detailed project cards with modal popups for comprehensive information
- **Professional Timeline**: Visual timeline for experience and education
- **Skills Section**: Organized skill cards with categorized technologies
- **Contact Form**: Integrated contact section for easy communication

## 🎨 Design Highlights

- **Color Scheme**: Dynamic gradient-based design with purple-blue accent colors
- **Typography**: Clean, modern fonts with proper hierarchy
- **Animations**: Smooth fade-in, slide-up, and hover animations
- **Glassmorphism**: Backdrop blur effects for modern card designs
- **Floating Shapes**: Animated background elements for visual interest

## 🛠️ Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Advanced styling with CSS variables, flexbox, grid, and animations
- **JavaScript**: Interactive features and theme management
- **No Dependencies**: Pure vanilla JavaScript - no frameworks or libraries required

## 📂 Project Structure

```
portfolio website/
├── index.html          # Main HTML file with all content
├── SA.png             # Profile image and favicon
├── avinash.jpg        # Additional profile image
└── README.md          # Project documentation
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No build tools or dependencies required

### Installation

1. Clone or download this repository:
   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```bash
   cd "portfolio website"
   ```

3. Open `index.html` in your web browser:
   - Double-click the file, or
   - Right-click and select "Open with" your preferred browser, or
   - Use a local development server (optional)

### Using a Local Server (Optional)

For the best experience, you can use a local development server:

**Using Python:**
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

**Using Node.js (http-server):**
```bash
npx http-server -p 8000
```

Then open `http://localhost:8000` in your browser.

## 📱 Sections

### 1. **Hero Section**
- Professional introduction
- Profile image with gradient border
- Call-to-action buttons
- Animated floating shapes background

### 2. **About Section**
- Professional summary
- Key statistics (Experience, Projects, Technologies)
- Responsive grid layout

### 3. **Skills Section**
- Categorized skill cards:
  - Programming Languages
  - Web Technologies
  - Databases
  - Frameworks & Tools
  - Concepts
- Interactive tag elements

### 4. **Experience Section**
- Professional timeline
- Detailed role descriptions
- Key achievements and responsibilities
- Company and client information

### 5. **Projects Section**
- Featured project cards
- Technology stack badges
- Project descriptions
- Links to code, demos, and detailed information
- Modal popups with comprehensive project details

### 6. **Education Section**
- Academic timeline
- Degree information
- Institution details

### 7. **Contact Section**
- Contact form
- Social media links
- Professional email

## 🎯 Key Features Explained

### Theme Toggle
The website supports both dark and light themes:
- Theme preference is saved in localStorage
- Smooth transitions between themes
- Custom CSS variables for easy theme management
- Animated toggle button with rotation effect

### Project Modals
Each project has a detailed modal with:
- Project overview
- Key features
- Technologies used
- Challenges and solutions
- Links to GitHub, live demo, and video walkthrough

### Responsive Navigation
- Fixed navigation bar with scroll effects
- Smooth scrolling to sections
- Active state indicators
- Mobile-friendly design

## 🎨 Customization

### Changing Colors
Edit the CSS variables in the `:root` section of `index.html`:

```css
:root {
    --primary: #1A202C;
    --secondary: #2D3748;
    --accent: #3182CE;
    --gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    /* ... more variables */
}
```

### Updating Content
All content is in `index.html`. Simply edit the HTML to update:
- Personal information
- Skills
- Projects
- Experience
- Education

### Adding New Projects
Copy an existing project card structure and modify:

```html
<div class="project-card">
    <div class="project-badge">Category • Type</div>
    <h3>Project Name</h3>
    <p>Project description...</p>
    <div class="project-tags">
        <span class="tag">Technology</span>
        <!-- Add more tags -->
    </div>
    <div class="project-buttons">
        <a href="#" class="btn-project">Code</a>
        <button class="btn-project btn-project-primary">Details</button>
    </div>
</div>
```

## 📊 Performance

- **Lightweight**: Single HTML file with embedded CSS and JavaScript
- **Fast Loading**: No external dependencies or frameworks
- **Optimized**: Minimal DOM manipulation and efficient CSS
- **Smooth Animations**: Hardware-accelerated CSS transitions

## 🌐 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Opera (latest)

## 📄 License

This project is open source and available for personal and commercial use.

## 👤 Author

**Avinash Shinde**
- Junior ColdFusion Developer at Cognizant Technology Solutions
- Client: Suncorp Bank, Australia
- Experience: Dec 2021 - Present

## 🔗 Links

- **GitHub**: [Shinde-Avinash](https://github.com/Shinde-Avinash)
- **LinkedIn**: [Connect on LinkedIn](https://www.linkedin.com/in/avinash-shinde-/)
- **Email**: avinash.shinde@example.com

## 🙏 Acknowledgments

- Design inspiration from modern portfolio trends
- Gradient color schemes from UI/UX best practices
- Icons and visual elements created with CSS

---

**Note**: This is a static portfolio website. For dynamic features or backend integration, consider adding a backend framework or CMS.

## 📝 Future Enhancements

- [ ] Add blog section
- [ ] Integrate analytics
- [ ] Add more project case studies
- [ ] Implement contact form backend
- [ ] Add testimonials section
- [ ] Create downloadable resume feature
- [ ] Add language switcher (i18n)
- [ ] Implement progressive web app (PWA) features

---

Made with ❤️ by Avinash Shinde
