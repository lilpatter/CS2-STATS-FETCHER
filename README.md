# CS2 Stats Fetcher

![CS2 Stats Fetcher](https://img.shields.io/badge/CS2-Stats%20Fetcher-orange?style=for-the-badge&logo=steam)
![Version](https://img.shields.io/badge/version-1.1.5-green?style=for-the-badge)
![Platform](https://img.shields.io/badge/platform-Windows-blue?style=for-the-badge&logo=windows)
![License](https://img.shields.io/badge/license-MIT-blue?style=for-the-badge)

*Overhauling the UI!*
*At the momement the UI is getting a overhaul.
*I have attached a screenshot so you can take a look at the progress.*

*Updated UI!!*
*Fixed: Padding, image errors*
*Added new icons, more stylized UI*

<img width="1898" height="909" alt="{52FC453C-E161-4ECE-8E37-D43825D09546}" src="https://github.com/user-attachments/assets/58670b8b-ed62-4d9d-857c-addc8053bcfc" />

*Displaying the CS2 Stats Fetcher main interface upon launch.*

<img src="https://github.com/user-attachments/assets/be8d60b3-b98e-4f32-b0c8-f854c906e4f3" alt="Main Interface" width="300" />

*Fetching recent players after clicking "Fetch Recent Players".*

<img src="https://github.com/user-attachments/assets/70ca1fab-3f68-4fe5-9050-40b11ae87914" alt="Fetching Players" width="300" />

*Showing comprehensive player statistics after fetching completes.*

<img src="https://github.com/user-attachments/assets/c81c0c09-ba61-4891-a4d7-9495291a58da" alt="Results Display" width="300" />

## Usage Instructions
1. **Download** the latest release and run the executable.
2. **Play CS2 Matches**: Ensure you’ve played at least one match for player detection.
3. **Fetch Stats**: Click **"Fetch Recent Players"** to retrieve stats automatically.
4. **Manual Search**: Use **Manual Mode** to query specific players via Steam ID.
5. **View Results**: Explore detailed stats in the intuitive interface.

## Technical Details
- **Architecture**: High-performance C++ backend with Crow framework; Electron-based frontend for cross-platform compatibility.
- **APIs**: Steam Web API, Faceit API, Leetify API for comprehensive data.
- **Security**: Local processing ensures no sensitive data leaves your device.
- **Distribution**: Official releases are cryptographically signed and distributed solely via GitHub.
- **Availability**: No source code is currently available. The backend executable file is planned for release in the near future, pending further cleanup and adjustments to ensure quality and performance.

## System Requirements
- **Minimum**: Windows 10 (64-bit), 4GB RAM, Steam client logged in.
- **Recommended**: Windows 11, 8GB+ RAM, stable internet connection for API calls.

## Troubleshooting

### Common Issues & Solutions
- **"No recent players found"**  
  - Verify Steam is running and online.
  - Play a CS2 match to populate recent player data.
  - Ensure Steam’s privacy settings allow match history access.

- **"Application fails to start"**  
  - Install [Microsoft Visual C++ Redistributable (x64)](https://aka.ms/vs/17/release/vc_redist.x64.exe).
  - Run the application as Administrator.
  - Add the executable to your antivirus whitelist.

For additional help, visit the [Issues](../../issues) page or join our [Discussions](../../discussions).

### Reporting Bugs
- Submit issues via the [Issues](../../issues) page.
- Provide detailed steps to reproduce, system specs, and screenshots.
- Check for existing reports to avoid duplicates.

### Requesting Features
- Share ideas on the [Issues](../../issues) page.
- Clearly explain the feature’s purpose and potential benefits.
- Review existing feature requests before submitting.

### Code Contributions
- **Note**: No source code is currently available for contribution. The backend executable file is planned for release in the near future after further cleanup and adjustments. Once released, contributions may be considered for future updates.
- Contributors will be credited in release notes and the [Acknowledgments](#acknowledgments) section.

## Acknowledgments
- **Valve Corporation**: For providing the Steam Web API.
- **Faceit**: For competitive match data and ELO metrics.
- **Leetify**: For in-depth player performance analytics.
- **Crow Framework**: Lightweight and efficient C++ web server.
- **Electron**: Enabling a modern, cross-platform desktop UI.
- **Open-Source Community**: For tools and libraries that power this project.

---

![CS2](https://img.shields.io/badge/Game-Counter--Strike%202-blue?style=flat-square&logo=steam)
![C++](https://img.shields.io/badge/Backend-C++-blue?style=flat-square&logo=cplusplus)
![Electron](https://img.shields.io/badge/Frontend-Electron-teal?style=flat-square&logo=electron)
![Steam](https://img.shields.io/badge/API-Steam-black?style=flat-square&logo=steam)
![Faceit](https://img.shields.io/badge/API-Faceit-orange?style=flat-square)
![Leetify](https://img.shields.io/badge/API-Leetify-green?style=flat-square)







