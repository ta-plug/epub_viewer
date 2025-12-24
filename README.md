# EPUB Viewer

A simple and user-friendly web-based EPUB reader application. Read EPUB files directly in your browser.

## Features

- 📖 **EPUB Format Support** - Read standard EPUB format ebooks
- 🌓 **Dark Mode** - Eye-friendly dark mode support
- 📱 **Responsive Design** - Works on desktop, tablet, and mobile devices
- 🔖 **Bookmark Functionality** - Save your favorite pages
- 🔍 **Full-text Search** - Search for text within the book
- 📑 **Table of Contents Navigation** - Quick navigation between chapters
- 🎨 **Customizable** - Adjust accent color, text color, and font size
- 📄 **Spread/Single Page Toggle** - Choose your preferred display mode
- 🌐 **Multi-language Support** - Supports English, Chinese, and Japanese
- 💾 **Works Locally** - Everything runs in the browser, data saved in localStorage

## Demo

View the live demo on GitHub Pages:
[https://[your-username].github.io/[repository-name]/epub-viewer.html](https://[your-username].github.io/[repository-name]/epub-viewer.html)

## Usage

### Online Usage

1. Visit the [GitHub Pages version](https://[your-username].github.io/[repository-name]/epub-viewer.html)
2. Drag and drop an EPUB file, or click the "Open" button to select a file
3. Enjoy reading!

### Local Usage

1. Download `epub-viewer.html`
2. Open the file in your browser
3. Load an EPUB file and start reading

## Feature Details

### Navigation
- **Keyboard Controls**: Use left/right arrow keys to navigate pages
- **Mouse Controls**: Click navigation buttons on the sides of the screen
- **Progress Bar**: Click anywhere on the progress bar to jump to that position

### Bookmarks
- Click the bookmark button to save the current page
- Access saved positions from the "Bookmarks" tab in the sidebar
- View date and progress percentage for each bookmark

### Search Functionality
- Search the book text from the "Search" tab in the sidebar
- Real-time search results display
- Click on search results to jump to that location

### Customization
- **Theme**: Toggle between light and dark mode
- **Accent Color**: Choose from 10 color palette options
- **Text Color**: Adjust to a comfortable reading color
- **Font Size**: Adjust between 80% and 150%

## Supported Browsers

- Chrome/Edge (Recommended)
- Firefox
- Safari
- Other modern browsers

## Technology Stack

- **HTML5/CSS3/JavaScript** - Frontend
- **Epub.js** - EPUB file parsing and rendering
- **JSZip** - EPUB (ZIP format) file decompression
- **localStorage** - Settings and bookmark persistence

## License

This project is free to use.

For third-party library licenses, see [THIRD_PARTY_LICENSES.md](THIRD_PARTY_LICENSES.md).

## Contributing

Bug reports and feature requests are welcome on GitHub Issues.
Pull requests are also welcome!

## Privacy

- All data is stored in the browser's localStorage
- No data is sent to any server
- Works completely offline

## Troubleshooting

### EPUB file won't load
- Verify the file is not corrupted
- Ensure you're using a supported browser
- Check the browser console for error messages

### Settings aren't being saved
- Verify that localStorage is enabled in your browser
- Settings are not saved in private browsing mode

## Future Plans

- [ ] PDF export functionality
- [ ] Highlight feature
- [ ] Notes and annotations
- [ ] Cloud synchronization
- [ ] Support for more languages

---

Made with ❤️ for book lovers
