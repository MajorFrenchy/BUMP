# BUMP - Backup Utility for My Pinball

![Version](https://img.shields.io/badge/version-1.0-blue.svg)
![Platform](https://img.shields.io/badge/platform-Windows-lightgrey.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

**BUMP** (Backup Utility for My Pinball) is a user-friendly Windows application designed to help virtual pinball enthusiasts safely backup their pinball machine configurations, tables, and media files.

## 📋 Table of Contents

- [Features](#features)
- [Supported Components](#supported-components)
- [Installation](#installation)
- [Usage](#usage)
- [Backup Modes](#backup-modes)
- [System Requirements](#system-requirements)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [Support](#support)
- [Author](#author)

## ✨ Features

- **Automatic Backup Mode** - Pre-configured backup paths for common pinball components
- **Manual Backup Mode** - Flexible selection of custom files and folders
- **Real-time Progress Tracking** - Visual progress bar with percentage completion
- **Cancellable Operations** - Stop backup process at any time
- **Timestamped Backups** - Automatic backup folder naming with date/time stamps
- **Comprehensive Logging** - Detailed backup log for every operation
- **Modern GUI** - Clean, intuitive interface with modern design
- **Backup Reminders** - Helpful reminder to keep backups off-site

## 🎮 Supported Components

BUMP provides automatic backup support for the following virtual pinball components:

| Component | Default Path |
|-----------|-------------|
| **Visual Pinball** | `C:\vPinball\VisualPinball` |
| **Future Pinball** | `C:\vPinball\FuturePinball` |
| **PinUP System** (Front End) | `C:\vpinball\PinUPSystem` |
| **DOF** (DirectOutput Framework) | `C:\DirectOutput` |
| **Pinball FX** | `C:\Program Files (x86)\Steam\steamapps\common\Pinball FX\PinballFX` |

### Additional Items to Consider Backing Up

- VPX tables
- Music files
- VPinMAME files
- ROM files
- Table aliases
- Front end databases
- Media folders (backglasses, wheel images, videos)
- Zen FX tables

## 💾 Installation

1. Download the latest release of `BUMP V1.0.exe`
2. Place the executable in a convenient location
3. Run the application (no installation required)

**Note:** This is a portable application - no installation needed!

## 🚀 Usage

### Quick Start

1. Launch `BUMP V1.0.exe`
2. Choose your backup mode:
   - **Automatic Backup** - For standard pinball installations
   - **Manual Backup** - For custom configurations
3. Select components to backup
4. Choose your backup destination
5. Click "Start Backup" and monitor progress
6. Find your backup in the timestamped folder

### Best Practices

- ✅ Backup regularly (weekly or after significant changes)
- ✅ Keep at least one backup copy off-site
- ✅ Verify backup contents periodically
- ✅ Keep multiple backup versions
- ✅ Review the backup log for any issues

## 🎯 Backup Modes

### Automatic Backup Mode

Perfect for standard virtual pinball setups. Features:
- Pre-configured paths for common components
- Checkbox selection for each component
- Path customization with browse functionality
- One-click backup of selected components

### Manual Backup Mode

For advanced users or custom setups:
- Select individual files or entire folders
- Mix and match any files/folders
- Flexible backup of non-standard locations
- Support for multiple custom paths

## 💻 System Requirements

- **Operating System:** Windows 7 or later
- **Framework:** .NET Framework 4.x or later
- **Disk Space:** Sufficient space for backup files (varies by selection)
- **Permissions:** Read access to source files, write access to backup destination

## 📸 Screenshots

<p align="center">
  <img src="https://github.com/MajorFrenchy/BUMP/raw/main/screenshots/screenshot01.jpg" width="50%" alt="VPXmerge Interface">
</p>
<br>
<p align="center">
  <img src="https://github.com/MajorFrenchy/BUMP/raw/main/screenshots/Screenshot%2002.jpg" width="50%" alt="VPXmerge Interface">
</p>
<br>
<p align="center">
  <img src="https://github.com/MajorFrenchy/BUMP/raw/main/screenshots/Screenshot%2003.jpg" width="50%" alt="VPXmerge Interface">
</p>

## 🤝 Contributing

Contributions are welcome! If you'd like to improve BUMP:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Ideas for Contributions

- Support for additional pinball platforms
- Scheduled/automated backups
- Cloud backup integration
- Compression options
- Incremental backup support
- Backup restoration wizard

##  Support me

If you find BUMP useful and would like to support its development: You can con tribute in 2 ways, Getting the VPC Chat Discord server a Boost :" https://discord.com/invite/virtual-pinball-chat-652274650524418078 

or by contributing to the VPC Chat Patreon: https://www.patreon.com/c/vpchat



## 👨‍💻 Author

**Major Frenchy**



## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## ⚠️ Disclaimer

Always verify your backups and test restoration procedures. The author is not responsible for data loss. This tool is provided "as is" without warranty of any kind.

## 🔄 Version History

### Version 1.0 (Current)
- Initial release
- Automatic and manual backup modes
- Progress tracking with cancel functionality
- Comprehensive backup logging
- Support for major virtual pinball components

---

**Remember:** Back up often and keep a copy off-site! 🎯

