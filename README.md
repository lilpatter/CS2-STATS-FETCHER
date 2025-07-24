# CS2 Stats Fetcher

![CS2 Stats Fetcher](https://img.shields.io/badge/CS2-Stats%20Fetcher-orange?style=for-the-badge&logo=steam)
![Version](https://img.shields.io/badge/version-1.0.0-green?style=for-the-badge)
![Platform](https://img.shields.io/badge/platform-Windows-blue?style=for-the-badge&logo=windows)

**A powerful desktop application for fetching and displaying comprehensive Counter-Strike 2 player statistics from Faceit and Leetify.**

---

## 🚀 Features

### 🎯 **Real-time Player Analysis**
- **Automatic Recent Players Detection**: Instantly fetches stats for players from your recent CS2 matches
- **Manual Player Lookup**: Search any player by Steam ID or profile URL
- **Comprehensive Data Sources**: Integrates with both Faceit and Leetify APIs for complete player profiles

### 📊 **Detailed Statistics**
- **Faceit Integration**: Skill level, ELO rating, country, match history
- **Leetify Analytics**: Advanced rating breakdowns (Aim, Positioning, Utility, Clutch, Opening)
- **Overall Performance**: K/D ratio, ADR, headshot percentage, win rate, MVP count
- **Match History**: Recent game performance and trends

### 🖥️ **Modern Interface**
- **Sleek Dark Theme**: Professional CS2-inspired UI design
- **Real-time Updates**: Live progress tracking during data fetching
- **Responsive Layout**: Optimized for various screen sizes
- **Interactive Scoreboard**: Hover effects and detailed player cards

### ⚡ **Performance & Reliability**
- **Hybrid Architecture**: C++ backend for speed + Electron frontend for UI
- **Multi-threaded Processing**: Concurrent API requests for faster results
- **Error Handling**: Robust fallback mechanisms and user feedback
- **Portable Executable**: Single .exe file - no installation required

---

## 📥 Download & Installation

### Quick Start
1. **Download** the latest release: [`CS2-Stats-Fetcher-Portable.exe`](../../releases/latest)
2. **Run** the executable - no installation needed!
3. **Launch CS2** and play some matches
4. **Click "Fetch Recent Players"** to see stats for your recent teammates/opponents

> **System Requirements**: Windows 10/11 (64-bit), Steam installed and logged in

---

## 🎮 How to Use

### Automatic Mode (Recommended)
1. **Play CS2 matches** as usual
2. **Open CS2 Stats Fetcher**
3. **Click "Fetch Recent Players"**
4. View comprehensive stats for all recent players automatically

### Manual Mode
1. **Click "Toggle Manual Mode"**
2. **Enter Steam ID or Profile URL** in the input field
3. **Click "Fetch Player Stats"**
4. View detailed statistics for the specific player

### Features Overview
- **Progress Tracking**: Real-time updates show fetch progress
- **Data Sources**: Automatically queries Faceit and Leetify
- **Player Identification**: Shows your current Steam profile highlighted in green
- **Export Options**: Results can be copied or saved for later analysis

---

## 🛠️ Technical Details

### Architecture
- **Backend**: C++ with Crow web framework for high-performance API handling
- **Frontend**: Electron-based desktop application with modern HTML5/CSS3/JavaScript
- **APIs**: Integrates with Steam, Faceit, and Leetify public APIs
- **Dependencies**: libcurl for HTTP requests, Steam API for user authentication

### Data Sources
- **Steam API**: Player names, profile information, recent game data
- **Faceit API**: Competitive rankings, ELO, match history, regional data
- **Leetify API**: Advanced analytics, detailed performance metrics, AI-driven insights

### Privacy & Security
- **Local Processing**: All data processing happens on your local machine
- **No Data Storage**: No personal information is stored or transmitted to external servers
- **Steam Integration**: Uses official Steam API with read-only access
- **Secure**: Thoroughly tested and scanned for malware before release

---

## 💾 Software Distribution

### Release-Only Distribution
This application is distributed exclusively through **GitHub Releases** as a pre-built, portable executable. 

- ✅ **Ready to Use**: No compilation or setup required
- ✅ **Portable**: Single executable file with all dependencies included
- ✅ **Tested**: Each release is thoroughly tested before distribution
- ✅ **Secure**: Official builds from verified source

---

## 📋 System Requirements

### Minimum Requirements
- **OS**: Windows 10 (64-bit)
- **RAM**: 4 GB
- **Storage**: 50 MB available space
- **Network**: Internet connection required
- **Steam**: Steam client installed and logged in

### Recommended
- **OS**: Windows 11 (64-bit)
- **RAM**: 8 GB or more
- **Storage**: 100 MB available space (for faster loading)
- **Network**: Stable broadband connection

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
