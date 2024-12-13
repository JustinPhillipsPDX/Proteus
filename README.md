# Proteus 🐍

Proteus is a dynamic, cross-platform window and tiling manager designed to serve as the interactive layer for [Hermes 🦀](https://github.com/JustinPhillipsPDX/Hermes). With its adaptable design, Proteus empowers users to manage windows and workflows efficiently, integrating seamlessly with intelligent task and file management systems. Proteus is part of an ecosystem of tools that includes [SeaShell 🐚](https://github.com/JustinPhillipsPDX/SeaShell), which acts as the installation and build mechanism for the project.

In addition to its core functionality, Proteus has the potential to replace system components like the taskbar and Explorer on Windows, providing a streamlined, privacy-first interface for managing tasks, files, and windows while minimizing unnecessary system tracking.

## Features (Planned)
- **Dynamic Window Management**: Customizable tiling and stacking layouts.
- **Cross-Platform Compatibility**: Runs on Linux, macOS, and Windows.
- **Integration with Hermes**: Enhanced file and task management capabilities.
- **User-Friendly Interface**: Keyboard-driven workflows with optional mouse support.
- **Theming and Customization**: Support for personalized layouts and styles.
- **Seamless Installation**: Uses [SeaShell 🐚](https://github.com/JustinPhillipsPDX/SeaShell) for cross-platform setup and build automation.
- **Explorer Replacement (Planned)**: Serve as an alternative to the Windows Explorer and taskbar while maintaining system wallpaper.

## Getting Started

### Requirements
- **C++17 or later**
- A C++ compiler (GCC, Clang, or MSVC)
- CMake (3.10 or higher)
- Git for version control
- [SeaShell 🐚](https://github.com/JustinPhillipsPDX/SeaShell): For installation and build automation.

### Build Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/JustinPhillipsPDX/Proteus.git
   cd Proteus
   ```

2. Use [SeaShell 🐚](https://github.com/JustinPhillipsPDX/SeaShell) for installation and compilation:
   - **Linux/macOS**:
     ```bash
     ./install.sh
     ```
   - **Windows** (run in PowerShell):
     ```powershell
     ./install.ps1
     ```

3. Follow the prompts to complete the setup.

## Roadmap
- [x] Repository setup
- [ ] Core window management functionality
- [ ] Platform-specific modules
- [ ] Theming and customization framework
- [ ] Integration with Hermes 🦀 for intelligent workflows
- [ ] Full support for installation via SeaShell 🐚
- [ ] Explorer replacement functionality for Windows, including system wallpaper support.

## License
This project is licensed under the [MIT License](LICENSE).
