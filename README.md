# Auto Mod Menu Update Tool
A powerful automation tool for modding Android game APKs and XAPKs. This tool drastically reduces the time required for modders and developers to update mod menus—from nearly an hour manually to under a minute automatically.

# Overview
The Auto Mod Menu Update Tool streamlines the process of modding Android games. It performs the following tasks automatically:
- Retrieves the APK and extracts critical information such as the package name and main launchable activity.
- Determines and applies method and function changes based on a pre-defined database.
- Merges XAPK to APK.
- Decompiles the APK, applies modifications (including updating offsets, editing the AndroidManifest.xml, and managing library files across architectures like ARM64 and armeabi-v7).
- Builds and injects the mod menu template into the game.
- Recompiles and signs the APK.
  
Future updates will include an auto-update feature that detects new game versions, downloads the updated APK, and applies mod updates automatically. Initially, it supports the LGL Team Template version 3.2, with plans to support custom templates in upcoming releases.

# Features
- Automated APK Processing:
  
  Retrieves package information, decompiles, and modifies the APK with minimal manual intervention.

- Mod Menu Injection:
  
  Automatically builds and injects a mod menu template into the game, ensuring rapid updates.

- Comprehensive Compatibility:
  
   Supports multiple architectures (ARM64, armeabi-v7) and works on any PC—with future support planned for macOS, Linux, and Android devices.

- Tool Integration:
  
    Utilizes New versions of apktool GUI and IL2CPP Dumper GUI (both created by andnixsh) to ensure compatibility with the latest versions.

- Extensible & Secure:
  
   Designed for developers, modders, and software engineers who work with Android game modifications. The code is protected via server-side licensing, ensuring that end users cannot view the source unless explicitly permitted.

# Installation & Setup
- Python: The primary language for the tool.
- Additional Languages/Tools:
  
Some components are built with C#, C++, and Java. Please ensure the respective runtime environments or compilers are installed.

# Installation Steps & Usage
- contact me [Amped Gems] on:
-  discord : https://discord.gg/mMA8UKnUNV
-  platinmods : https://platinmods.com/forums/android-mods-by-approved-modders.115/?starter_id=5086032&order=post_date&direction=desc

# old Video Demonstration
https://www.youtube.com/watch?v=PNlcqo_7SZI


# Contributing
- Contributions are welcome! If you’d like to help improve the tool:
 contact me first though 

# Licensing & Code Protection
 The tool uses server-side licensing to protect the source code:
- Free Version vs. Paid Version:

A free version is available alongside a premium version offering additional features.

- Code Protection:

Users of the tool will not have access to view the underlying source code unless specifically purchased by the developer.

# Roadmap

Auto-Update Feature:

- Automatically download and update the game APK when new updates are available.

Template Support Expansion:

- Support additional mod menu templates, including fully custom ones.
Cross-Platform Support:

- Extend compatibility to macOS, Linux, and Android devices.

