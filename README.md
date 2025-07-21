# Tailwind Demo - Dark Theme Website

A modern, responsive website built with Tailwind CSS featuring a beautiful dark theme and smooth animations.

## Features

- 🌙 **Dark Theme by Default** - Beautiful dark color scheme with smooth transitions
- 📱 **Fully Responsive** - Looks great on all devices and screen sizes
- ⚡ **Fast Performance** - Optimized CSS with minimal bundle size
- 🎨 **Modern Design** - Clean, professional layout with attention to detail
- 🔄 **Theme Toggle** - Switch between light and dark modes
- 🎯 **Accessible** - Built with accessibility best practices

## Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn

### Installation

1. Clone or download this project
2. Install dependencies:
   ```bash
   npm install
   ```

### Development

1. Start the development server:
   ```bash
   npm run dev
   ```

2. Open `src/index.html` in your browser to view the website

### Building for Production

1. Build the CSS:
   ```bash
   npm run build
   ```

2. The compiled CSS will be available in `dist/output.css`

## Project Structure

```
tailwinddemo/
├── src/
│   ├── index.html          # Main HTML file
│   └── input.css           # Tailwind CSS input file
├── dist/                   # Compiled CSS output (generated)
├── package.json            # Project dependencies and scripts
├── tailwind.config.js      # Tailwind configuration
└── README.md              # This file
```

## Customization

### Colors
The dark theme colors can be customized in `tailwind.config.js` under the `theme.extend.colors.dark` section.

### Components
Custom component classes are defined in `src/input.css` under the `@layer components` section.

### Theme Toggle
The theme toggle functionality is implemented in JavaScript at the bottom of `src/index.html`.

## Technologies Used

- **Tailwind CSS** - Utility-first CSS framework
- **Inter Font** - Modern, readable typeface
- **Vanilla JavaScript** - For theme toggle functionality

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is open source and available under the [MIT License](LICENSE).

## Contributing

Feel free to submit issues and enhancement requests! 