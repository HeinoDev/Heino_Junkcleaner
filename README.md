# Heino Cleaner

A Windows system cleaner tool with a clean, modern GUI. Safely removes temporary files, cache, and other unnecessary data to free up disk space.

## Features

- 🧹 Clean temporary files, Windows Temp, DirectX cache, FiveM cache, and Discord cache
- 🎨 Modern dark/light theme support (automatically detects Windows theme)
- 👤 Non-admin mode supported (some features require admin)
- 📊 Real-time scan and cleaning progress
- 📝 Detailed logging of all operations
- 🔒 Safe deletion - only scans designated safe directories

## Installation

### PowerShell (Recommended)

```powershell
python heino_cleaner.py --install
```

### Command Prompt (CMD)

```cmd
python heino_cleaner.py --install
```

## After Installation

Once installed, you can run Heino Cleaner from any terminal:

```powershell
heino-cleaner
```

Or:

```cmd
heino-cleaner
```

You can also find "Heino Cleaner" in your Start Menu.

## Usage

1. **Run the application** - Launch Heino Cleaner from your terminal or Start Menu
2. **Click "Scan"** - Scan your system to see what can be cleaned
3. **Select items** - Check the boxes for the items you want to clean
4. **Click "Ryd valgte" (Clean selected)** - Confirm and clean
5. **View results** - Check the log for details

## System Requirements

- Windows 10 or later
- Python 3.6+
- For full functionality, run as Administrator (optional)

## Uninstallation

### PowerShell

```powershell
python heino_cleaner.py --uninstall
```

### Command Prompt (CMD)

```cmd
python heino_cleaner.py --uninstall
```

## What Gets Cleaned

- **Temporary User Files** - %TEMP% directory
- **Windows Temporary Files** - Windows\Temp (requires admin)
- **DirectX Shader Cache** - D3D cache files
- **FiveM Cache** - Game cache (safe, rebuilds automatically)
- **Discord Cache** - Chat and media cache (optional)

## Notes

- Files in use are automatically skipped during cleaning
- Most caches rebuild automatically when needed
- Close Discord before cleaning its cache for best results
- The tool is safe and only touches designated system directories
- Always check the log before confirming deletion
