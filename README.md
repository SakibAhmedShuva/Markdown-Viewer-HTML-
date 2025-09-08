# Markdown Viewer HTML

A lightweight, client-side markdown viewer that allows you to browse and render markdown files from your local file system directly in your web browser.

## ✨ Features

- **📁 Folder-based Navigation** - Select entire directories containing markdown files
- **🖼️ Image Support** - Automatically resolves and displays relative image paths
- **📱 Responsive Design** - Clean, GitHub-flavored styling that works on all devices
- **⚡ Fast Performance** - Client-side rendering with efficient file caching
- **🎯 No Dependencies** - Self-contained HTML file with CDN resources
- **🔒 Privacy-First** - Everything runs locally in your browser

## 🚀 Quick Start

1. **Download** the `viewer.html` file from this repository
2. **Place** it in your markdown project folder
3. **Open** `viewer.html` in your web browser
4. **Click** "Select Markdown Folder" and choose your directory
5. **Browse** your markdown files in the sidebar

## 📋 Requirements

- Modern web browser (Chrome, Firefox, Safari, Edge)
- No server or installation required
- Internet connection for CDN resources (marked.js and GitHub markdown CSS)

## 🏗️ Repository Structure

```
Markdown-Viewer-HTML/
├── README.md
└── viewer.html          # The markdown viewer
```

## 🎨 Features in Detail

### Markdown Rendering
- GitHub-flavored markdown styling
- Syntax highlighting support
- Tables, lists, and code blocks
- Headers with proper hierarchy

### Image Handling
- Automatic resolution of relative image paths
- Efficient blob URL caching for performance
- Support for common image formats (PNG, JPG, GIF, SVG)
- Graceful fallback for missing images

### User Interface
- Clean, minimal sidebar navigation
- Active file highlighting
- Responsive layout that adapts to screen size
- Smooth scrolling and hover effects

## 🛠️ Technical Details

### Built With
- **Vanilla JavaScript** - No frameworks required
- **marked.js** - Markdown parsing and rendering
- **GitHub Markdown CSS** - Professional styling
- **File API** - Local file system access

### Browser Compatibility
- Chrome 21+
- Firefox 42+
- Safari 11.1+
- Edge 79+

## 📖 Usage

1. Download `viewer.html` from this repository
2. Copy it to any folder containing your markdown files
3. Open the HTML file in your browser
4. Use the "Select Markdown Folder" button to browse your `.md` files

The viewer will automatically scan for all `.md` files and create a navigable sidebar.

## 🔧 Customization

### Styling
The viewer uses GitHub markdown CSS by default. You can customize the appearance by:
1. Modifying the CSS variables in the `<style>` section
2. Overriding GitHub markdown CSS classes
3. Adding your own custom styles

### Configuration
Key customizable elements:
- Sidebar width: Adjust the `width` property in `#sidebar`
- Color scheme: Modify background colors and hover states
- Typography: Change font families in the `body` selector

## 🤝 Contributing

Contributions are welcome! Here are some ways you can help:

1. **🐛 Bug Reports** - Found an issue? Please open an issue with details
2. **💡 Feature Requests** - Have ideas for improvements? Let's discuss them
3. **🔧 Code Contributions** - Submit pull requests for bug fixes or new features
4. **📚 Documentation** - Help improve this README or add examples

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- [marked.js](https://marked.js.org/) - Fast markdown parser
- [GitHub Markdown CSS](https://github.com/sindresorhus/github-markdown-css) - Beautiful GitHub-style CSS
- Web File API - For local file system access

## 📞 Support

If you encounter any issues or have questions:

1. Check the [Issues](../../issues) page for similar problems
2. Create a new issue with detailed information
3. Include your browser version and operating system

---

**Made with ❤️ for the markdown community**
