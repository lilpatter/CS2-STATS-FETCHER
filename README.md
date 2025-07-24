# CS2 Stats Fetcher

![CS2 Stats Fetcher](https://img.shields.io/badge/CS2-Stats%20Fetcher-orange?style=for-the-badge&logo=steam)
![Version](https://img.shields.io/badge/version-1.0.0-green?style=for-the-badge)
![Platform](https://img.shields.io/badge/platform-Windows-blue?style=for-the-badge&logo=windows)

**A powerful desktop application for fetching comprehensive Counter-Strike 2 player statistics from Faceit and Leetify.**

## 📥 **Download**
**[⬇️ Download Latest Release](../../releases/latest)** • **Requirements:** Windows 10/11 (64-bit), Steam logged in

## 🚀 **Key Features**
- 🎯 **Auto-detect recent CS2 players** and fetch their stats instantly
- 📊 **Faceit & Leetify integration** - ELO, skill levels, detailed analytics
- 🖥️ **Modern dark UI** with real-time progress tracking
- ⚡ **Portable executable** - no installation required

## 🎮 **How to Use**
1. **Download and run** the executable
2. **Play CS2 matches** as usual
3. **Click "Fetch Recent Players"** to see comprehensive stats
4. **Toggle Manual Mode** to search specific players by Steam ID

## 🔧 **Technical Info**
**Architecture:** C++ backend + Electron frontend • **APIs:** Steam, Faceit, Leetify • **Privacy:** All processing local, no data stored • **Distribution:** Official releases only

## 📋 **System Requirements** 
**Minimum:** Windows 10 (64-bit), 4GB RAM, Steam logged in • **Recommended:** Windows 11, 8GB+ RAM

---

## 🐛 Troubleshooting

### Common Issues

**"No recent players found"**
- Ensure Steam is running and you're logged in
- Play at least one CS2 match before fetching
- Check that Steam is not in offline mode

**"API rate limit exceeded"**
- Wait a few minutes before trying again
- Faceit/Leetify APIs have rate limiting
- Try fetching fewer players at once

**"Backend server not responding"**
- Restart the application
- Check Windows Firewall settings
- Ensure port 18080 is not blocked

**Application won't start**
- Install [Microsoft Visual C++ Redistributable](https://aka.ms/vs/17/release/vc_redist.x64.exe)
- Run as Administrator if needed
- Check antivirus software isn't blocking the executable

---

## 🤝 Contributing

We welcome community input! Here's how you can help:

### Bug Reports
- Use the [Issues](../../issues) page to report bugs
- Include system information and steps to reproduce
- Attach screenshots if relevant

### Feature Requests
- Suggest new features via [Issues](../../issues)
- Describe the use case and expected behavior
- Check existing requests to avoid duplicates

### Code Contributions
- Fork the repository and make your changes
- Submit a Pull Request with your improvements
- **Note**: All releases are built and distributed exclusively by the project maintainer
- Contributors will be credited in release notes and acknowledgments

---

## 🙏 Acknowledgments

- **Valve Corporation** for the Steam API
- **Faceit** for providing competitive match data
- **Leetify** for advanced player analytics
- **Crow Framework** for the lightweight C++ web server
- **Electron** for cross-platform desktop application framework

---

## 📞 Support

- **Issues**: [GitHub Issues](../../issues)
- **Discussions**: [GitHub Discussions](../../discussions)
- **Steam**: [Steam Profile](https://steamcommunity.com/profiles/76561197963549247)

---

## 🔄 Changelog

### Version 1.0.0 (Latest)
- ✨ Initial release
- 🎯 Automatic recent players detection
- 📊 Faceit and Leetify integration
- 🖥️ Modern Electron-based UI
- ⚡ High-performance C++ backend
- 🛡️ Comprehensive error handling

---

**Made with ❤️ for the CS2 community**

![CS2](https://img.shields.io/badge/Game-Counter--Strike%202-blue?style=flat-square&logo=steam)
![C++](https://img.shields.io/badge/Backend-C++-blue?style=flat-square&logo=cplusplus)
![Electron](https://img.shields.io/badge/Frontend-Electron-teal?style=flat-square&logo=electron)
![Steam](https://img.shields.io/badge/API-Steam-black?style=flat-square&logo=steam)
