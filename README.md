# Personal Portfolio Website

A responsive personal portfolio website built with HTML, CSS, and JavaScript as per the Web Technology assignment requirements.

## 🎯 Assignment Requirements Met

✅ **Technical Stack:**
- HTML for structure
- CSS for styling  
- JavaScript for interactivity

✅ **Portfolio Content:**
- Photo and Bio section
- Education background
- Experience (internships/jobs/volunteer)
- Projects (2+ with descriptions)
- Skills (technical skills with progress bars)
- Certificates & Awards
- Contact Information (phone, email, LinkedIn, GitHub)
- Contact Form (Name, Email, Message)

✅ **Design & Layout:**
- Consistent color scheme and typography
- Navigation bar for different sections
- CSS Flexbox and Grid layouts
- Full responsiveness with media queries
- Semantic HTML elements

✅ **Bonus Features:**
- Hover effects and transitions
- Downloadable resume link
- FontAwesome icons for social media
- Smooth scrolling
- Animated skill bars
- Mobile-friendly hamburger menu

## 🚀 Getting Started

1. **Customize Your Information:**
   - Replace `[Your Name Here]` in HTML comments with your actual name
   - Update personal information in `index.html`:
     - Name and bio in hero section
     - Profile photo path
     - Education details
     - Experience information
     - Project descriptions and images
     - Skills and skill levels
     - Certificates and awards
     - Contact information

2. **Add Your Photos:**
   - Replace the profile image: `css/images/about me/me.jpg`
   - Add project screenshots to: `css/images/skills/`
   - Ensure images are optimized for web (recommended: JPG/PNG, max 500KB)

3. **Customize Colors (Optional):**
   - Edit CSS variables in `styles.css`:
     ```css
     :root {
         --primary-color: #2c3e50;
         --secondary-color: #3498db;
         --accent-color: #e74c3c;
     }
     ```

## 📱 Responsive Design

The website is fully responsive and works on:
- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (320px - 767px)

## 🎨 Features

- **Smooth Scrolling:** Navigation links smoothly scroll to sections
- **Mobile Menu:** Hamburger menu for mobile devices
- **Animated Skills:** Progress bars animate when scrolled into view
- **Contact Form:** Functional form with validation (frontend only)
- **Hover Effects:** Interactive elements with smooth transitions
- **Loading Animations:** Fade-in effects for sections
- **Typing Effect:** Animated subtitle in hero section

## 📁 File Structure

```
portfolio/
├── index.html          # Main portfolio page
├── styles.css          # All CSS styles
├── script.js           # JavaScript functionality
├── about.html          # Redirect to main page
├── skill.html          # Redirect to main page
├── README.md           # This file
└── css/
    └── images/
        ├── about me/   # Profile photos
        └── skills/     # Project images
```

## 🔧 Customization Guide

### Adding New Projects
1. Duplicate a project card in the HTML
2. Update the image, title, description, and tools
3. Add project links (GitHub, live demo)

### Modifying Skills
1. Update skill names and percentages in HTML
2. Adjust `data-width` attribute for progress bars
3. Add new skill categories as needed

### Changing Colors
1. Modify CSS variables in `:root` selector
2. Update specific element colors if needed
3. Test contrast for accessibility

## 📋 Assignment Checklist

- [ ] Add your name to HTML/CSS file comments
- [ ] Replace placeholder content with your information
- [ ] Add your profile photo
- [ ] Update education details
- [ ] Add real experience/internships
- [ ] Include 2+ actual projects
- [ ] List your technical skills
- [ ] Add certificates/awards you have
- [ ] Update contact information
- [ ] Test responsiveness on mobile
- [ ] Validate HTML and CSS
- [ ] Create GitHub repository
- [ ] Deploy to GitHub Pages
- [ ] Submit repository and live links

## 🌐 Deployment

1. **GitHub Repository:**
   - Create repo named: `YourName_RegNumber`
   - Push all files to repository
   - Ensure `index.html` is in root directory

2. **GitHub Pages:**
   - Go to repository Settings
   - Scroll to Pages section
   - Select source: Deploy from branch
   - Choose main branch
   - Save and wait for deployment

## 📊 Assessment Criteria Coverage

- **HTML Structure & Semantics (2 pts):** ✅ Semantic elements, proper structure
- **CSS Styling & Visual Design (2 pts):** ✅ Modern design, consistent styling
- **Responsiveness (2 pts):** ✅ Mobile-first, media queries
- **Content Completeness (2 pts):** ✅ All required sections included
- **Code Organization (1 pt):** ✅ Clean, commented code
- **Creativity & Personal Touch (1 pt):** ✅ Animations, interactions, modern design

## 🎯 Tips for Success

1. **Personalize Everything:** Make it truly yours with real content
2. **Test Thoroughly:** Check on different devices and browsers
3. **Optimize Images:** Compress images for faster loading
4. **Validate Code:** Use W3C validators for HTML/CSS
5. **Get Feedback:** Ask others to review before submission
6. **Document Changes:** Keep track of customizations made

## 📞 Support

If you need help customizing the portfolio:
1. Check the code comments for guidance
2. Refer to this README for instructions
3. Test changes incrementally
4. Use browser developer tools for debugging

Good luck with your assignment! 🚀