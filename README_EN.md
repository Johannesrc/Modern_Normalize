# Modern Normalize Enhanced

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![SCSS](https://img.shields.io/badge/SCSS-v3.0.3-pink.svg)]()
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)]()

A modern, enhanced SCSS version of [modern-normalize](https://github.com/sindresorhus/modern-normalize) that makes browsers render elements more consistently while adhering to modern web standards.

## 🚀 Features

- Written in SCSS for better maintainability and customization
- Removes deprecated vendor prefixes and non-standard properties
- Enhanced accessibility features
- Improved form element normalization
- Better media element handling
- Modern focus management
- Built-in responsive design considerations

## 📦 Installation

```bash
# Using npm
npm install modern-normalize-enhanced

# Using yarn
yarn add modern-normalize-enhanced

# Using pnpm
pnpm add modern-normalize-enhanced
```

## 🔧 Usage

### SCSS

```scss
@import "modern-normalize-enhanced";
```

### CSS

```html
<link rel="stylesheet" href="modern-normalize-enhanced.css" />
```

## 🆚 Key Differences from Original

### 1. Architecture & Organization

- **Original:** Plain CSS with basic organization
- **Enhanced:**
  - SCSS-based architecture
  - Modular structure with variables and mixins
  - Better code organization with logical grouping

### 2. Modern Properties

- **Original:** Includes vendor prefixes and some non-standard properties
- **Enhanced:**
  - Removed deprecated `-webkit-appearance`
  - Uses modern `appearance` property
  - Updated text rendering properties
  - Modern focus management with `:focus-visible`

### 3. Features Added

- Responsive media handling
- Enhanced accessibility features
- Modern selection styles
- Improved form element normalization
- Better table defaults
- Scroll behavior normalization
- ARIA state handling

### 4. Variables & Customization

- **Original:** Limited CSS variables
- **Enhanced:**

```scss
$system-fonts: system-ui, -apple-system, "Segoe UI"...;
$monospace-fonts: ui-monospace, SFMono-Regular...;
$base-line-height: 1.15;
```

## 🎯 Browser Support

- Chrome ≥ 60
- Firefox ≥ 60
- Safari ≥ 12
- Edge ≥ 79

## 📚 Documentation

### Base Reset

```scss
*,
::before,
::after {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  border: 0;
}
```

### Typography

- Improved font stacks for system and monospace fonts
- Better text rendering
- Enhanced sub/sup handling

### Forms

- Modern form element normalization
- Improved button styles
- Better input handling
- Accessible form elements

### Media

- Responsive image handling
- Better video and iframe defaults
- Audio element normalization

## 🤝 Contributing

1. Fork it
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 Best Practices

1. **Custom Properties**

```scss
// Use variables for consistent values
$base-line-height: 1.15;
```

2. **Media Elements**

```scss
// Always include responsive defaults
img {
  max-width: 100%;
  height: auto;
}
```

3. **Accessibility**

```scss
// Include ARIA state handling
[aria-disabled="true"] {
  cursor: not-allowed;
}
```

## 🔍 Testing

```bash
# Run tests
npm test

# Run linting
npm run lint

# Check formatting
npm run format
```

## 📋 TODO

- [ ] Add RTL support
- [ ] Enhance dark mode compatibility
- [ ] Add CSS Grid normalization
- [ ] Improve print styles

## 🎯 Roadmap

- **v3.1.0** - Add CSS Grid normalization
- **v3.2.0** - Enhanced dark mode support
- **v3.3.0** - RTL support
- **v4.0.0** - Complete modernization of all properties

## 📜 License

This project is based on [modern-normalize](https://github.com/sindresorhus/modern-normalize) by Sindre Sorhus.
Licensed under the MIT License - see the [LICENSE](LICENSE) file for details

## 🙏 Acknowledgments

- [Sindre Sorhus](https://github.com/sindresorhus) for the original modern-normalize
- [Nicolas Gallagher](https://github.com/necolas) for Normalize.css
- All contributors who have helped improve this project

---

## 💡 Usage Tips

### Import Order

```scss
// 1. Modern Normalize Enhanced
@import "modern-normalize-enhanced";

// 2. Your variables
@import "variables";

// 3. Your styles
@import "styles";
```

### Customization

```scss
// Override default variables
$base-line-height: 1.6;
$system-fonts: "Your Custom Font Stack";
```

---

Made with ❤️ by Johannes Rosenkranz
