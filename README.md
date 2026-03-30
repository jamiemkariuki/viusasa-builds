# Viusasa Desktop App - Builds

[![Build Status](https://github.com/jamiemkariuki/viusasa-builds/actions/workflows/build-mirror.yml/badge.svg)](https://github.com/jamiemkariuki/viusasa-builds/actions)

Official build releases for the Viusasa Desktop Application.

## 📥 Downloads

Download the latest version from the **[Releases](https://github.com/jamiemkariuki/viusasa-builds/releases)** page.

### Available Platforms

| Platform | File | Architecture |
|----------|------|--------------|
| **Windows** | `Viusasa-*.msi` | x64 |
| **Windows (Portable)** | `Viusasa-*.zip` | x64 |
| **macOS** | `Viusasa-*.dmg` | Universal (Intel + Apple Silicon) |
| **macOS (Portable)** | `Viusasa-*.zip` | Universal |
| **Linux** | `Viusasa-*.AppImage` | x64 |

## 🚀 Installation

### Windows

**Using MSI Installer (Recommended):**
1. Download `Viusasa-*.msi`
2. Run the installer
3. Launch Viusasa from Start Menu

**Using Portable ZIP:**
1. Download `Viusasa-*.zip`
2. Extract to a folder
3. Run `Viusasa.exe`

### macOS

⚠️ **First Time Opening:** macOS may show a warning because the app is not signed with an Apple Developer certificate.

**Option 1 - System Preferences:**
1. Go to **System Preferences** → **Privacy & Security**
2. Click **"Open Anyway"**

**Option 2 - Terminal:**
```bash
# Remove quarantine attribute
xattr -cr /Applications/Viusasa.app

# Then open
open /Applications/Viusasa.app
```

**Option 3 - Right-click:**
1. Right-click (or Control-click) on `Viusasa.app`
2. Select **Open**
3. Click **Open** in the dialog

### Linux

```bash
# Make executable
chmod +x Viusasa-*.AppImage

# Run
./Viusasa-*.AppImage
```

## ✨ Features

- 🌐 Browse [viusasa.com](https://viusasa.com/) in a dedicated desktop window
- 🎨 Custom red & black themed scrollbars
- 🧭 Built-in navigation (Back, Forward, Home)
- 🖥️ Frameless window with custom title bar
- 🔲 Window controls (Minimize, Maximize, Close)

## 🎮 Usage

### Navigation Bar
- **← Back**: Go to previous page
- **→ Forward**: Go to next page
- **🏠 Home**: Return to viusasa.com

### Window Controls
- **➖ Minimize**: Minimize window
- **⬜ Maximize**: Maximize/Restore window
- **❌ Close**: Close the app

## 🔧 Automated Builds

Builds are automated via GitHub Actions. Every push to the main branch of the source repo triggers builds for all platforms.

### Build Status

[![Build Desktop Apps](https://github.com/jamiemkariuki/viusasa-builds/actions/workflows/build-mirror.yml/badge.svg)](https://github.com/jamiemkariuki/viusasa-builds/actions/workflows/build-mirror.yml)

### Manual Build Trigger

1. Go to [Actions](https://github.com/jamiemkariuki/viusasa-builds/actions)
2. Select **Build Desktop Apps**
3. Click **Run workflow**
4. Enter version tag (e.g., `v1.0.2`) or leave as `main`
5. Click **Run workflow**

## 📝 License

ISC

## 🔗 Links

- **Source Code**: [viusasa-desktop-app](https://github.com/jamiemkariuki/viusasa-desktop-app)
- **Website**: [viusasa.com](https://viusasa.com/)
- **Issues**: [Report a Bug](https://github.com/jamiemkariuki/viusasa-builds/issues)
