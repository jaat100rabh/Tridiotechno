# Tridiotech

A modern, responsive educational platform website that showcases courses, AI training programs, real-world projects, and mentorship opportunities for students and professionals.

## 🌟 About

Tridiotech is a next-generation learning and innovation platform founded by Saurabh Kumar Singh. Our mission is to empower students with practical skills, AI-driven learning, real-world project experience, and industry-focused mentorship. We help learners transform their ideas into impactful projects, build strong portfolios, earn certifications, and prepare for successful careers in technology.

## ✨ Features

- **Responsive Design**: Fully responsive layout optimized for desktop, tablet, and mobile devices (Android, iOS)
- **Modern UI/UX**: Beautiful gradient backgrounds, glassmorphism effects, and smooth animations
- **Dark/Light Mode**: Toggle between dark and light themes for comfortable viewing
- **Interactive Navigation**: Full-screen hamburger menu for mobile devices
- **Course Showcase**: Display of multiple course programs including:
  - Full Stack Java Development Program
  - Full Stack Python Project Program
  - AI Tools Mastery Program
- **Skills Section**: Highlights essential skills participants receive
- **About Section**: Company information with statistics and team details
- **FAQ Section**: Interactive accordion-style frequently asked questions
- **Contact Section**: Easy access to email and WhatsApp communication
- **Smooth Scrolling**: Anchor navigation with proper header offset
- **Footer**: Comprehensive footer with links, services, and contact information

## 🚀 Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: 
  - Flexbox and CSS Grid for layout
  - Media queries for responsive design
  - CSS variables for theming
  - Glassmorphism effects
  - Animations and transitions
- **JavaScript (Vanilla)**:
  - Dark/Light mode toggle
  - Hamburger menu functionality
  - FAQ accordion
  - Scroll-to-top button
  - Canvas animations (particles, rain drops to rose petals)
- **Responsive Units**: rem, %, vw, vh for scalable design

## 📱 Responsive Breakpoints

- **Desktop**: 1025px and above
- **Tablet**: 768px - 1024px
- **Mobile**: 320px - 767px
- **Small Mobile**: 480px and below

## 🎨 Design Highlights

- **Color Scheme**: 
  - Primary: Blue and purple gradients
  - Light Mode: Teal and mint backgrounds
  - Dark Mode: Dark gray backgrounds
- **Typography**: Segoe UI font family with responsive sizing
- **Animations**: 
  - Electric glow effects on cards
  - Particle background animations
  - Rain drop to rose petal transitions
  - Smooth hover effects

## 📁 Project Structure

```
tridiotechno/
├── index.html          # Main HTML file containing all content
├── logo.png           # Company logo
├── trio.png           # About section image
└── one.mp4            # Background video
```

## 🛠️ How to Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/jaat100rabh/Tridiotech.git
   cd Tridiotech
   ```

2. **Open the website**:
   - Simply open `index.html` in any modern web browser
   - Or use a local server:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js (if you have http-server installed)
     npx http-server
     ```
   - Navigate to `http://localhost:8000`

## 📧 Contact Information

- **Email**: tridiotech@gmail.com
- **WhatsApp**: +91 8650115781
- **Founder**: Saurabh Kumar Singh

## 🌐 Sections Overview

1. **Hero Section**: Professional introduction with company branding
2. **Founder Section**: Meet the visionaries behind Tridiotech
3. **Courses Section**: Detailed course offerings with features and outcomes
4. **Skills Section**: Essential skills every participant receives
5. **About Section**: Company mission, vision, and statistics
6. **FAQ Section**: Common questions and answers
7. **Contact Section**: Direct communication channels
8. **Footer**: Navigation links, services, and contact information

## 🎯 Key Features Implementation

### Mobile Responsiveness
- Full-screen hamburger menu with centered navigation items
- Stacked card layouts on mobile devices
- Optimized font sizes and spacing for small screens
- Touch-friendly buttons and links
- No horizontal overflow

### Accessibility
- Proper semantic HTML structure
- ARIA labels where appropriate
- Keyboard navigation support
- High contrast ratios in both light and dark modes

### Performance
- Optimized CSS with minimal external dependencies
- Efficient JavaScript without heavy frameworks
- Smooth animations using CSS transforms
- Lazy loading considerations for images

## 🔧 Customization

### Changing Colors
Modify the CSS variables and gradient values in the `<style>` section of `index.html`:

```css
:root {
    --navbar-height: 80px;
}
```

### Adding New Courses
Duplicate the `.electric-card` structure in the HTML and update the content accordingly.

### Modifying FAQ Items
Add new `.faq-item` elements with `.faq-question` and `.faq-answer` content.

## 📄 License

This project is owned and maintained by Tridiotech. All rights reserved.

## 🙏 Acknowledgments

- Designed and developed for Tridiotech
- Founder: Saurabh Kumar Singh
- Built with modern web technologies for optimal performance and user experience

---

**Tridiotech** - Empowering the next generation of tech professionals with practical skills and real-world experience.
