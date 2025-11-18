# Geetu's Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. This portfolio showcases professional experience, education, skills, and projects in an elegant and user-friendly design.

## 🌟 Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean and professional design with smooth animations
- **Interactive Navigation**: Smooth scrolling and active section highlighting
- **Sections Include**:
  - Hero section with introduction
  - About me with statistics
  - Work experience timeline
  - Education background
  - Skills and technologies
  - Featured projects showcase
  - Contact form
  - Downloadable resume

## 🚀 Deployment to GitHub Pages

Follow these steps to deploy your portfolio website to GitHub Pages:

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the "+" icon in the top right and select "New repository"
3. Name your repository: `yourusername.github.io` (replace `yourusername` with your actual GitHub username)
   - For example, if your username is `john-doe`, name it `john-doe.github.io`
4. Make the repository **Public**
5. Click "Create repository"

### Step 2: Push Your Code to GitHub

Open your terminal/command prompt in the portfolio folder and run:

```bash
# Initialize git repository
git init

# Add all files
git add .

# Commit your files
git commit -m "Initial portfolio website commit"

# Add your GitHub repository as remote (replace with your actual repository URL)
git remote add origin https://github.com/yourusername/yourusername.github.io.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on "Settings" tab
3. Scroll down to "Pages" section in the left sidebar
4. Under "Source", select "Deploy from a branch"
5. Under "Branch", select `main` and folder `/ (root)`
6. Click "Save"

### Step 4: Access Your Website

After a few minutes, your website will be live at:
```
https://yourusername.github.io
```

## 📝 Customization Guide

### Update Personal Information

1. **Open `index.html`** and update:
   - Your name in the hero section
   - Professional title and tagline
   - About me content
   - Work experience details
   - Education information
   - Skills and technologies
   - Project details
   - Contact information
   - Social media links (GitHub, LinkedIn, Twitter, Email)

2. **Update Contact Form**:
   - Sign up for a free account at [Formspree](https://formspree.io/)
   - Replace `your-form-id` in the form action with your Formspree form ID:
     ```html
     <form action="https://formspree.io/f/your-form-id" method="POST">
     ```

3. **Add Your Profile Picture**:
   - Replace the placeholder image URL in the About section:
     ```html
     <img src="path/to/your/photo.jpg" alt="Profile Picture">
     ```

4. **Add Project Screenshots**:
   - Replace placeholder images in the Projects section with your actual project screenshots

### Customize Colors

Open `styles.css` and modify the CSS variables at the top:

```css
:root {
    --primary-color: #3b82f6;    /* Change to your preferred primary color */
    --secondary-color: #8b5cf6;  /* Change to your preferred secondary color */
    /* ... other colors */
}
```

### Add More Sections

You can add more sections by following the existing HTML structure pattern in `index.html`.

## 📁 File Structure

```
portfolio/
│
├── index.html              # Main HTML file
├── styles.css              # Stylesheet
├── script.js               # JavaScript functionality
├── Geetu _Resume_Job ID 7566.pdf  # Your resume PDF
└── # Geetu Ayyappan - Professional Portfolio Website

A modern, responsive portfolio website showcasing the professional experience, skills, and qualifications of Geetu Ayyappan, a Training & Facilitation Specialist with HR expertise.

## 🌟 Features

- **Responsive Design**: Fully responsive layout that works seamlessly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations and transitions
- **Interactive Navigation**: Smooth scrolling navigation with active link highlighting
- **Mobile Menu**: Hamburger menu for mobile devices with smooth slide-in effect
- **Animated Sections**: Fade-in animations triggered as users scroll through content
- **Skill Visualization**: Animated progress bars for technical and soft skills
- **Professional Timeline**: Visual timeline showcasing career progression
- **Contact Information**: Easy-to-access contact details with social media links
- **Performance Optimized**: Debounced scroll handlers and intersection observers for optimal performance
- **Accessibility**: Keyboard navigation support and ARIA labels for screen readers

## 📁 Project Structure

