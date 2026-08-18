# void-bullshit-go
[![Void Linux](https://img.shields.io/badge/Void_Linux-rolling-blue?logo=voidlinux&logoColor=white)](https://voidlinux.org)

> A collection of void packages that you might actually need.

i should've stored the templates...

# INSTALLATION

 install the .xbps package from releases page and run 

```bash
cd Downloads

# 1. Index the current directory as a repository
xbps-rindex -a *.xbps

# 2. Install the package from the indexed local directory
sudo xbps-install --repository=. packagename

```
you can also build the packages yourself if theyre outdated or anything

## Included Packages (more to come)

* **FjordLauncherUnlocked**: A fork of Fjord Launcher with offline support.
* **Heroic Games Launcher**: Native games launcher for Epic Games, GOG, and Amazon Games.
* **LocalSend**: An open-source cross-platform tool for sharing files and messages with nearby devices.
* **Vesktop**: A custom desktop client for Discord focused on performance and enhanced Vencord support.
* **Zen Browser**: Firefox Based Browser. ( Audio doesnt work for me, i'll fix this later.)
* **CachyOS Kernel**: Performance focused cachyos kernel.
