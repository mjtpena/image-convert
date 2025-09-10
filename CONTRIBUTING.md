# Contributing to Image Converter

Thank you for your interest in contributing to Image Converter! We welcome contributions from the community.

## How to Contribute

### Reporting Bugs

1. **Check existing issues** to avoid duplicates
2. **Use the bug report template** when creating new issues
3. **Include details** like browser version, steps to reproduce, and screenshots
4. **Be specific** about the expected vs actual behavior

### Suggesting Features

1. **Check existing feature requests** first
2. **Explain the use case** and why it would be valuable
3. **Provide mockups** or detailed descriptions if possible
4. **Consider the impact** on performance and user experience

### Code Contributions

#### Getting Started

1. **Fork** the repository
2. **Clone** your fork locally:
   ```bash
   git clone https://github.com/yourusername/image-convert.git
   cd image-convert
   ```
3. **Create a branch** for your feature:
   ```bash
   git checkout -b feature/your-feature-name
   ```

#### Development Guidelines

- **Keep it simple**: Use vanilla JavaScript when possible
- **Performance matters**: Optimize for speed and memory usage
- **Mobile-first**: Ensure features work on mobile devices
- **Accessibility**: Follow WCAG guidelines
- **Browser support**: Test in Chrome, Firefox, Safari, and Edge
- **No dependencies**: Avoid adding new external libraries unless absolutely necessary

#### Code Style

- Use **consistent indentation** (2 spaces)
- **Semicolons** are required
- Use **camelCase** for variables and functions
- Use **meaningful names** for variables and functions
- **Comment complex logic** but avoid obvious comments
- Keep **functions small** and focused on one task

#### Testing

1. **Test manually** in multiple browsers
2. **Test responsive design** on different screen sizes
3. **Test PWA functionality** (offline mode, installation)
4. **Test batch processing** with various image types and sizes
5. **Test error scenarios** (invalid files, network issues)

#### Submitting Changes

1. **Commit your changes** with clear messages:
   ```bash
   git commit -m "Add resize presets for common social media sizes"
   ```
2. **Push to your fork**:
   ```bash
   git push origin feature/your-feature-name
   ```
3. **Create a Pull Request** with:
   - Clear title and description
   - Screenshots/GIFs of new features
   - Testing notes
   - Any breaking changes

## Development Setup

### Local Development

1. **No build process required** - just open `index.html` in a browser
2. **Use a local server** for PWA features:
   ```bash
   python -m http.server 8000
   # or
   npx serve .
   ```
3. **Enable service worker** in dev tools for offline testing

### File Structure

```
image-convert/
├── index.html          # Main application
├── manifest.json       # PWA manifest
├── sw.js              # Service worker
├── README.md          # Documentation
├── LICENSE            # MIT license
├── CONTRIBUTING.md    # This file
└── .gitignore        # Git ignore rules
```

## Feature Ideas

### High Priority
- **AVIF format support** - Modern image format with better compression
- **HEIC/HEIF support** - iPhone photo format
- **Image filters** - Basic adjustments like brightness, contrast
- **Crop functionality** - Manual and preset aspect ratios
- **Metadata preservation** - Keep EXIF data when possible

### Medium Priority
- **Advanced resize options** - Smart cropping, fit modes
- **Watermark support** - Add text or image watermarks
- **Internationalization** - Multiple language support
- **Dark mode** - User preference for dark theme
- **Keyboard navigation** - Full keyboard accessibility

### Nice to Have
- **Image optimization** - Smart compression algorithms
- **Format recommendations** - Suggest best format for image type
- **Batch rename options** - Custom naming patterns
- **Cloud storage integration** - Direct upload to services
- **API mode** - Programmable interface for developers

## Code of Conduct

- **Be respectful** and inclusive in all interactions
- **Focus on constructive feedback** when reviewing code
- **Help newcomers** and answer questions patiently
- **Acknowledge contributions** from community members

## Questions?

- **Open an issue** for general questions
- **Start a discussion** for feature ideas
- **Contact maintainers** for sensitive issues

Thank you for contributing! 🙏