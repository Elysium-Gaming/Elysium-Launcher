Elysium Launcher
A lightweight, portable World of Warcraft launcher for ElysiumCore, TrinityCore, and compatible private servers.

Elysium Launcher is a single-file Windows executable designed to launch World of Warcraft using your own private server configuration.

Simply place the launcher beside Wow.exe, configure your server connection, and launch the game.

Microsoft .NET 9 Desktop Runtime (Windows x64) is required.

Client Compatibility
Elysium Launcher supports World of Warcraft Retail build 68974 and newer.

Client	Status
WoW Retail — Build 68974	Supported
WoW Retail — Build 69933	Supported
WoW Retail 12.1.5 — Build 70783	Tested and working
Newer Retail builds (above 70783)	Supported range; individual builds not necessarily tested
WoW Classic	Not tested
WoW Classic Era / Forever	Not tested
Older Retail builds (below 68974)	Not tested
Supported build range: 68974 and above.

Individual build compatibility may vary. Not every Retail build has been independently tested.

Compatibility with Classic, Classic Era, Classic Forever, and other WoW client variants is not guaranteed.

Server Compatibility
Elysium Launcher is designed for use with:

ElysiumCore — Custom World of Warcraft server
TrinityCore — World of Warcraft server emulator
Other compatible private servers — Compatibility may vary
Important: Your server must support the client build you are launching.

Elysium Launcher does not automatically make incompatible World of Warcraft clients and private servers compatible.

System Requirements
Windows 64-bit
Microsoft .NET 9 Desktop Runtime (x64)
World of Warcraft Retail build 68974 or newer
Access to your own compatible private server
Your server's IP address or hostname
Download Microsoft .NET 9
Install the Windows x64 version of Microsoft .NET 9 Desktop Runtime before launching the application.

Official download:

https://dotnet.microsoft.com/en-us/download/dotnet/9.0

Select .NET Desktop Runtime 9.0 — Windows x64.

Download
Download the latest ElysiumLauncher.exe from the repository's Releases section.

No installer is required for Elysium Launcher itself.

Installation
Install Microsoft .NET 9 Desktop Runtime (Windows x64).
Locate your World of Warcraft installation directory.
Open the folder containing Wow.exe. For Retail, this is normally _retail_.
Place ElysiumLauncher.exe directly beside Wow.exe.
Update your World of Warcraft configuration with your own private server IP address or hostname.
Save your configuration changes.
Double-click ElysiumLauncher.exe to launch the game.
Example Folder Structure
World of Warcraft/
└── _retail_/
    ├── Wow.exe
    ├── ElysiumLauncher.exe
    ├── Data/
    ├── WTF/
    └── Interface/
Important: The launcher must be located in the same directory as Wow.exe.

Server Configuration — Required
You must configure your own World of Warcraft client to connect to your private server.

Elysium Launcher does not automatically:

Configure your server IP address or hostname
Provide private server connection details
Host a World of Warcraft server
Update your game client
Convert incompatible client builds into supported server versions
Make sure your server is online, accessible, and compatible with your WoW client build.

Features
Single portable Windows executable
No launcher installation required
Supports Retail clients starting at build 68974
Designed for ElysiumCore and TrinityCore servers
Uses your existing private server configuration
Simple copy, configure, and launch setup
No separate launcher folder required
Troubleshooting
Launcher does not start
Verify that Microsoft .NET 9 Desktop Runtime (Windows x64) is installed.

Download: https://dotnet.microsoft.com/en-us/download/dotnet/9.0

Launcher cannot find Wow.exe
Make sure ElysiumLauncher.exe is in the same folder as Wow.exe.

Game does not launch
Verify that your game installation is complete and that your client build is compatible with the launcher.

Cannot connect to your server
Check your server IP address or hostname, configuration settings, network connectivity, and client/server build compatibility.

Unsupported or untested client
Support for Classic, Classic Era, Classic Forever, and other client variants has not been verified.

Community & Support
Join the official ElysiumCore Discord community for announcements, discussions, feedback, and support.

Discord: https://discord.gg/nn4yZD8un

License
Copyright © 2026 Elysium Launcher. All rights reserved.

Elysium Launcher is proprietary software distributed as a compiled executable. Source code is not publicly available.

World of Warcraft and related trademarks belong to Blizzard Entertainment.

Elysium Launcher is an independent, unofficial project and is not affiliated with or endorsed by Blizzard Entertainment.
