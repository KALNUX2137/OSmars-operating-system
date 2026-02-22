# OSmars-operating-system in python
🖥️ OSmars PC GUI System
Version: 1.0.0-beta
Status: ⚠️ Beta - Expect bugs and instability
License: MIT
📖 About
A fully functional desktop environment simulation built with Python and PySide6 (Qt for Python). This project replicates a modern operating system interface with window management, applications, and file system interaction.
This is an early beta release. The software is functional but may contain bugs, stability issues, or breaking changes in future updates. Use at your own discretion.
✨ Features
Window Manager - Custom window management with minimize, maximize, drag and drop, and taskbar integration
File Explorer - Full-featured explorer with navigation history, file operations (copy, move, delete), and tree view
Terminal - Integrated command-line interface with history, built-in commands (ls, cd, mkdir, python), and output capture
Web Browser - QtWebEngine-based browser with download support, fullscreen video, and navigation controls
Notepad - Text editor with file open/save, font customization, and status bar
Calculator - Modern calculator with basic arithmetic operations and theme support
Theming - Switch between Dark and Light modes. Supports custom wallpapers and icon positioning
Taskbar - Start menu, active window tracking, and real-time clock
🚀 Installation
Requirements:

    Python 3.8 or higher
    PySide6
    psutil

Install Dependencies:

1

📦 Usage

    Clone the repository
    Run the system by importing and calling launch_gui_system with your OS instance object

⚠️ Known Issues (Beta)
Since this is a Beta release, you may encounter:

    Occasional UI freezing during heavy file operations
    Minor styling inconsistencies in Light Mode
    WebEngine components may require additional system dependencies
    Settings may reset between sessions if not saved properly

Please report any bugs via the Issues tab to help improve stability.
📁 Project Structure
gui_system.py - Main GUI logic and components
system/ - System settings (JSON)
files/ - Virtual file system root

    Desktop/ - Desktop files
    Downloads/ - Downloaded files
    wallpapers/ - Custom wallpapers

osmars_gui.log - Application logs
🛠️ Technical Details
Framework: PySide6 (Qt for Python)
Logging: Built-in logging to osmars_gui.log
State Management: Settings saved in system/desktop_settings.json
Threading: File operations run on separate threads to prevent UI freezing
🤝 Contributing
Contributions are welcome! Since this is in Beta, please focus on:

    Bug fixes
    Stability improvements
    Performance optimization

Please feel free to submit a Pull Request.
📄 License
This project is open-source and available under the MIT License.
Status: ⚠️ Beta
Version: 1.0.0-beta
Author: KALNUX2137
