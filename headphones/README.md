# Headphones Website

A responsive headphone company website built from scratch using HTML and CSS as part of the ALX Frontend Development program.

## 📋 Project Overview

This project implements a fully responsive website for a headphone company based on a Figma design. The website showcases modern web development practices with clean code, semantic HTML, and responsive design principles.

## 🎯 Learning Objectives

- Implement a design from scratch without external frameworks
- Create responsive layouts using CSS Grid and Flexbox
- Apply CSS animations and hover effects
- Build mobile-first responsive design
- Use semantic HTML5 elements
- Implement accessibility best practices

## 🛠️ Technologies Used

- **HTML5** - Semantic markup structure
- **CSS3** - Styling, layouts, animations, and responsive design
- **No external frameworks** - Vanilla CSS only
- **No JavaScript** - Pure HTML/CSS implementation (minimal JS for navigation)

## 📁 Project Structure

```
headphones/
├── README.md
├── 0-index.html          # Main HTML file with embedded CSS
├── 1-index.html          # Header/Hero section
├── 2-index.html          # "What we do" section  
├── 3-index.html          # "Our results" section
├── 4-index.html          # Contact us section
├── 5-index.html          # Footer section
├── 6-index.html          # Replace background image with code
├── 7-index.html          # Add animations
├── 8-index.html          # Add hamburger menu
├── images/
│   ├── logo_headphones.png
│   ├── favicon.ico
│   └── [background images]
└── fonts/
    ├── source-sans-pro.woff2
    └── spin-cycle-ot.woff
```

## ✨ Features

### 🎨 Design Features
- **Responsive Layout** - Mobile-first design with 480px breakpoint
- **Custom Animations** - Smooth transitions and hover effects
- **Pentagon Shapes** - CSS clip-path for results section
- **Modern Typography** - Custom fonts (Source Sans Pro, Spin Cycle OT)
- **Color Scheme** - Primary: #FF6565, Background: #071629

### 📱 Responsive Features
- **Desktop** - Full layout with navigation bar
- **Mobile (≤480px)** - Hamburger menu, stacked layout
- **Flexible Grid** - Auto-fitting columns for services and results
- **Scalable Typography** - Responsive font sizes

### 🎯 Interactive Features
- **Hover Effects** - Links change color to #FF6565
- **Button Animations** - Opacity and transform effects
- **Smooth Scrolling** - Navigation links scroll to sections
- **Mobile Menu** - Hamburger menu toggle

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Text editor (VS Code, Atom, Sublime Text)
- Basic knowledge of HTML/CSS

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/alx_html_css.git
   cd alx_html_css/headphones
   ```

2. **Download required assets**
   - Add `logo_headphones.png` to `/images/` folder
   - Add font files to `/fonts/` folder
   - Add background images as needed

3. **Open in browser**
   ```bash
   open 0-index.html
   # or
   python3 -m http.server 8000
   ```

## 📐 Design Requirements

### Layout Specifications
- **Max width**: 1000px (centered)
- **Mobile breakpoint**: 480px or less
- **Content spacing**: Consistent padding and margins
- **Grid system**: CSS Grid and Flexbox

### Typography
- **Primary font**: Source Sans Pro
- **Secondary font**: Spin Cycle OT  
- **Responsive sizes**: Scale down on mobile
- **Line height**: 1.6 for body text

### Color Palette
```css
Primary Color:    #FF6565
Background Dark:  #071629  
Text Light:       #FFFFFF
Text Dark:        #071629
Muted Text:       #979797
```

## 📱 Responsive Behavior

### Desktop (>480px)
- Horizontal navigation menu
- 4-column grid for services
- 4-column grid for results
- Side-by-side footer elements

### Mobile (≤480px)
- Hamburger menu navigation
- Single column layout
- 2-column grid for results
- Stacked footer elements

## 🎨 CSS Features Used

### Modern CSS Techniques
- **CSS Grid** - For responsive layouts
- **Flexbox** - For alignment and spacing
- **CSS Custom Properties** - For maintainable code
- **Media Queries** - For responsive design
- **Clip-path** - For pentagon shapes
- **Transitions** - For smooth animations

### Animation Effects
```css
/* Hover effects */
.cta-button:hover {
    opacity: 0.9;
    transform: translateY(-2px);
}

/* Fade-in animations */
@keyframes fadeInUp {
    from { opacity: 0; transform: translateY(30px); }
    to { opacity: 1; transform: translateY(0); }
}
```

## ✅ Project Checklist

- [x] **Task 0**: Read and be familiar with Figma
- [x] **Task 1**: Header/Hero piece
- [x] **Task 2**: "What we do..." section  
- [x] **Task 3**: "Our results" section
- [x] **Task 4**: Contact us section
- [x] **Task 5**: Footer
- [x] **Task 6**: Replace background image with code
- [x] **Task 7**: Let's animate items
- [x] **Task 8**: Hamburger menu

## 🧪 Testing

### Browser Compatibility
- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+

### Responsive Testing
```bash
# Test different screen sizes
Desktop: 1200px+
Tablet:  768px - 1199px  
Mobile:  320px - 479px
```

### Validation
- HTML5 validation: [W3C Markup Validator](https://validator.w3.org/)
- CSS3 validation: [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)

## 🎓 Learning Outcomes

After completing this project, you will have learned:

- How to implement a design from a Figma file
- Responsive web design principles
- CSS Grid and Flexbox layouts
- CSS animations and transitions
- Mobile-first development approach
- Semantic HTML5 structure
- Cross-browser compatibility

## 📚 Resources

### Design Resources
- **Figma File**: [Headphone Company Design](figma-link)
- **Font Files**: Source Sans Pro, Spin Cycle OT
- **Icon Font**: Holberton School Icon Font

### Documentation
- [MDN Web Docs](https://developer.mozilla.org/)
- [CSS Grid Guide](https://css-tricks.com/snippets/css/complete-guide-grid/)
- [Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

## 🤝 Contributing

This is an educational project for ALX. If you're an ALX student:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -am 'Add some improvement'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Create a Pull Request

## 📝 License

This project is part of the ALX Software Engineering Program. For educational purposes only.

## 👨‍💻 Author

**Your Name**
- ALX Software Engineering Student
- GitHub: [@yourusername](https://github.com/yourusername)
- Email: your.email@example.com

## 🙏 Acknowledgments

- **ALX Team** - For the amazing curriculum
- **Holberton School** - For the design resources
- **Nicolas Philippot** - For the original Figma design
- **My Peers** - For collaboration and code reviews

---

⭐ **Star this repository if it helped you learn something new!**