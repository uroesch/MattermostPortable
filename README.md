[![Build](https://github.com/uroesch/MattermostPortable/workflows/build-package/badge.svg)](https://github.com/uroesch/MattermostPortable/actions?query=workflow%3Abuild-package)
[![GitHub release (latest by date including pre-releases)](https://img.shields.io/github/v/release/uroesch/MattermostPortable?include_prereleases)](https://github.com/uroesch/MattermostPortable/releases)
[![Runs on](https://img.shields.io/badge/runs%20on-Win64%20%26%20Win32-blue)](#runtime-dependencies)
![GitHub All Releases](https://img.shields.io/github/downloads/uroesch/MattermostPortable/total?style=flat)

# Mattermost Portable for PortableApps.com

<img src="App/AppInfo/appicon_128.png" align=left>

[Mattermost](https://mattermost.com/) is an open-source, self-hostable
online chat service with file sharing, search, and integrations. It is
designed as an internal chat for organisations and companies, and mostly
markets itself as an open-source alternative to Slack and Microsoft Teams.

Mattermost desktop applications are available for Windows, Mac and Linux 
operating systems.

## Runtime dependencies
* 32-bit or 64-bit version of Windows.


## Support matrix

| OS              | 32-bit             | 64-bit              | 
|-----------------|:------------------:|:-------------------:|
| Windows XP      | ![ns][ns]          | ![ns][ns]           | 
| Windows Vista   | ![ns][ns]          | ![ns][ns]           | 
| Windows 7       | ![ps][ps]          | ![ps][ps]           |  
| Windows 8       | ![ps][ps]          | ![ps][ps]           |  
| Windows 10      | ![fs][fs]          | ![fs][fs]           |

Legend: ![ns][ns] not supported;  ![nd][nd] no data; ![ps][ps] supported but not verified; ![fs][fs] verified;`

## Status 
This PortableApps project is in beta stage. 

## Todo
- [ ] Documentation
- [x] Add updater

## Build

### Prerequisites

* [PortableApps.com Launcher](https://portableapps.com/apps/development/portableapps.com_launcher)
* [PortableApps.com Installer](https://portableapps.com/apps/development/portableapps.com_installer)
* [Powershell](https://docs.microsoft.com/en-us/powershell/scripting/install/installing-powershell-core-on-linux?view=powershell-7)
* [Wine (Linux / MacOS only)](https://www.winehq.org/)

### Build

To build the installer run the following command in the root of the git repository.

```
powershell Other/Update/Update.ps1
```
[nd]: Other/Icons/no_data.svg
[ns]: Other/Icons/no_support.svg
[ps]: Other/Icons/probably_supported.svg
[fs]: Other/Icons/full_support.svg
