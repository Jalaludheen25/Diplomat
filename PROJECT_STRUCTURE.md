# Diplomat Project Structure

```
Diplomat/
├── index.html              # Main HTML file
├── styles.css              # Custom CSS styles
├── assets/                 # Assets directory
│   └── images/            # Images directory
│       ├── logo.png       # Company logo (navigation)
│       ├── logo-text.png  # Company name logo with text
│       ├── favicon.ico    # Browser favicon
│       └── README.md      # Image specifications guide
├── PROJECT_STRUCTURE.md   # This file
└── README.md              # Project documentation
```

## Setup Instructions

### 1. Add Your Logo Files

Place your logo files in the `assets/images/` directory:

- **logo.png** - Your company logo for the navigation bar
  - Recommended size: 150-200px width
  - Format: PNG with transparent background (or SVG)
  
- **logo-text.png** - Company name logo with text (optional)
  - Recommended size: 200-300px width
  - Format: PNG with transparent background (or SVG)
  
- **favicon.ico** - Browser tab icon
  - Size: 32x32px or 64x64px
  - Format: ICO or PNG

### 2. Logo Usage in HTML

The logo is referenced in two places:

1. **Navigation Bar** (line ~20 in index.html):
   ```html
   <img src="assets/images/logo.png" alt="Diplomat Logo" class="h-12 w-auto">
   ```

2. **Favicon** (line ~7 in index.html):
   ```html
   <link rel="icon" type="image/x-icon" href="assets/images/favicon.ico">
   ```

### 3. Using SVG Instead of PNG

If you prefer SVG format (recommended for better quality):

1. Save your logo as `logo.svg`
2. Update the image source in index.html:
   ```html
   <img src="assets/images/logo.svg" alt="Diplomat Logo" class="h-12 w-auto">
   ```

### 4. Adjusting Logo Size

To change the logo size, modify the `h-12` class in the img tag:
- `h-8` = 32px height
- `h-10` = 40px height
- `h-12` = 48px height (current)
- `h-16` = 64px height
- `h-20` = 80px height

## File Descriptions

- **index.html** - Main webpage with all sections
- **styles.css** - Custom styles for hover effects, gradients, and responsive design
- **assets/images/** - Directory for all image assets

## Technologies Used

- HTML5
- Tailwind CSS (via CDN)
- Font Awesome Icons
- Custom CSS

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
