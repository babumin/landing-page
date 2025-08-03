# The Blog - A Web Personal Blog Landing Page

A modern, responsive blog landing page built from a Figma design with exact layout, colors, and styling.

## Features

- **Exact Figma Design Implementation**: Pixel-perfect recreation of the original design
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Dark Mode Toggle**: Interactive theme switching with persistent preferences
- **Modern Animations**: Smooth hover effects and scroll animations
- **Semantic HTML**: Accessible and SEO-friendly markup
- **Clean CSS**: Well-organized styles with CSS custom properties

## Design Elements

### Layout Structure
- **Header**: Navigation bar with logo, menu items, and dark mode toggle
- **Hero Section**: Large "THE BLOG" title with decorative border
- **Recent Blog Posts**: Featured post with side posts layout
- **Grid System Section**: Horizontal blog post layout
- **All Blog Posts**: 3-column grid layout with pagination
- **Footer**: Copyright and social links

### Color Scheme
- **Primary Text**: #1A1A1A (Dark Gray)
- **Secondary Text**: #667085 (Medium Gray)
- **Accent Color**: #6941C6 (Purple)
- **Background**: #FFFFFF (White)
- **Badge Colors**: Various semantic colors for categories

### Typography
- **Font Family**: Inter (Google Fonts)
- **Weights**: 400 (Regular), 500 (Medium), 600 (Semi-bold), 700 (Bold)
- **Responsive Sizing**: Scales appropriately across devices

## File Structure

```
figma-blog/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
├── images/             # Blog post images and icons
│   ├── blog-post-1.png
│   ├── blog-post-2.png
│   └── ...
└── README.md           # Project documentation
```

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript (ES6+)**: Interactive functionality
- **Google Fonts**: Inter font family
- **Figma API**: Design extraction and asset download

## Getting Started

1. **Clone or Download**: Get the project files
2. **Open in Browser**: Open `index.html` in a modern web browser
3. **Explore**: Navigate through the different sections and test the dark mode toggle

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Responsive Breakpoints

- **Desktop**: 1280px and above
- **Tablet**: 768px - 1279px
- **Mobile**: Below 768px

## Features in Detail

### Dark Mode
- Toggle between light and dark themes
- Persistent preference storage using localStorage
- Smooth transitions between themes
- Proper color contrast in both modes

### Interactive Elements
- Hover effects on blog cards
- Clickable pagination buttons
- Smooth scrolling navigation
- Loading animations for images

### Accessibility
- Semantic HTML structure
- Proper heading hierarchy
- Alt text for images
- Keyboard navigation support
- Screen reader friendly

## Customization

### Colors
Modify the CSS custom properties in `styles.css` to change the color scheme:

```css
:root {
    --primary-color: #1A1A1A;
    --secondary-color: #667085;
    --accent-color: #6941C6;
    --background-color: #FFFFFF;
}
```

### Content
Update the blog posts in `index.html` by modifying:
- Blog post titles and excerpts
- Author names and dates
- Category badges
- Image sources

### Layout
Adjust the grid layouts and spacing in `styles.css` to match your preferences.

## Performance

- Optimized images for web
- Minimal JavaScript for fast loading
- Efficient CSS with minimal redundancy
- Responsive images with appropriate sizing

## License

This project is created for educational and portfolio purposes. The design is based on a Figma community template.

## Credits

- **Design**: Figma Community Template
- **Fonts**: Inter by Google Fonts
- **Icons**: Custom SVG icons
- **Images**: Sample blog post images

---

Built with ❤️ using modern web technologies 