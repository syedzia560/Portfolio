# Zia UI Hassan - Portfolio Website

A modern, responsive portfolio website showcasing skills, experience, and projects as a Junior Web Developer.

## 🌟 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: Hover effects, smooth scrolling, and dynamic navigation
- **Contact Form**: Functional contact form with validation
- **SEO Optimized**: Proper meta tags and semantic HTML structure
- **Fast Loading**: Optimized code and resources for quick page loads

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and accessibility features
- **CSS3**: Modern styling with Flexbox, Grid, and animations
- **JavaScript**: Interactive functionality and smooth user experience
- **Font Awesome**: Icons for better visual appeal
- **Google Fonts**: Professional typography with Poppins font family

## 📂 Project Structure

```
portfolio-website/
├── index.html          # Main HTML file
├── css/
│   └── style.css       # All styling and responsive design
├── js/
│   └── script.js       # JavaScript functionality
├── images/
│   └── profile-placeholder.svg  # Profile image placeholder
└── README.md          # This file
```

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- A text editor or IDE for customization

### Installation

1. **Download/Clone the project**:
   ```bash
   # If you have git installed
   git clone <repository-url>
   
   # Or download the files directly
   ```

2. **Navigate to the project directory**:
   ```bash
   cd portfolio-website
   ```

3. **Open the website**:
   - Double-click `index.html` to open in your default browser
   - Or right-click → Open with → Your preferred browser
   - For development, use a local server like Live Server in VS Code

## 🎨 Customization

### Replace Profile Image
1. Replace `images/profile-placeholder.svg` with your professional photo
2. Rename your image to `profile.jpg` or update the src in `index.html` line 59:
   ```html
   <img src="images/your-photo.jpg" alt="Zia UI Hassan" class="profile-img">
   ```

### Update Personal Information
Edit the following sections in `index.html`:

1. **Contact Information** (lines 71-72, 224-235):
   - Email address
   - Phone number
   - Location

2. **Social Links** (lines 270-274):
   - Add your GitHub, LinkedIn, Twitter profiles
   - Replace `#` with actual URLs

3. **Skills & Technologies** (lines 89-119):
   - Add/remove skills as needed
   - Update technology lists

4. **Experience Section** (lines 132-149):
   - Update work experience details
   - Add more positions if needed

5. **Projects Section** (lines 155-182):
   - Update project descriptions
   - Add more projects or modify existing ones

6. **Education Section** (lines 188-209):
   - Update educational background
   - Add certifications if any

### Styling Customization
Edit `css/style.css` to change:
- **Colors**: Update CSS custom properties for consistent theming
- **Fonts**: Change font families in the CSS file
- **Layout**: Modify sections, spacing, and responsive breakpoints
- **Animations**: Adjust transition timings and effects

### JavaScript Functionality
`js/script.js` includes:
- Mobile navigation toggle
- Smooth scrolling
- Form validation
- Scroll animations
- Interactive elements

## 📱 Responsive Design

The website is fully responsive with breakpoints at:
- **Desktop**: 1200px and above
- **Tablet**: 768px to 1199px
- **Mobile**: Below 768px

## 🎯 SEO Features

- Semantic HTML structure
- Meta tags for social media sharing
- Proper heading hierarchy
- Alt text for images
- Fast loading optimization

## 🚀 Deployment Options

### GitHub Pages
1. Push code to a GitHub repository
2. Go to Settings → Pages
3. Select source branch (usually `main`)
4. Your site will be available at `username.github.io/repository-name`

### Netlify
1. Drag and drop the project folder to Netlify
2. Or connect your GitHub repository
3. Automatic deployment on every commit

### Vercel
1. Import your GitHub repository
2. Deploy with zero configuration
3. Automatic deployments and previews

## 🔧 Development Tips

1. **Use Live Server**: For real-time updates during development
2. **Browser DevTools**: Test responsive design and debug
3. **Optimize Images**: Compress images for better performance
4. **Test Forms**: Ensure contact form works properly
5. **Cross-browser Testing**: Test on different browsers

## 📞 Contact Form Setup

The contact form currently shows a success message. To make it functional:

1. **Backend Service**: Use services like Formspree, Netlify Forms, or EmailJS
2. **Server-side**: Set up your own backend with PHP, Node.js, etc.
3. **Third-party**: Integrate with services like Google Forms

Example with Formspree:
```html
<form action="https://formspree.io/f/your-form-id" method="POST">
  <!-- form fields -->
</form>
```

## 🤝 Support

For questions or support:
- **Email**: syedzis564@gmail.com
- **Phone**: +92-335-2643

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

**Built with ❤️ by Zia UI Hassan**

*Last updated: August 2025*
