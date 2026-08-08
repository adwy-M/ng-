# ng- | Login Form UI

A modern, responsive login form interface built with HTML and CSS. This project showcases a professional authentication UI with split-layout design, social login options, and full mobile responsiveness.

## 📋 Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Design Details](#design-details)
- [Browser Support](#browser-support)
- [License](#license)

## 🎯 Project Overview

**ng-** is a frontend login form interface designed to provide users with a seamless authentication experience. The project features a modern, clean design with a split-layout approach that combines an image section with a functional login form. It includes traditional email/password authentication along with social media login options (Google, Facebook, Apple).

This project demonstrates best practices in:
- **Responsive Web Design** - Mobile-first approach with media queries
- **CSS Grid Layout** - Advanced CSS Grid for complex layouts
- **User Experience** - Intuitive form design with clear visual hierarchy
- **Accessibility** - Proper HTML semantics and form controls

## ✨ Features

- **Split Layout Design** - Professional two-column layout with image and form sections
- **Email & Password Authentication** - Standard login form inputs with validation
- **Social Login Integration** - Quick login buttons for Google, Facebook, and Apple
- **Password Recovery** - "Forgot Password?" link for account recovery
- **Sign-Up Redirection** - Link to sign-up page for new users
- **Responsive Design** - Fully responsive layout that adapts to all screen sizes (mobile, tablet, desktop)
- **Modern Styling** - Linear gradient submit button with hover effects
- **Form Validation** - HTML5 validation attributes for input fields

## 🛠 Tech Stack

- **Frontend Language:** HTML5
- **Styling:** CSS3
- **Layout System:** CSS Grid
- **Design Approach:** Responsive Web Design (Mobile-first)
- **Fonts:** Montserrat, Open Sans (via system font stack)

## 📁 Project Structure

```
ng-/
├── index2.html          # Main login form HTML file
├── style2.css           # Stylesheet with responsive design
├── Sign_Up3.png         # Background image for login form
└── README.md            # Project documentation
```

### File Descriptions

**index2.html**
- Main HTML file containing the login form structure
- Semantic HTML5 markup with proper form elements
- Includes email and password inputs with autofocus attributes
- Social login buttons with external icon resources
- Terms of Service and Privacy Policy links
- Sign-up redirection link

**style2.css**
- Complete styling for the login form
- CSS Grid layout for the split-panel design
- Responsive media queries for screens up to 600px width
- Custom styling for buttons, inputs, and form elements
- Linear gradient effects for the submit button
- Hover states for improved user interaction

**Sign_Up3.png**
- Decorative image displayed on the left side of the login form
- Enhances visual appeal of the authentication interface

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic HTTP server for local development (optional, can open HTML directly)

### Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/adwy-M/ng-.git
   cd ng-
   ```

2. **Open the application:**
   - **Option 1:** Directly open `index2.html` in your web browser
   ```bash
   open index2.html  # macOS
   start index2.html # Windows
   firefox index2.html # Linux
   ```
   
   - **Option 2:** Use a local server (recommended for development)
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Python 2
   python -m SimpleHTTPServer 8000
   
   # Using Node.js (http-server)
   npx http-server
   ```

3. **Access the application:**
   - If using a server: Navigate to `http://localhost:8000` in your browser
   - The login form will display with full responsiveness

## 🎨 Design Details

### Layout Structure

The login form uses a CSS Grid-based layout with two main sections:

1. **Left Section** - Image area (30% width)
   - Displays `Sign_Up3.png` as a decorative background
   - Responsive: Hidden or repositioned on mobile devices

2. **Right Section** - Form area (70% width)
   - Login title and welcome message
   - Email and password input fields
   - Forgot password link
   - Submit button with gradient styling
   - Social login options (Google, Facebook, Apple)
   - Terms of Service and Privacy Policy text
   - Sign-up redirection link

### Color Scheme

- **Primary Button Color:** Linear gradient from #3866FF to #2084F9
- **Border Color:** #c1cadf (light blue-gray)
- **Shadow Color:** rgba(0, 82, 224, 0.1) with subtle blue tint
- **Text Color:** Black/Gray
- **Background:** White

### Responsive Breakpoints

- **Desktop:** Full split-layout design (600px and above)
- **Mobile:** Adjusted layout with narrower container, repositioned elements (below 600px)
- On mobile, the form width reduces to 400px with adjusted margins and padding

## 🌐 Browser Support

| Browser | Support |
|---------|---------|
| Chrome  | ✅ Latest versions |
| Firefox | ✅ Latest versions |
| Safari  | ✅ Latest versions |
| Edge    | ✅ Latest versions |
| Opera   | ✅ Latest versions |

## 📱 Responsive Design

The project includes comprehensive media queries ensuring optimal viewing experience across all devices:

- **Desktop (> 600px):** Full-featured split layout
- **Tablets & Mobile (≤ 600px):** Optimized single-column layout with:
  - Adjusted container width (400px)
  - Modified grid areas for better mobile UX
  - Full-width buttons and form elements
  - Centered text and content

## 🔐 Features Walkthrough

### Email Input
- Placeholder: "Email"
- Required field with validation
- Autofocus attribute for immediate interaction

### Password Input
- Placeholder: "Password"
- Type: password (masked input)
- Required field with validation

### Submit Button
- Gradient background with hover effects
- Smooth shadow animation on hover
- Full width (90%) for easy touch targets

### Social Login
- Three quick-login options: Google, Facebook, Apple
- Icon buttons with hover states
- External icon resources from CDN

### Additional Links
- Forgot Password - Account recovery option
- Terms of Service - Legal agreement link
- Privacy Policy - Data protection information
- Sign Up - New user registration link

## 📝 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for complete details.

### MIT License Summary

You are free to:
- ✅ Use this software for any purpose
- ✅ Copy, modify, and distribute the software
- ✅ Include this software in proprietary applications

Under the following conditions:
- 📋 Include the original license and copyright notice
- ⚖️ The software is provided "as is" without any warranty

For more information, visit [MIT License Official Page](https://opensource.org/licenses/MIT)

## 👨‍💼 Author

**Project Owner:** adwy-M  
**Repository:** https://github.com/adwy-M/ng-  
**Homepage:** https://github.com/adwy-Tu/ng-

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📧 Support & Feedback

For questions, bug reports, or feature requests, please open an issue on the [GitHub Issues](https://github.com/adwy-M/ng-/issues) page.

## 🔄 Version History

- **v1.0.0** (November 25, 2023) - Initial release with responsive login form UI

## 📚 Additional Resources

- [MDN Web Docs - HTML Forms](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/form)
- [MDN Web Docs - CSS Grid](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout)
- [Responsive Web Design Best Practices](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design)
- [Web Accessibility (WCAG)](https://www.w3.org/WAI/WCAG21/quickref/)

---

**Last Updated:** August 8, 2026  
**Project Status:** Active
