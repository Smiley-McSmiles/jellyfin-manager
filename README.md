![jellyfin-cli](.github/banner-dark.png?raw=true "Jellyfin Logo")
======

> v-1.3.7 CLI companion tool for the Jellyfin amd64.tar.gz installer

> Tested on Fedora 34/35/36, Ubuntu 22.04, Manjaro 21.3.6

> Should work on Any Debian, Arch, or RHEL Based Distro, and OpenSuse

### Features

* **Setup** - Sets up the initial install.
* **Update** - [URL - optional] Downloads and updates the current stable or supplied Jellyfin version.
* **Update-cli** - Updates this Jellyfin CLI Tool.
* **Update Beta** Downloads and updates to the current Jellyfin Beta version.
* **Disable** - Disable the jellyfin.service.
* **Enable** - Enable the jellyfin.service
* **Start** - Start the jellyfin.service.
* **Stop** - Stop the jellyfin.service.
* **Restart** - Restart the jellyfin.service.
* **Status** - Get status information on jellyfin.service.
* **Backup** - Input a directroy to output the backup archive.
* **Import** - Import a .tar file to pick up where you left off on another system.
* **Get Version** - Get the current installed version of Jellyfin.
* **Remove Version** - Remove a specific version of Jellyfin
* **Version Switch** - Switch Jellyfin version for another previously installed version.
* **Uninstall** - Uninstalls Jellyfin completely (Ignores the Media Directory).

### Getting Started

```shell
git clone https://github.com/Smiley-McSmiles/jellyfin-cli
cd jellyfin-cli
chmod ug+x setup.sh
sudo ./setup.sh
```

## Usage

```shell
jellyfin - The CLI Tool
-Created by Smiley McSmiles

Syntax: jellyfin -[b|d|e|h|i|p|r|s|S|u|U|ub|v|vs|X] [OPTIONS]
options:
-b     [DIRECTORY] Input directory to output backup archive
-d     Disable Jellyfin on System Start
-e     Enable Jellyfin on System Start
-h     Print this Help
-i     [FILE.tar] Input file to Import jellyfin-backup.tar
-p     Reset the permissions of Jellyfins Media Library
-r     Restart Jellyfin
-s     Start Jellyfin
-S     Stop Jellyfin
-t     Status of Jellyfin
-u     [URL - optional] Downloads and updates the current stable or supplied Jellyfin version.
-U     Update Jellyfin - The CLI Tool
-ub    Update Jellyfin to the most recent Beta
-v     Get the current version of Jellyfin.
-vs    Switch Jellyfin version for another previously installed version.
-rv    Remove a Jellyfin version
-X     Uninstall Jellyfin Completely
```

### License

   This project is licensed under the [GPL V3.0 License](https://github.com/Smiley-McSmiles/jellyfin-cli/blob/main/LICENSE).

