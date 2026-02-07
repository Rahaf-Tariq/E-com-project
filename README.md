# Riona Jewels

> A modern, responsive e-commerce website for premium jewelry collections.

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=flat&logo=javascript&logoColor=%23F7DF1E)
![Bootstrap](https://img.shields.io/badge/bootstrap-%23563D7C.svg?style=flat&logo=bootstrap&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

Riona Jewels is a fully responsive jewelry e-commerce website showcasing premium collections with elegant design and smooth user experience. Built with Bootstrap 5 and modern CSS, this project demonstrates best practices in responsive web design and component-based layouts.

![Riona Jewels Preview](https://github.com/Rahaf-Tariq/E-com-project/blob/9af69838c09863df6b6cca2e84ee7cd77baed633/ecom.PNG)

## What This Project Does

Riona Jewels provides:

- **Responsive Navigation**: Fixed-top navbar with smooth scrollspy navigation
- **Hero Section**: Eye-catching landing section with call-to-action
- **Featured Collection**: Curated showcase of premium jewelry pieces
- **Product Gallery**: Complete catalog with 10+ products
- **About Section**: Brand story and value propositions
- **Contact Information**: Multi-channel contact options
- **Responsive Design**: Optimized for mobile, tablet, and desktop devices
- **Interactive Elements**: Hover effects, smooth scrolling, and animations

## Installation

### Basic Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/Rahaf-Tariq/riona-jewels.git
   ```

2. Navigate to the project directory:
   ```bash
   cd riona-jewels
   ```

3. Open the website:
   ```bash
   open index.html
   ```

No build process required. The website runs directly in any modern browser.

### Using a Local Server

For better development experience, serve the project using:

**Python 3:**
```bash
python -m http.server 8000
```

**Node.js:**
```bash
npx http-server -p 8000
```

**VS Code Live Server:**
- Right-click on `index.html`
- Select "Open with Live Server"

Then navigate to `http://localhost:8000`

## Project Structure

```
riona-jewels/
├── index.html                  # Main HTML file
├── css/
│   ├── style.css              # Main stylesheet
│   └── responsiveStyle.css    # Responsive breakpoints
├── js/
│   └── main.js                # JavaScript functionality
├── images/
│   ├── logo1.jpg              # Brand logo/hero image
│   ├── imgs/                  # Featured products
│   │   ├── p1.jpg
│   │   ├── p2.jpg
│   │   └── p3.jpg
│   └── product-img/           # Full product catalog
│       ├── p1.jpg
│       ├── p2.jpg
│       └── ...
└── README.md                   # Documentation
```

## Example Usage

### Navigation

The website includes six main sections accessible through the navigation bar:
- **Home**: Hero landing section
- **Featured**: Highlighted product collection
- **Products**: Complete product catalog
- **About**: Brand information and values
- **Contact**: Contact details
- **Cart**: Shopping cart icon (placeholder)

### Responsive Breakpoints

The website is optimized for multiple screen sizes:

**Desktop (1024px+)**
- Full grid layout
- 4-column product display
- Enhanced hover effects

**Tablet (768px - 1023px)**
- 2-column product display
- Adjusted typography
- Optimized spacing

**Mobile (576px - 767px)**
- Single column layout
- Compressed hero section
- Mobile-optimized navigation

**Extra Small (<576px)**
- Minimal layout
- Touch-friendly buttons
- Condensed content

## Setting Up the Development Environment

### Prerequisites

- Web browser (Chrome 90+, Firefox 88+, Safari 14+, Edge 90+)
- Text editor (VS Code, Sublime Text, Atom)
- Git for version control
- Optional: Local server (Python, Node.js, or Live Server extension)

### Development Setup

1. Fork and clone the repository:
   ```bash
   git clone https://github.com/Rahaf-Tariq/riona-jewels.git
   cd riona-jewels
   ```

2. Open in your code editor:
   ```bash
   code .
   ```

3. Start development server (optional):
   ```bash
   python -m http.server 8000
   ```

4. Make changes to HTML, CSS, or JavaScript files

5. Test across multiple browsers and devices

### External Dependencies

The project uses CDN-hosted libraries:

- **Bootstrap 5.3.3**: UI framework
- **Font Awesome 7.0.1**: Icon library
- **Google Fonts** (optional): Custom typography

No npm or package manager installation required.

## How to Ship a Change

### Contributing Guidelines

1. **Fork the Repository**
   ```bash
   git fork https://github.com/Rahaf-Tariq/riona-jewels.git
   ```

2. **Create a Feature Branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Make Your Changes**
   - Follow existing code structure
   - Maintain Bootstrap class conventions
   - Test responsive layouts
   - Ensure cross-browser compatibility

4. **Test Thoroughly**
   - Desktop browsers (Chrome, Firefox, Safari, Edge)
   - Mobile devices (iOS Safari, Chrome Mobile)
   - Tablet viewports
   - Different screen orientations

5. **Commit Your Changes**
   ```bash
   git add .
   git commit -m "Add: Brief description of changes"
   ```

6. **Push to Your Fork**
   ```bash
   git push origin feature/your-feature-name
   ```

7. **Submit a Pull Request**
   - Provide clear description
   - Include screenshots for UI changes
   - Reference related issues

### Code Style Guidelines

**HTML:**
- Use semantic HTML5 elements
- Maintain proper indentation (2 spaces)
- Keep Bootstrap classes organized
- Add comments for complex sections

**CSS:**
- Follow BEM naming convention where applicable
- Group related styles together
- Use CSS custom properties for theme colors
- Comment major sections

**JavaScript:**
- Use modern ES6+ syntax
- Add JSDoc comments for functions
- Handle edge cases gracefully
- Maintain code readability

### Adding New Products

When adding products to the catalog:

1. Add product images to `images/product-img/` directory
2. Optimize images (recommended: 800x800px, <200KB)
3. Update HTML with new product card
4. Follow existing naming conventions
5. Test image loading and responsiveness

## Features Breakdown

### Navigation Bar
- Fixed-top positioning
- Smooth scroll behavior
- Active state highlighting
- Responsive hamburger menu

### Hero Section
- Full-width background image
- Overlay gradient effect
- Centered content alignment
- Call-to-action button

### Product Cards
- Hover effects and animations
- Consistent aspect ratios
- "Add to Cart" functionality (placeholder)
- Responsive grid layout

### About Section
- Split-screen layout
- Brand story narrative
- Feature highlights with icons
- Image hover effects

### Contact Section
- Three-column layout
- Contact information display
- Icon integration
- Responsive stacking

### Footer
- Multi-column layout
- Quick navigation links
- Social media integration
- Copyright information

## Browser Compatibility

**Fully Supported:**
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+
- Opera 76+

**Mobile Browsers:**
- iOS Safari 14+
- Chrome Mobile 90+
- Samsung Internet 14+

**Requirements:**
- CSS Grid and Flexbox support
- ES6 JavaScript support
- Bootstrap 5 compatibility

## Change Log

### Version 1.0.0 (Current)

**Features:**
- Responsive navigation with scrollspy
- Hero section with overlay effect
- Featured products section (3 items)
- Full product catalog (10+ items)
- About section with brand story
- Contact information display
- Responsive design for all devices
- Hover effects and animations
- Bootstrap 5 integration
- Font Awesome icons

**Known Limitations:**
- Shopping cart functionality not implemented
- No product detail pages
- Contact form not functional
- No backend integration
- Images are placeholders

### Planned Features

**Version 1.1.0:**
- Shopping cart functionality
- Product quick view modal
- Image gallery/lightbox
- Product filtering and sorting

**Version 2.0.0:**
- Backend integration
- User authentication
- Payment gateway integration
- Admin dashboard
- Order management system

**Version 2.1.0:**
- Product reviews and ratings
- Wishlist functionality
- Advanced search
- Newsletter subscription

## Performance Optimization

Current optimizations:
- CDN-hosted libraries for faster loading
- Optimized image sizes
- Minimal custom JavaScript
- CSS minification ready
- Lazy loading compatible

Recommended improvements:
- Implement image lazy loading
- Minify CSS and JavaScript
- Use WebP image format
- Add service worker for offline support
- Implement critical CSS

## License and Author Info

### License

This project is licensed under the MIT License.

### Author

**[Rahaf Muhammad Tariq]**
- GitHub: [@Rahaf-Tariq](https://github.com/Rahaf-Tariq)
- Email: rahafkhan510@gmail.com

### Acknowledgments

- **Bootstrap Team**: For the excellent UI framework
- **Font Awesome**: For comprehensive icon library
- **Unsplash/Pexels**: For product image placeholders (if used)
- Design inspiration from modern e-commerce platforms

### Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](https://github.com/Rahaf-Tariq/riona-jewels/issues) if you want to contribute.

### Support

If you found this project helpful:
- Give it a star on GitHub
- Share it with others
- Report bugs or suggest features
- Contribute to the codebase

---


