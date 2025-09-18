# 💕 Funbi-chan's Gallery

A beautiful, modern web gallery built with love featuring a romantic theme, glass morphism design, and responsive layout. This gallery showcases precious memories with an elegant user interface and smooth animations.

![Gallery Preview](https://via.placeholder.com/800x400/1e3a8a/ffffff?text=Funbi-chan%27s+Gallery)

## ✨ Features

### 🎨 **Modern Design**
- **Glass Morphism UI** - Beautiful frosted glass effects with backdrop blur
- **Responsive Grid Layout** - Modern CSS Grid system that adapts to all screen sizes
- **Professional Typography** - Comprehensive font hierarchy with Inter and Playfair Display
- **Smooth Animations** - Polished transitions and micro-interactions throughout

### 📱 **Responsive Design**
- **Mobile-First Approach** - Optimized for all devices from mobile to desktop
- **Adaptive Grid** - 1 column on mobile, up to 5+ columns on large screens
- **Touch-Friendly** - Enhanced controls and interactions for mobile users
- **Progressive Enhancement** - Works great on all modern browsers

### 🖼️ **Gallery Features**
- **Media Support** - Images and videos with lazy loading
- **Advanced Filtering** - Filter by type (All, Videos, Images)
- **Search Functionality** - Real-time search through memories
- **Slideshow Mode** - Full-screen presentation with navigation controls
- **Lightbox View** - Detailed media viewing with metadata
- **Upload Support** - Add new memories directly through the interface

### 💖 **Romantic Elements**
- **Love Counter** - Track favorite memories
- **Floating Hearts** - Animated romantic effects
- **Special Badges** - Anniversary and special moment indicators
- **Memory Tags** - Categorize precious moments
- **Romantic Toasts** - Sweet notification messages

## 🚀 Quick Start

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No server required - runs entirely in the browser!

### Installation
1. **Clone or download** this repository
2. **Open** `index.html` in your web browser
3. **Enjoy** the beautiful gallery experience!

```bash
# If using Git
git clone <repository-url>
cd peters-gallery
open index.html
```

## 📁 Project Structure

```
peters-gallery/
├── index.html              # Landing page with welcome screen
├── peter-gallery.html      # Main gallery interface
├── media/                  # Media files directory
│   ├── funbi1.mp4         # Video files
│   ├── funbi2.mp4
│   ├── ...
│   ├── funbi11.jpeg       # Image files
│   ├── funbi12.jpeg
│   └── ...
├── public/
│   └── favicon.ico        # Site favicon
└── README.md              # This file
```

## 🎯 Usage

### Landing Page (`index.html`)
- **Age Verification** - Ensures appropriate content access
- **Welcome Screen** - Beautiful introduction with video preview
- **Theme Toggle** - Switch between light and dark themes
- **About Modal** - Learn more about the gallery

### Main Gallery (`peter-gallery.html`)
- **Grid View** - Modern masonry-style layout
- **Filter Controls** - Sort by media type
- **Search Bar** - Find specific memories
- **Upload Button** - Add new content
- **Slideshow Mode** - Full-screen presentation
- **Lightbox** - Detailed media viewing

### Keyboard Shortcuts
- `Escape` - Close modals/lightbox
- `Enter` - Enter gallery (from landing page)
- `S` - Focus search bar
- `H` - Show romantic message
- `←` `→` - Navigate slideshow
- `Space` - Play/pause slideshow
- `M` - Toggle metadata panel

## 🛠️ Technical Details

### Technologies Used
- **HTML5** - Semantic markup structure
- **CSS3** - Modern styling with custom properties
- **JavaScript (ES6+)** - Interactive functionality
- **Tailwind CSS** - Utility-first CSS framework
- **Google Fonts** - Typography (Inter, Playfair Display)

### Key Features
- **CSS Grid Layout** - Modern responsive grid system
- **CSS Custom Properties** - Consistent design tokens
- **Backdrop Filter** - Glass morphism effects
- **Intersection Observer** - Lazy loading implementation
- **Local Storage** - Persistent user preferences
- **File API** - Client-side file uploads

### Browser Support
- ✅ Chrome 88+
- ✅ Firefox 87+
- ✅ Safari 14+
- ✅ Edge 88+

## 🎨 Customization

### Adding New Media
1. Place images/videos in the `media/` folder
2. Follow the naming convention: `funbi[number].[extension]`
3. Supported formats: `.mp4`, `.webm`, `.jpeg`, `.jpg`, `.png`, `.webp`

### Modifying Colors
Edit the CSS custom properties in both HTML files:
```css
:root {
  --primary-500: #3b82f6;    /* Main blue */
  --secondary-500: #22c55e;  /* Accent green */
  --accent-500: #ec4899;     /* Romantic pink */
}
```

### Changing Typography
Update the font imports and custom properties:
```css
/* Google Fonts import */
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=Playfair+Display:wght@700&display=swap');

/* Typography scale */
:root {
  --font-size-base: 1rem;
  --font-size-lg: 1.125rem;
  /* ... more sizes */
}
```

## 🔧 Development

### Local Development
1. Open `index.html` in your browser
2. Use browser dev tools for debugging
3. Modify files and refresh to see changes
4. No build process required!

### Adding Features
- **New Animations**: Add CSS keyframes and classes
- **Additional Filters**: Extend the filtering system
- **Custom Themes**: Create new color schemes
- **Media Types**: Support additional file formats

## 📱 Mobile Optimization

- **Touch Gestures** - Swipe navigation in slideshow
- **Responsive Images** - Optimized loading for mobile
- **Touch-Friendly Controls** - Larger tap targets
- **Performance** - Lazy loading and image optimization

## 🎭 Themes

### Dark Theme (Default)
- Deep blue gradient background
- Glass morphism with blue tints
- White text with opacity variations
- Romantic pink accents

### Light Theme
- Soft pastel gradient background
- Light glass effects
- Dark text for contrast
- Maintained romantic elements

## 💝 Special Features

### Romantic Elements
- **Floating Hearts** - Animated heart particles
- **Love Messages** - Hidden romantic notifications
- **Memory Tags** - Categorize special moments
- **Anniversary Badges** - Mark important dates
- **Romantic Cursor Trail** - Magical mouse effects

### Interactive Elements
- **Magnetic Buttons** - Buttons that respond to mouse proximity
- **Ripple Effects** - Material design-inspired interactions
- **Hover Animations** - Smooth 3D transforms
- **Loading States** - Beautiful skeleton screens

## 🚀 Performance

- **Lazy Loading** - Images load as they come into view
- **Thumbnail Generation** - Optimized preview images
- **Memory Management** - Efficient resource handling
- **Smooth Animations** - 60fps transitions using CSS transforms

## 📄 License

This project is created with love and is intended for personal use. Feel free to use it as inspiration for your own projects!

## 💌 Credits

- **Design Inspiration** - Modern glass morphism trends
- **Typography** - Google Fonts (Inter, Playfair Display)
- **Icons** - Custom emoji and Unicode symbols
- **Animations** - CSS3 and JavaScript interactions

---

**Made with 💙 for Funbi-chan**

*Every memory tells a story, and every story deserves to be told beautifully.*
