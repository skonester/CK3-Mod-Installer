# CK3 Mod Installer

**CK3 Mod Installer** is a graphical tool to simplify the installation and management of Crusader Kings III mods. Built with Python and PySide6, it provides an intuitive drag-and-drop interface, log viewer, and mod fixing functionality.

## Features

- 📦 Install mods from `.zip` and `.7z` archives
- 📂 Drag & drop support
- 🛠 Auto-resolve broken `.mod` descriptor files
- 📋 Logs view with auto-refresh
- 🗑 Context menu for deleting mods or opening mod folders

> **Note:** Support for `.rar` archives is **planned** for future updates.

## Platform

- ✅ **Supported OS:** Windows 10/11 (64-bit)
- ❌ Linux/macOS not tested

## Installation

This software is distributed as a **standalone executable** (no Python installation required). Just download the latest release and run `CK3Installer.exe`.

## Development

If you want to build or run the source manually:

### Requirements

- Python 3.10+
- `pip install -r requirements.txt`

### Running the App

```bash
python main.py
```

## Roadmap

Planned features and improvements for future versions of **CK3 Mod Installer**:

- 🎨 **UI Redesign Using Qt (Open Source)**
  - Migration from the current layout to a redesigned interface using Qt (via PySide6) under the LGPL v3 open-source license.
  - Improved layout, accessibility, and visual clarity.

- 🖌️ **UI Styling Enhancements**
  - Consistent theme and styling across all interface elements.
  - Dark mode and better visual feedback during mod operations.

- 🧩 **CK3 Launcher Compatibility**
  - Integration with Crusader Kings III's official launcher functionality:
    - Toggle mod activation/deactivation.
    - View mod compatibility and metadata (e.g., supported version, tags).

- 📦 **.rar Archive Support**
  - Add support for extracting mods packaged in `.rar` format.

- 🖥️ **Cross-Platform Support**
  - Experimental support for **Linux** and **macOS** platforms, in addition to Windows.

- 🛡️ **False Positive Antivirus Detection Reduction**
  - Refactor build and packaging process to avoid triggering false AV flags.
  - Ensure smoother installation experience for end users.

## License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

### Qt Licensing Notice

This software uses **PySide6**, the official Python bindings for the Qt toolkit, which is licensed under the **GNU Lesser General Public License (LGPL) version 3**.

As required by the LGPL:

- Qt (via PySide6) is **dynamically linked**.
- No modifications have been made to the Qt source libraries.
- End users are granted the right to modify or replace the PySide6 libraries used by this software, as permitted by the LGPL.

For more information, refer to:
- [GNU LGPL v3 License](https://www.gnu.org/licenses/lgpl-3.0.html)
- [Qt Open Source Licensing](https://www.qt.io/licensing/open-source-lgpl-obligations)

