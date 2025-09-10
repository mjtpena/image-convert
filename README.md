# 🖼️ Image Converter

A modern, feature-rich web application for converting images between different formats instantly in your browser. No server uploads required - everything works client-side for maximum privacy and speed.

## ✨ Features

### Core Functionality
- **Multi-format Support**: Convert between JPG, PNG, WEBP, GIF, and BMP formats
- **Batch Processing**: Convert multiple images at once with ZIP download
- **Image Resizing**: Resize images with preset dimensions or custom values
- **Quality Control**: Adjust compression quality for JPEG and WEBP formats
- **File Size Comparison**: See before/after file sizes

### User Experience
- **Drag & Drop Interface**: Intuitive drag-and-drop file upload
- **Real-time Preview**: Instant image preview with file information
- **Progress Tracking**: Visual progress bars for batch operations
- **Error Handling**: User-friendly error messages and validation
- **Keyboard Shortcuts**: ESC to reset, Enter to convert
- **Responsive Design**: Works perfectly on desktop and mobile devices

### Advanced Features
- **PWA Support**: Install as a desktop/mobile app
- **Offline Functionality**: Works without internet connection
- **No Data Upload**: All processing happens in your browser
- **Privacy First**: Images never leave your device

## 🚀 Live Demo

[**Try it now!**](https://yourusername.github.io/image-convert) ← Replace with your GitHub Pages URL

## 📸 Screenshots

### Desktop Interface
![Desktop Screenshot](screenshot-desktop.png)

### Mobile Interface  
![Mobile Screenshot](screenshot-mobile.png)

### Batch Processing
![Batch Processing](screenshot-batch.png)

## 🛠️ Installation & Usage

### Online Usage
Simply visit the live demo link above - no installation required!

### Local Development
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/image-convert.git
   cd image-convert
   ```

2. Open `index.html` in your browser or serve with a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Using PHP
   php -S localhost:8000
   ```

3. Navigate to `http://localhost:8000`

### PWA Installation
1. Visit the web app in Chrome, Edge, or Safari
2. Look for the "Install" button in the address bar
3. Click "Install" to add it to your device

## 📱 PWA Features

When installed as a PWA, the app provides:
- **Offline Access**: Use without internet connection
- **Native App Feel**: Standalone window without browser UI
- **Fast Loading**: Cached resources for instant startup
- **Cross-Platform**: Works on Windows, Mac, Linux, iOS, and Android

## 🔧 Technical Details

### Technologies Used
- **Vanilla JavaScript**: No frameworks, pure performance
- **HTML5 Canvas**: Client-side image processing
- **CSS3**: Modern styling with animations and gradients
- **PWA APIs**: Service Workers and Web App Manifest
- **JSZip**: Creating ZIP archives for batch downloads

### Browser Support
- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 11+
- ✅ Edge 79+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

### Performance
- **Client-side Processing**: No server required, instant conversions
- **Memory Efficient**: Processes one image at a time in batch mode
- **Progressive Enhancement**: Core functionality works without JavaScript

## 🎯 How to Use

### Single Image Conversion
1. **Upload**: Drag & drop an image or click to browse
2. **Select Format**: Choose your desired output format
3. **Adjust Settings**: Set quality (for JPEG/WEBP) or resize options
4. **Convert**: Click the convert button
5. **Download**: Download your converted image

### Batch Processing
1. **Enable Batch Mode**: Check the "Batch mode" checkbox
2. **Add Images**: Upload multiple images at once
3. **Remove Unwanted**: Click "Remove" on any unwanted images
4. **Configure**: Select format and options for all images
5. **Convert All**: Process all images into a ZIP file
6. **Download ZIP**: Get all converted images in one download

### Resize Options
- **Preset Sizes**: Quick selection (1920×1080, 1280×720, etc.)
- **Custom Dimensions**: Set exact width and height
- **Aspect Ratio**: Maintain proportions by setting only width or height
- **Quality Control**: Adjust compression (10-100%)

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. **Commit** your changes (`git commit -m 'Add amazing feature'`)
4. **Push** to the branch (`git push origin feature/amazing-feature`)
5. **Open** a Pull Request

### Ideas for Contributions
- 📸 Add more image formats (AVIF, HEIC, TIFF)
- 🎨 Implement image filters (brightness, contrast, saturation)
- 🔧 Add advanced resize options (crop, fit modes)
- 🌐 Internationalization support
- ♿ Accessibility improvements
- 📱 Enhanced mobile experience

## 🐛 Bug Reports

Found a bug? Please open an issue with:
- **Browser** and version
- **Steps** to reproduce
- **Expected** vs actual behavior
- **Screenshots** if applicable

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **JSZip Library**: For creating ZIP archives
- **Canvas API**: For client-side image processing  
- **Web APIs**: For PWA functionality and file handling
- **Community**: For feature requests and bug reports

## 🔗 Links

- **Demo**: [Live Application](https://yourusername.github.io/image-convert)
- **Repository**: [GitHub](https://github.com/yourusername/image-convert)
- **Issues**: [Bug Reports](https://github.com/yourusername/image-convert/issues)
- **Discussions**: [Feature Requests](https://github.com/yourusername/image-convert/discussions)

---

Made with ❤️ for the open source community

**Enjoy converting your images!** 🎉