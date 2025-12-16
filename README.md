# Rapidapter - the rapid adapter adapter.  

![Screenshot of Rapidapter](./screencap.png)

Rapidapter is a lightweight PowerShell-based Windows utility for rapidly switching IPv4 network adapter configurations via a clean GUI. 

I made this utility because I often needed to manually change my ethernet adapter settings for various admin tasks, and was frustrated at how many clicks, scrolls, and characters I needed to enter to get to that adapter page. 

I'm providing it here on GitHub for any interested user -- My version is built with all the quick settings I need out of the box (DHCP, Persistent Systems, Silvus, LEMR, and manual profiles).

In potential future iterations I may provide a templating tool to build custom Rapidapter loadouts. 

## Features
- One-click IPv4 profile switching
- Self-elevating (admin-safe)
- Dark-mode UI
- Hotkey-friendly
- Installer script for Start Menu/Desktop shortcuts

## Installation
Run the installer script from Powershell as an admin:

```powershell
.\Install-Rapidapter.ps1
```

Alternatively, if you want a desktop shortcut created as well, run the installation script with the `-DesktopShortcut` flag enabled. 

```powershell
.\Install-Rapidapter.ps1 -DesktopShortcut
```