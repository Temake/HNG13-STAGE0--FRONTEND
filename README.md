# Profile Card Component

A simple, accessible, and responsive profile card built with vanilla HTML, CSS, and JavaScript. This project showcases modern frontend development practices with semantic markup, accessibility features, and responsive design.

## 🎯 Project Overview

This profile card component displays user information in an elegant, interactive format that works seamlessly across all devices. Built as part of the HNG13 Stage 0 frontend task, it demonstrates proficiency in fundamental web technologies without relying on frameworks or libraries.

## ✨ Features

### Core Components
- **Profile Information**: Name, bio, and real-time timestamp
- **Avatar Display**: User profile picture with responsive sizing
- **Social Links**: External links to social media profiles
- **Hobbies & Dislikes**: Organized lists showcasing personal interests

### Technical Features
- **Semantic HTML**: Proper use of HTML5 semantic elements
- **Accessibility**: WCAG compliant with keyboard navigation support
- **Responsive Design**: Mobile-first approach with tablet and desktop layouts
- **Real-time Updates**: Live timestamp display using vanilla JavaScript
- **Clean CSS**: Modern styling with Flexbox and Grid layouts

## 🛠️ Technologies Used

- **HTML5**: Semantic markup with proper accessibility attributes
- **CSS3**: Modern styling with Flexbox, Grid, and responsive design
- **Vanilla JavaScript**: Real-time functionality without external dependencies

## 📁 Project Structure

```
frontend/
├── index.html          # Main HTML file with semantic structure
├── index.css           # Comprehensive styling and responsive design
├── README.md           # Project documentation
└── Teminiolwa.jpg      # Profile avatar image
```

## 🎨 Design Features

### Responsive Layout
- **Mobile (< 768px)**: Stacked vertical layout for optimal mobile viewing
- **Tablet (768px+)**: Side-by-side layout with avatar and content
- **Desktop (1024px+)**: Enhanced spacing and larger elements

### Visual Design
- Clean, modern interface with subtle shadows and rounded corners
- Smooth hover transitions and interactive feedback
- Accessible color contrast ratios
- Professional typography hierarchy

### Accessibility
- Semantic HTML structure for screen readers
- Keyboard navigation support for all interactive elements
- Proper ARIA labels and alt text
- High contrast focus indicators

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required

### Installation
1. Clone or download the project files
2. Ensure all files are in the same directory
3. Open `index.html` in your web browser

### Usage
Simply open the `index.html` file in any modern web browser. The profile card will load with:
- Real-time timestamp updates
- Responsive layout adaptation
- Interactive social links
- Accessible keyboard navigation

## 🔧 Customization

### Updating Profile Information
Edit the HTML content in `index.html`:

```html
<!-- Update name -->
<h1 data-testid="test-user-name" class="user-name">Your Name</h1>

<!-- Update bio -->
<p data-testid="test-user-bio" class="user-bio">
    Your biography here...
</p>

<!-- Update avatar -->
<img data-testid="test-user-avatar" 
     src="your-image.jpg" 
     alt="Your profile picture" 
     class="avatar">
```

### Styling Modifications
Customize colors, fonts, and layout in `index.css`:

```css
/* Update primary color */
.avatar {
    border: 4px solid #your-color;
}

.social-links a {
    background-color: #your-color;
}
```

### Adding Features
The vanilla JavaScript foundation makes it easy to add new features:
- Interactive form elements
- Local storage for user preferences
- Dynamic content loading
- Animation enhancements

## 📋 Requirements Compliance

This project meets all specified requirements:

### ✅ Required Elements (with data-testid)
- Profile card container (`test-profile-card`)
- User name (`test-user-name`)
- User biography (`test-user-bio`)
- Current time in milliseconds (`test-user-time`)
- Avatar image (`test-user-avatar`)
- Social links container (`test-user-social-links`)
- Hobbies list (`test-user-hobbies`)
- Dislikes list (`test-user-dislikes`)

### ✅ Technical Requirements
- Semantic HTML5 structure
- Accessibility compliance
- Responsive design
- Real-time JavaScript functionality
- Cross-browser compatibility

## 🧪 Testing

### Automated Testing
All elements include the required `data-testid` attributes for automated testing:

```javascript
// Example test queries
document.querySelector('[data-testid="test-profile-card"]')
document.querySelector('[data-testid="test-user-name"]')
document.querySelector('[data-testid="test-user-time"]')
```

### Manual Testing
1. **Responsiveness**: Resize browser window to test layout adaptation
2. **Accessibility**: Navigate using keyboard (Tab, Enter, Space)
3. **Functionality**: Verify timestamp updates every second
4. **Links**: Test social media links open in new tabs


## 📱 Mobile Optimization

- Touch-friendly interface elements
- Optimized image sizes for mobile bandwidth
- Responsive typography scaling
- Proper viewport configuration

## 🔒 Security Features

- External links use `rel="noopener noreferrer"`
- No inline JavaScript in HTML
- Clean separation of concerns
- No external dependencies or CDNs

## 🎯 Future Enhancements

Potential features for future versions:
- Dark/light theme toggle
- Interactive avatar upload
- Editable profile fields
- Social media integration
- Animation library integration
- Progressive Web App features

## 📄 License

This project is created for educational purposes as part of the HNG13 program.

## 👤 Author

**Teminiolwa Adekoya**
- Full-stack developer passionate about accessible web experiences
- Building user-friendly applications with modern web technologies

---

*Built with ❤️ using vanilla HTML, CSS, and JavaScript*