```
GeetuPortfolio/
│
├── index.html          # Main HTML file with semantic structure
├── styles.css          # Complete CSS styling with animations
├── script.js           # Interactive JavaScript functionality
└── README.md          # Project documentation
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No build tools or dependencies required - pure HTML, CSS, and JavaScript

### Installation

1. Clone or download this repository
2. Open `index.html` in your web browser
3. That's it! The website is ready to view

### Local Development

Simply open the `index.html` file in your preferred web browser:

```bash
# On Windows (using PowerShell)
start index.html

# Or double-click the index.html file in File Explorer
```

For live development with auto-refresh, you can use:
- VS Code Live Server extension
- Python's built-in server: `python -m http.server 8000`
- Node.js http-server: `npx http-server`

## 📄 Sections

### 1. **Hero Section**
- Eye-catching introduction with gradient background
- Call-to-action buttons
- Social media links

### 2. **About Section**
- Professional summary
- Key highlights (experience, certifications, languages)
- Core competencies

### 3. **Experience Section**
- Timeline-based career history
- Detailed role descriptions
- Key achievements and responsibilities

### 4. **Skills Section**
- Technical skills with progress bars
- Soft skills visualization
- Core competencies tags
- Language proficiency

### 5. **Education Section**
- Academic qualifications
- Professional certifications
- Current training (CHRL, French language)
- Live project experience

### 6. **Contact Section**
- Email, phone, and location information
- LinkedIn profile link
- Availability details

## 🎨 Customization

### Colors
Edit the CSS variables in `styles.css` to change the color scheme:

```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #7c3aed;
    --accent-color: #06b6d4;
    /* Add more custom colors */
}
```

### Content
Update content directly in `index.html`:
- Personal information
- Work experience
- Skills and competencies
- Education details
- Contact information

### Animations
Modify animation timings and effects in `styles.css` under the animations section.

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## 📱 Mobile Responsive

The website is fully responsive with breakpoints at:
- Desktop: 1200px and above
- Tablet: 768px - 1199px
- Mobile: 320px - 767px

## ⚡ Performance Features

- Debounced scroll event handlers
- Intersection Observer API for lazy animations
- Optimized CSS with hardware acceleration
- Minimal external dependencies

## 🔧 Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with flexbox, grid, and animations
- **JavaScript (ES6+)**: Interactive features and DOM manipulation
- **Font Awesome**: Icon library (loaded via CDN)

## 📞 Contact Information

**Geetu Ayyappan**
- Email: geetuatwork@gmail.com
- Phone: +1 (437) 933-3735
- LinkedIn: [linkedin.com/in/geetua](https://linkedin.com/in/geetua)
- Location: Scarborough, ON, Canada

## 📝 License

This is a personal portfolio website. All rights reserved.

## 🤝 Contributing

This is a personal portfolio project, but suggestions and feedback are welcome!

## 📈 Future Enhancements

Potential features to add:
- [ ] Dark mode toggle
- [ ] Contact form with backend integration
- [ ] Blog section
- [ ] Testimonials slider
- [ ] Project portfolio gallery
- [ ] Downloadable resume PDF
- [ ] Multi-language support (English/French)

## 🙏 Acknowledgments

- Font Awesome for icons
- Google Fonts (if added)
- Inspiration from modern portfolio designs

---

**Built with ❤️ by Geetu Ayyappan**

*Last Updated: November 2025*               # This file
```

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)
- Font Awesome Icons
- Google Fonts

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📞 Support

If you encounter any issues or have questions, feel free to:
- Open an issue in the GitHub repository
- Contact me through the contact form on the website

## 📄 License

This project is open source and available for personal use. Feel free to customize it for your own portfolio!

## 🙏 Acknowledgments

- Icons provided by [Font Awesome](https://fontawesome.com/)
- Inspiration from various portfolio designs across the web

---

**Note**: Remember to update all placeholder content with your actual information before deploying!

## Quick Checklist Before Deployment

- [ ] Updated all personal information (name, title, bio)
- [ ] Added real work experience
- [ ] Added real education details
- [ ] Updated skills section
- [ ] Added actual projects with links
- [ ] Updated contact information
- [ ] Added real social media links
- [ ] Set up Formspree for contact form
- [ ] Added profile picture
- [ ] Added project screenshots
- [ ] Tested on mobile devices
- [ ] Tested all links
- [ ] Resume PDF is accessible

Enjoy your new portfolio website! 🎉
