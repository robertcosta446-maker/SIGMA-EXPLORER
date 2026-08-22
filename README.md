# Sigma Explorer
![Roblox Explorer](https://img.shields.io/badge/Roblox-Explorer-purple)

**Sigma Explorer** is a customized Roblox instance explorer/debugger, based on DeX Explorer (Dex++).

## Features
- 🔍 **Explorer** - Browse the full Roblox instance hierarchy
- 📋 **Properties** - View and edit all instance properties and attributes
- 📝 **Script Viewer** - Decompile and view scripts with syntax highlighting
- 🖥️ **Console** - Interactive Lua console with output logging
- 💾 **Save Instance** - Save games/models to file
- 🎮 **3D Viewer** - Preview 3D models in a viewport
- 📱 **Mobile Support** - Full touch input support
- 🖱️ **Click to Select** - Click parts in-game to select them

## Usage

### Latest Version Script
```lua
loadstring(game:HttpGet("YOUR_RAW_URL_HERE/sigma_explorer.lua"))()
```

## Building from Source

### Requirements
- Python 3.x

### Build
```bash
python build.py
```
This will generate `sigma_explorer.lua` - a single file containing all modules.

## Project Structure
```
sigma-explorer/
├── header.lua          # Script header and polyfills
├── main.lua            # Core initialization and UI
├── build.py            # Build script (concatenates all files)
├── modules/
│   ├── Lib.lua         # UI framework and utilities
│   ├── Explorer.lua    # Instance tree explorer
│   ├── Properties.lua  # Property inspector
│   ├── Console.lua     # Developer console
│   ├── ScriptViewer.lua # Script decompiler/viewer
│   ├── SaveInstance.lua # Save instance to file
│   └── ModelViewer.lua # 3D model preview
└── sigma_explorer.lua  # Built output (generated)
```

## Credits
- Based on [DeX Explorer](https://github.com/FusionWTF/Dex-Explorer) by Chillz
- Original Dex by Moon

## License
MIT License
