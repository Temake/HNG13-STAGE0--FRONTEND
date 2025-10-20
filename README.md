# Profile Card Application

A responsive, accessible multi-page profile application built with vanilla HTML, CSS, and JavaScript. Created for HNG13 Stage 0 frontend task.

## 🎯 Features

- **Profile Card**: Interactive profile with real-time timestamp and social links
- **About Me Page**: Personal reflections and development goals  
- **Contact Form**: Validated contact form with real-time feedback
- **Fully Responsive**: Mobile-first design that works on all devices
- **Accessible**: WCAG compliant with keyboard navigation and screen reader support
- **Semantic HTML**: Proper HTML5 structure with required `data-testid` attributes

## 🛠️ Technologies

- **HTML5**: Semantic markup with accessibility features
- **CSS3**: Responsive design with Flexbox and Grid
- **Vanilla JavaScript**: Form validation and real-time updates

## 📁 Project Structure

```
frontend/
├── index.html          # Main profile card page
├── about.html          # About me with reflections
├── contact.html        # Contact form with validation
├── index.css           # Shared styles for all pages
├── README.md           # Project documentation
└── Teminiolwa.jpg      # Profile image
```

## 🚀 Quick Start

1. Clone or download the project files
2. Open `index.html` in any modern web browser
3. Navigate between pages using the top navigation

## 📋 Pages Overview

### Profile Card (index.html)
- User information with real-time timestamp
- Avatar image and social media links
- Hobbies and dislikes lists
- All elements include required `data-testid` attributes

### About Me (about.html)
- Personal biography and development story
- Program goals and aspirations
- Areas for confidence building
- Note to future self and additional reflections

### Contact Us (contact.html)
- Full contact form with validation
- Required fields: name, email, subject, message
- Real-time validation with error messages
- Success confirmation after submission

## ✅ Requirements Compliance

**Required Elements (with data-testid):**
- ✅ Profile card (`test-profile-card`)
- ✅ User name (`test-user-name`)
- ✅ User bio (`test-user-bio`)
- ✅ Current time (`test-user-time`)
- ✅ Avatar (`test-user-avatar`)
- ✅ Social links (`test-user-social-links`)
- ✅ Hobbies (`test-user-hobbies`)
- ✅ Dislikes (`test-user-dislikes`)

**Contact Form Elements:**
- ✅ Name field (`test-contact-name`)
- ✅ Email field (`test-contact-email`)
- ✅ Subject field (`test-contact-subject`)
- ✅ Message field (`test-contact-message`)
- ✅ Submit button (`test-contact-submit`)
- ✅ Error messages (`test-contact-error-*`)
- ✅ Success message (`test-contact-success`)

**About Page Elements:**
- ✅ Main wrapper (`test-about-page`)
- ✅ Bio section (`test-about-bio`)
- ✅ Goals section (`test-about-goals`)
- ✅ Confidence areas (`test-about-confidence`)
- ✅ Future note (`test-about-future-note`)
- ✅ Extra thoughts (`test-about-extra`)

## 🌐 Browser Support

Compatible with all modern browsers (Chrome, Firefox, Safari, Edge).

## 👤 Author

**Teminiolwa Adekoya** - Full-stack developer passionate about accessible web experiences.

---

*Built with vanilla HTML, CSS, and JavaScript*