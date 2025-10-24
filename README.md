# Fixar

A modern, minimal bookmark manager with drag-and-drop folder organization. Built with vanilla JavaScript, Bootstrap 5, and GSAP animations.

![Fixar Banner](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3.0-purple.svg)
![GSAP](https://img.shields.io/badge/GSAP-3.12.2-green.svg)

## ✨ Features

- **📁 Smart Folder Organization** - Drag containers onto each other to create folders
- **🎯 Container System** - Organize bookmarks in collapsible containers
- **🔍 Instant Search** - Search across all bookmarks, tags, and URLs
- **🏷️ Tag Support** - Add tags to categorize your bookmarks
- **🎨 Custom Colors** - Personalize containers with custom colors
- **📥 Import/Export** - Support for JSON and browser HTML bookmarks
- **🌊 Smooth Animations** - GSAP-powered animations for a premium feel
- **📱 Fully Responsive** - Works perfectly on desktop, tablet, and mobile
- **💾 Local Storage** - All data saved locally in your browser
- **⚡ No Backend Required** - Completely client-side application

## 🚀 Quick Start

### Option 1: Direct Use (Recommended)
1. Download the `fixar.html` file
2. Open it in your browser
3. Start organizing your bookmarks!

### Option 2: Host It Yourself
```bash
# Clone the repository
git clone https://github.com/jorge-brizio/fixar.git

# Navigate to the directory
cd fixar

# Open in browser
open fixar.html
# or serve with any static server
python -m http.server 8000
```

### Option 3: GitHub Pages
1. Fork this repository
2. Go to Settings → Pages
3. Enable GitHub Pages from main branch
4. Access at `https://yourusername.github.io/fixar`

## 🎯 Usage

### Creating Containers
1. Enter a container name in the input field
2. Choose a color (optional)
3. Click "Add Container"

### Creating Folders
Simply drag one container onto another to create a folder. Name it, and both containers will be grouped together.

### Managing Bookmarks
- **Add**: Click "Add Bookmark" in any container
- **Edit**: Click the pencil icon on any bookmark
- **Delete**: Click the X icon on any bookmark
- **Sort**: Use the dropdown to sort by date or name
- **Drag**: Reorder bookmarks by dragging the grip handle

### Keyboard Shortcuts
- `Ctrl/Cmd + K` - Focus search (coming soon)
- `Escape` - Close modals

### Import/Export

#### Importing from Chrome/Edge/Firefox:
1. Export bookmarks from your browser (usually `Ctrl+Shift+O` → Menu → Export)
2. Click "Import" in Fixar
3. Select the HTML file

#### Backing Up Your Data:
1. Click "Export" to download a JSON file
2. Keep this file safe - it contains all your bookmarks and folders

## 🛠️ Technologies

- **Bootstrap 5.3.0** - UI Components and Grid System
- **GSAP 3.12.2** - Smooth animations
- **Vanilla JavaScript** - No framework dependencies
- **Local Storage API** - Persistent data storage
- **Bootstrap Icons** - Beautiful icon set

## 📁 Project Structure

```
fixar/
│
├── index.html          # Main application file
├── README.md          # Documentation
├── LICENSE            # MIT License
└── screenshots/       # Screenshots for documentation
    ├── main.png
    ├── folders.png
    └── mobile.png
```

## 🎨 Customization

### Changing the Color Scheme
Edit the CSS variables in the `<style>` section:

```css
:root {
  --bg-primary: #ffffff;
  --bg-secondary: #f8f9fa;
  --text-primary: #212529;
  /* ... more variables */
}
```

### Adding New Features
The codebase is well-commented and modular. Key functions:
- `addContainer()` - Creates new containers
- `createFolderFromContainers()` - Handles folder creation
- `saveBookmark()` - Manages bookmark CRUD operations
- `render()` - Main rendering function

## 📊 Browser Support

- Chrome/Edge (90+)
- Firefox (88+)
- Safari (14+)
- Opera (76+)

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 🐛 Known Issues

- Safari may have slight animation delays
- Large bookmark collections (1000+) may impact performance

## 🗺️ Roadmap

- [ ] Dark mode support
- [ ] Bookmark favicon caching
- [ ] Advanced search filters
- [ ] Bulk bookmark operations
- [ ] Chrome extension
- [ ] Cloud sync option
- [ ] Bookmark sharing
- [ ] Custom themes

## 📄 License

This project is licensed under the MIT License:

```
MIT License

Copyright (c) 2024 Jorge

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 👤 Author

**Jorge**  
📧 Email: [your.email@example.com]  
🔗 GitHub: [@yourusername](https://github.com/yourusername)

## 🌟 Acknowledgments

- Bootstrap team for the amazing CSS framework
- GreenSock for GSAP animations
- The open-source community

## 💖 Support

If you like this project, please give it a ⭐ on GitHub!

---

<p align="center">Made with ❤️ and ☕</p>