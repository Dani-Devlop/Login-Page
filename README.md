
# Login & Sign Up - Flip Card

A modern, responsive login and sign-up page with a sleek flip-card animation, built with pure HTML and CSS. This component is perfect for authentication interfaces in web applications.

## ✨ Features

- **Flip Card Animation**: Smooth 3D flip transition between Login and Sign Up forms.
- **Fully Responsive**: Optimized for desktops, tablets, and mobile devices.
- **Form Validation**: 
  - Email validation using regex patterns.
  - Password strength requirements (minimum 8 characters, including letters and numbers).
- **Interactive UI Elements**:
  - Floating labels with underline animations.
  - Social login buttons (Google, Apple, Facebook, X).
  - "Remember me" checkbox with custom styling.
  - Terms & Conditions agreement for sign-up.
- **Visual Design**:
  - Gradient background with a glass-morphism (frosted glass) header.
  - Custom CSS variables for easy theming.
  - Hover and focus transitions for enhanced user experience.

## 🛠️ Technologies Used

- **HTML5**: Semantic structure.
- **CSS3**: Custom properties, Flexbox, animations, and responsive design.
- **SVG Icons**: Sourced from SVGRepo and Wikimedia Commons.
- **No JavaScript**: All interactivity (flip, validation) is handled via CSS and HTML attributes.

## 📁 Project Structure

```

Login-Page/
├── Login.html                # Main HTML file
├── Static/
│   ├── Css/
│   │   ├── Style.css         # Primary styles (layout, colors, animations)
│   │   ├── Style2.css        # Additional/responsive styles
│   │   └── FlipStyle.html    # Flip card-specific styles (inline)
│   └── Image/
│       ├── icons/            # Social media icons (SVG)
│       └── [background images]
└── README.md

```

## 🚀 Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Dani-Devlop/Login-Page.git
```

2. Navigate to the project folder:
   ```bash
   cd Login-Page
   ```
3. Open Login.html in your browser.

No build tools or dependencies are required—just open the file and go!

🎨 Customization

You can easily customize the look and feel by modifying the CSS variables in Static/Css/Style.css:

```css
:root {
  --background-img: linear-gradient(135deg, #0b5351, #092327, #077283);
  --button-color: #067e7c;
  --text-color-logo-text: white;
  /* ... and more */
}
```

Adjust colors, fonts, shadows, and spacing to match your brand.

📱 Responsive Design

The layout adapts seamlessly to different screen sizes:

· Desktop: Full card view with flip animation.
· Tablet/Mobile: Adjusted spacing, font sizes, and touch-friendly inputs.

🔒 Form Validation

· Login:
  · Email: Must follow a valid email format (pattern="^[\w-\.]+@([\w-]+\.)+[\w-]{2,4}$").
  · Password: Minimum 8 characters, including letters and numbers.
· Sign Up:
  · Name: Required field.
  · Email: Valid email format required.
  · Password: Strong password pattern (pattern="^(?=.*\d)(?=.*[a-z])(?=.*[A-Z])(?=.*[a-zA-Z]).{8,}$").
  · Terms: Must agree to Terms & Conditions and Privacy Policy.

🤝 Contributing

Contributions are welcome! Feel free to open issues or submit pull requests for improvements.

1. Fork the repository.
2. Create a new branch (git checkout -b feature/your-feature).
3. Commit your changes (git commit -m 'Add some feature').
4. Push to the branch (git push origin feature/your-feature).
5. Open a Pull Request.

📄 License

This project is open-source and available under the MIT License.

---

Made with ❤️ by Dani-Devlop

```
