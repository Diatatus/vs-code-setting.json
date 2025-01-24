VS Code Settings

This repository contains a custom settings.json configuration file for Visual Studio Code.
By using these settings, you can quickly align your development environment with a pre-configured setup.

Table of Contents
. Prerequisites
. Installation
. Usage
. Troubleshooting
. License

Prerequisites

. Visual Studio Code installed on your machine
. Download: https://code.visualstudio.com/Download

Installation

1. Clone or download this repository to your local machine.
2. Locate the settings.json file within the repository.

Usage

You have two primary ways to apply these custom settings:

1. Direct Copy-Paste Into User Settings

1. Open Visual Studio Code.
1. Open the Command Palette:
   . Windows/Linux: <kbd>Ctrl + Shift + P</kbd>
   . macOS: <kbd>Command + Shift + P</kbd>
1. Type Preferences: Open Settings (JSON) and press <kbd>Enter</kbd>.
1. This will open your personal settings.json file.
1. Copy the content of this repository’s settings.json.
1. Paste it into your personal settings.json.
1. Save the file and relaunch VS Code if necessary.

1. Replace the Existing User Settings File
   Warning: This will overwrite any existing VS Code user settings you have.
   Make sure to back up your current settings.json beforehand if you want to keep those.

1. Find your local VS Code user settings folder:
   . Windows: C:\Users\<YourUserName>\AppData\Roaming\Code\User\
   . Linux: /home/<YourUserName>/.config/Code/User/
   . macOS: /Users/<YourUserName>/Library/Application Support/Code/User/

1. Copy this repository’s settings.json directly into that folder.
1. Restart Visual Studio Code.

Troubleshooting

. If you encounter issues with extensions after applying the settings, verify that you have the recommended extensions installed or adjust the settings accordingly.
. For OS-specific settings (like file paths), make sure to update them to match your operating system.
. If you want project-specific settings rather than user-wide settings, consider placing the settings.json file in a .vscode folder inside your project. VS Code will then apply these settings only to that project.

License

This project is licensed under the MIT License. Feel free to use, modify, and distribute it as you see fit.
