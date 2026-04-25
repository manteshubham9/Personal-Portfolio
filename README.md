# Shubham Mante - Modern Portfolio Website

A visually striking, modern personal portfolio website with dark theme, glassmorphism effects, and smooth animations. This portfolio showcases projects, skills, achievements, and provides a professional way to share your work with potential employers and collaborators.

---

## 📋 Features

### Design & User Experience
- **Dark Theme** with purple/blue gradient accents
- **Glassmorphism Effects** with backdrop-filter blur and transparent cards
- **Smooth Animations** and transitions throughout
- **Fully Responsive** design for desktop, tablet, and mobile
- **Modern Typography** using Inter font
- **Hover Effects** on all interactive elements

### Sections
1. **Hero Section** - Full-screen introduction with typing animation and profile image
2. **About Section** - Personal introduction with info cards and contact details
3. **Facts & Stats** - Dynamic counters for projects and skills
4. **Skills Section** - Animated progress bars showing skill levels
5. **Resume Section** - Professional resume with education and future goals (2-column layout)
6. **Projects Section** - Showcase of real projects with descriptions and tech stacks
7. **Achievements Section** - Organized certifications and courses completed
8. **Contact Section** - Contact information and message form

---

## 📁 File Structure

```
portfolio/
├── index.html              # Main HTML file
├── css/
│   └── styles.css          # All styling
├── js/
│   └── script.js           # JavaScript animations and interactions
├── images/
│   └── profile.jpg         # Your profile photo (add here)
├── SETUP_IMAGES.md         # Guide for adding profile image
└── README.md               # This file
```

---

## 🚀 Quick Start

### 1. Open the Portfolio
- Open `index.html` in your web browser
- No installation or build process required!

### 2. Add Your Profile Image
- Place your profile photo in the `images/` folder
- Name it: `profile.jpg` (or `.png`)
- Recommended size: 800x800 pixels
- See `SETUP_IMAGES.md` for detailed instructions

### 3. Customize Content
All content is in `index.html`. Edit:
- Name and title in hero section
- About text and details
- Skills and their percentages
- Projects with descriptions
- Certifications and courses
- Contact information and form fields

---

## 🎨 Customization

### Change Colors
Open `css/styles.css` and search for color values:
- `#ba55d3` - Primary purple accent
- `#4169e1` - Secondary blue accent
- `#0a0a0a` - Dark background

### Modify Content
All text content is in `index.html`. Key sections:
- Lines 40-50: Hero section text
- Lines 68-100: About section content
- Lines 102-125: Facts counters
- Lines 145-170: Skills and percentages
- Lines 175-215: Resume content
- Lines 220-260: Projects
- Lines 265-290: Certifications
- Lines 295-310: Contact info

### Update Skills Percentages
In the skills section, modify the `data-width` attribute:
```html
<div class="progress" data-width="80%"></div>
```

### Add/Remove Sections
To add a new section:
1. Add menu link in navbar
2. Add section HTML with unique id
3. Add CSS styling
4. Add JavaScript if animation needed

---

## 🎬 Animations

### Included Animations
- **Typing Effect**: Hero title cycles through "AI & ML Student", "Builder", "Problem Solver"
- **Counter Animation**: Facts section numbers count up when scrolled into view
- **Progress Bars**: Skills bars fill from 0 to their percentage
- **Fade-in Effect**: Sections fade in as you scroll
- **Hover Effects**: Cards and buttons react to mouse hover
- **Scroll Indicator**: Bouncing animation suggesting scrolling
- **Parallax**: Subtle background movement on scroll

---

## 📱 Mobile Responsiveness

The portfolio is fully responsive:
- **Mobile Menu**: Hamburger menu appears on screens under 768px
- **Adaptive Layouts**: 2-column resume becomes 1-column on mobile
- **Touch-Friendly**: All buttons and links are easily tappable
- **Optimized Typography**: Text sizes adjust for different screens

---

## 🔗 Project Links

Update project links in `index.html`:
```html
<a href="link-to-your-project" class="btn">View Project</a>
```

---

## 📧 Contact Form

The contact form is a placeholder. To make it functional:

### Option 1: FormSubmit (Free)
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

### Option 2: Formspree
1. Visit: https://formspree.io
2. Create an account
3. Replace form action with your form ID

### Option 3: Backend Service
Connect the form to your backend API (NodeJS, Flask, etc.)

---

## 🎯 Best Practices

### For Your Profile Image
- Use a professional headshot
- Good lighting and clear visibility
- Square format (1:1 aspect ratio)
- JPG format recommended for optimization
- Size: 800x800 pixels minimum

### For Project Descriptions
- Keep descriptions concise but informative
- Highlight the problem you solved
- Mention technologies used
- Add actual project links when available

### For Content
- Keep text professional but natural
- Use short paragraphs for readability
- Proofread carefully
- Update regularly with new projects

---

## 🌐 Deployment

### Host on Netlify (Free)
1. Create GitHub repository
2. Connect to Netlify
3. Deploy automatically

### Host on GitHub Pages
1. Create `username.github.io` repository
2. Push files to main branch
3. Access at `https://username.github.io`

### Host on Vercel
1. Import project to Vercel
2. Auto-deploys on git push
3. Custom domain support

---

## 🛠️ Browser Support

- Chrome/Edge: ✅ Full support
- Firefox: ✅ Full support
- Safari: ✅ Full support
- Mobile browsers: ✅ Full support

---

## 📝 Notes

- No external dependencies (pure HTML/CSS/JS)
- Fast loading (no frameworks)
- SEO optimized
- Accessible design (semantic HTML)
- Print-friendly CSS included

---

## 📞 Support

For questions or issues:
1. Check `SETUP_IMAGES.md` for image-related questions
2. Review the HTML/CSS/JS files
3. Test in different browsers
4. Check browser console for errors

---

## 🎉 You're All Set!

Your modern portfolio is ready to showcase your work. Make it yours by:
- Adding your professional photo
- Updating all personal information
- Adding real project links
- Sharing with employers and collaborators

Good luck with your portfolio! 🚀

---

**Last Updated**: April 2026  
**Version**: 2.0 (Updated & Enhanced)
