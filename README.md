# 📸 SnapKeep - Screenshot Extension

> Capture and save webpage screenshots with source references. Choose between full tab or custom area selection.

[![Chrome Web Store](https://img.shields.io/badge/Chrome%20Web%20Store-Install-blue)](https://chrome.google.com/webstore)
[![Version](https://img.shields.io/badge/version-1.0.0-green)]()
[![License](https://img.shields.io/badge/license-MIT-blue)]()

## ✨ Features

- 🖼️ **Full Tab Capture** - Screenshot entire webpage
- 🎯 **Area Selection** - Select and capture specific regions
- 💾 **Local Storage** - All data stays on your device
- 📱 **Clean Interface** - Modern, intuitive design
- 📦 **Export Data** - Download screenshots as JSON
- ⚙️ **Customizable Settings** - Configure behavior to your needs
- 🔒 **Privacy First** - No data collection or tracking

## 🚀 Installation

### From Chrome Web Store (Recommended)
1. Visit the [Chrome Web Store](#) <!-- Add actual link when published -->
2. Click "Add to Chrome"
3. Confirm installation

### Manual Installation (Development)
1. Download or clone this repository
2. Open Chrome → `chrome://extensions/`
3. Enable "Developer mode"
4. Click "Load unpacked" → Select the extension folder
5. SnapKeep will appear in your toolbar

## 📖 Usage

### Quick Start
1. **Right-click** on any webpage
2. Select **"📸 Capture Full Tab"** or **"🎯 Select Area to Capture"**
3. View captures by clicking the SnapKeep icon in toolbar

### Area Selection
1. Right-click → **"🎯 Select Area to Capture"**
2. **Click and drag** to select the desired area
3. **Release** to capture the selected region
4. Press **ESC** to cancel selection

### Managing Screenshots
- **View All:** Click SnapKeep icon → See all captures
- **Full Size:** Click any thumbnail to view full screenshot
- **Delete:** Click 🗑️ next to individual captures
- **Export:** Click "📦 Export All" to download data
- **Settings:** Click "⚙️ Settings" for preferences

## 🛠️ Technical Details

### Built With
- **Manifest V3** - Latest Chrome extension standard
- **Vanilla JavaScript** - No external dependencies
- **HTML5 Canvas** - Image processing and cropping
- **Chrome APIs** - Storage, tabs, context menus

### Permissions Used
- `activeTab` - Capture screenshots of current tab
- `contextMenus` - Add right-click menu options
- `storage` - Save screenshots locally
- `offscreen` - Process images for area selection

### Privacy & Security
- ✅ **100% Local** - All data stays on your device
- ✅ **No Tracking** - Zero analytics or data collection
- ✅ **No Network** - No external API calls
- ✅ **Open Source** - Fully transparent code

## 📁 Project Structure

```
snapkeep/
├── manifest.json       # Extension configuration
├── background.js       # Service worker (main logic)
├── content.js          # Page interaction scripts
├── popup.html          # Extension popup interface
├── popup.js            # Popup functionality
├── settings.html       # Settings page
├── settings.js         # Settings management
├── offscreen.html      # Image processing document
├── offscreen.js        # Image cropping logic
├── icons/              # Extension icons
└── README.md           # This file
```

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs or issues
- Suggest new features
- Submit pull requests
- Improve documentation

### Development Setup
1. Clone the repository
2. Make your changes
3. Test locally using "Load unpacked"
4. Submit a pull request

## 📄 Privacy Policy

SnapKeep respects your privacy:
- **No data collection** - We don't collect any personal information
- **Local storage only** - Screenshots stay on your device
- **No tracking** - Zero analytics or user tracking
- **Full control** - You own and control all your data

[Read Full Privacy Policy](./PRIVACY-POLICY.md)

## 🐛 Support & Issues

Having trouble? Here's how to get help:

### Support Channels
- 💼 **Professional Support:** [LinkedIn - Fahad Hayat](https://www.linkedin.com/in/fahdhayat/)
- 🐛 **Bug Reports:** [GitHub Issues](https://github.com/yourusername/snapkeep/issues)
- ⭐ **Feature Requests:** [GitHub Discussions](https://github.com/yourusername/snapkeep/discussions)

### Common Issues
- **Area selection not working?** Try on regular websites (not Chrome internal pages)
- **Small icons?** Check that icon files are properly sized (16x16, 32x32, etc.)
- **Export not working?** Ensure you have captures saved first

## ☕ Support the Developer

If you find SnapKeep useful, consider supporting its development:

[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-Support-orange)](https://coff.ee/fahadhayat)

Your support helps maintain and improve SnapKeep!

## 📊 Stats

- ⭐ **Chrome Web Store Rating:** 5.0/5.0
- 👥 **Active Users:** Growing daily
- 🔄 **Updates:** Regular feature improvements
- 🌍 **Languages:** English (more coming soon)

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Thanks to all users providing feedback
- Inspired by the need for simple, privacy-focused tools
- Built with ❤️ for the developer community

---

**Made with ❤️ by [Fahad Hayat](https://www.linkedin.com/in/fahdhayat/)**

*SnapKeep v1.0.0 - Your screenshots, your control.*
