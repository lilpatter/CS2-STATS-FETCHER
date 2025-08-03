# CS2 Stats Fetcher

![CS2 Stats Fetcher](https://img.shields.io/badge/CS2-Stats%20Fetcher-orange?style=for-the-badge&logo=steam)
![Version](https://img.shields.io/badge/version-1.0.0-green?style=for-the-badge)
![Platform](https://img.shields.io/badge/platform-Windows-blue?style=for-the-badge&logo=windows)
![License](https://img.shields.io/badge/license-MIT-blue?style=for-the-badge)

**A robust desktop application for retrieving comprehensive Counter-Strike 2 player statistics from Faceit and Leetify APIs, designed for competitive gamers.**

<div style="width: 200px;">
  <img src="https://github.com/user-attachments/assets/be8d60b3-b98e-4f32-b0c8-f854c906e4f3" alt="Main Interface" />
</div>
*CS2 Stats Fetcher upon launch, displaying the main interface.*

<div style="width: 600px;">
  <img src="https://github.com/user-attachments/assets/70ca1fab-3f68-4fe5-9050-40b11ae87914" alt="Fetching Players" />
</div>
*Fetching recent players after clicking "Fetch Recent Players".*

<div style="width: 600px;">
  <img src="https://github.com/user-attachments/assets/c81c0c09-ba61-4891-a4d7-9495291a58da" alt="Results Display" />
</div>
*Comprehensive player statistics displayed after fetching completes.*

## 📥 **Download**
**[⬇️ Download Latest Release](../../releases/latest)**  
**Requirements:** Windows 10/11 (64-bit), Steam client running and logged in.

## 🌟 **Key Features**
- 🎯 **Automatic Player Detection**: Instantly identifies and fetches stats for recent CS2 match players.
- 📊 **Faceit & Leetify Integration**: Retrieves ELO, skill levels, K/D ratios, and detailed match analytics.
- 🖥️ **Sleek Dark UI**: Modern Electron-based interface with real-time progress indicators.
- ⚡ **Portable Application**: No installation required; runs directly from the executable.
- 🔒 **Privacy-Focused**: All data processing is local, with no external storage or telemetry.

## 🎮 **Usage Instructions**
1. **Download** the latest release and run the executable.
2. **Play CS2 Matches**: Ensure you’ve played at least one match for player detection.
3. **Fetch Stats**: Click **"Fetch Recent Players"** to retrieve stats automatically.
4. **Manual Search**: Use **Manual Mode** to query specific players via Steam ID.
5. **View Results**: Explore detailed stats in the intuitive interface.

## 🔧 **Technical Details**
- **Architecture**: High-performance C++ backend with Crow framework; Electron-based frontend for cross-platform compatibility.
- **APIs**: Steam Web API, Faceit API, Leetify API for comprehensive data.
- **Security**: Local processing ensures no sensitive data leaves your device.
- **Distribution**: Official releases are cryptographically signed and distributed solely via GitHub.

## 🛠️ **Troubleshooting**

### Common Issues & Solutions
- **"No recent players found"**  
  - Verify Steam is running and online.
  - Play a CS2 match to populate recent player data.
  - Ensure Steam’s privacy settings allow match history access.

- **"API rate limit exceeded"**  
  - Wait 5–10 minutes before retrying.
  - Reduce the number of players fetched in one go.
  - Check Faceit/Leetify API status for outages.

- **"Backend server not responding"**  
  - Restart the application.
  - Allow port 18080 through Windows Firewall.
  - Disable conflicting VPN or network software.

- **"Application fails to start"**  
  - Install [Microsoft Visual C++ Redistributable (x64)](https://aka.ms/vs/17/release/vc_redist.x64.exe).
  - Run the application as Administrator.
  - Add the executable to your antivirus whitelist.

For additional help, visit the [Issues](../../issues) page or join our [Discussions](../../discussions).

## 🤝 **Contributing**
We value community contributions to make CS2 Stats Fetcher even better!

### Reporting Bugs
- Submit issues via the [Issues](../../issues) page.
- Provide detailed steps to reproduce, system specs, and screenshots.
- Check for existing reports to avoid duplicates.

### Requesting Features
- Share ideas on the [Issues](../../issues) page.
- Clearly explain the feature’s purpose and potential benefits.
- Review existing feature requests before submitting.

### Code Contributions
- Submit a Pull Request with clear commit messages and documentation.
- **Note**: All official releases are built and signed by the project maintainer.
- Contributors are credited in release notes and the [Acknowledgments](#-acknowledgments) section.




