# 🎨 Omega-Nart

A **modern, responsive animated login form** built with pure HTML and CSS. Features a glassmorphism design with dynamic animated backgrounds and smooth transitions.

## ✨ Features

- 🎯 **Responsive Design** - Fully responsive layout that works seamlessly on desktop and mobile devices
- ✨ **Smooth Animations** - Beautiful CSS animations including background color rotation and input label transitions
- 🎨 **Glassmorphism UI** - Modern frosted glass effect on the login container using backdrop-filter
- 🔒 **Form Validation** - Built-in HTML5 validation for email and password fields
- 📱 **Mobile Optimized** - Adapts gracefully to screens as small as 360px wide
- �� **Pure CSS & HTML** - No JavaScript framework dependencies (only uses Ionicons for icons)
- 🎭 **Dynamic Backgrounds** - Rotating image backgrounds with smooth color filter animations

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No installation or build tools required!

### Installation

1. Clone the repository:
```bash
git clone https://github.com/DeadlyRaymond/omega-nart.git
cd omega-nart
```

2. Open `index.html` in your web browser:
```bash
# On macOS
open index.html

# On Windows
start index.html

# On Linux
xdg-open index.html
```

3. Or deploy to GitHub Pages for instant hosting

## 📁 Project Structure

```
omega-nart/
├── index.html      # Main HTML file with login form structure
├── style.css       # Complete styling and animations
├── bg1.jpg         # Background image 1 (currently active)
├── bg2.jpg         # Background image 2
├── bg3.jpg         # Background image 3
├── bg4.jpg         # Background image 4
├── bg5.jpg         # Background image 5
└── README.md       # This file
```

## 🎬 How It Works

### HTML Structure
The login form includes:
- Email input field with icon
- Password input field with icon
- Remember me checkbox
- Forgot password link
- Login button
- Register account link

### CSS Features

#### Glassmorphism Effect
```css
.login-box {
  background: transparent;
  border: 2px solid rgba(255, 255, 255, .5);
  backdrop-filter: blur(15px);
}
```

#### Animated Background
```css
@keyframes animateBg {
  100% {
    filter: hue-rotate(360deg);
  }
}
```
The background image continuously rotates through the color spectrum.

#### Responsive Input Labels
Input labels smoothly animate when the user focuses on or enters data into the input fields.

#### Mobile Responsiveness
At screens 360px and smaller, the form expands to full screen for better usability.

## 🎨 Customization

### Change Background Image
Edit line 16 in `style.css`:
```css
background: url('bg5.jpg') no-repeat;
```
Replace `bg5.jpg` with any of the other background images (bg1.jpg - bg4.jpg) or your own image.

### Modify Colors
- Form border color: `.login-box` border property
- Text color: Change `color: #fff;` to your preferred color
- Button color: Edit the `button` CSS rule

### Adjust Form Dimensions
Edit the `.login-box` width and height properties:
```css
.login-box {
  width: 400px;
  height: 450px;
}
```

### Font Family
The form uses the **Poppins** font family imported from Google Fonts. Change it by modifying the `@import` URL at the top of `style.css`.

## 🌐 Browser Support

- ✅ Chrome/Edge (latest 2 versions)
- ✅ Firefox (latest 2 versions)
- ✅ Safari (latest 2 versions)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

**Note:** Glassmorphism effects (backdrop-filter) require modern browsers. Older browsers will show the form without blur effects but remain fully functional.

## 📊 Language Composition

- **CSS**: 59.1% - Handles all styling and animations
- **HTML**: 40.9% - Provides semantic structure

## 🔐 Security Notes

This is a **frontend demonstration only**. The form currently:
- Does not validate credentials
- Does not submit to a backend
- Should be integrated with a proper authentication system for production use

For production implementation, add:
- Backend validation
- HTTPS encryption
- Secure password hashing
- CSRF protection

## 🎓 Learning Resources

This project is great for learning:
- HTML form semantics
- CSS Flexbox layouts
- CSS animations and transitions
- Responsive design principles
- Modern CSS features (backdrop-filter, CSS Grid)
- SVG icon integration

## 📦 Dependencies

- **Ionicons** (v5.5.2) - Icon library via CDN
- **Google Fonts: Poppins** - Typography

## 📄 License

This project is provided as-is for educational and demonstration purposes.

## 🤝 Contributing

Feel free to fork, modify, and improve! If you have suggestions or improvements, contributions are welcome.

## 📞 Support

For issues or questions, please open a GitHub issue in the repository.

---

**Made with ❤️ by DeadlyRaymond**

Happy coding! 🚀
