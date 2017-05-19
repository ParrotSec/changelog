# Parrot Release changelog

This file contains the changelog of the Parrot Security distribution.

This changelog contains only a summary of the changes we consider being most relevant in each release



## From 3.5 to 3.6 (18/05/2017)
* Include linux 4.9.25
* Improve global mirror redirector
* Include an update reminder
* Upgrade to anonsurf 2.5
* Upgrade drivers pack
* Apply minor fixes to some startup daemons
* Make the system less memory hungry
* Upgrade many security tools
* Import new upstream releases from debian stretch and sid
* Apply minor fixes to parrot-interface
* Improve interface metapackages
* Fix some parrot-menu launchers
* Add Parrot AIR
* Improve ARMel and ARM64 support


## From 3.4.1 to 3.5 (08/03/2017)
* Include linux 4.9.13
* Include virtualbox and vmware guest support
* Include virt-manager (KVM/LXC virtual machine manager)
* Add cryptkeeper (EncFS system tray)
* Add sirikali (GUI front end to cryfs,gocryptfs,securefs and encfs)
* Re-include ZuluMount (zulucrypt mount utility)
* Include onboard virtual keyboard
* Include CUPS and printing support
* Include experimental cinnamon support
* Drop airmode (needs maintainance and will be included again soon)
* Drop penmode (deprecated and no longer maintained)
* Drop gtkdialog (discontinued)
* Drop all the packges depending on gtkdialog
* Import new upstream releases from debian stretch and sid
* Upgrade many security tools
* Re-include many tools not previously included in parrot full
* Replace firefox-esr 45 with firefox 51
* Improve and update Firefox security plugins
* Clean and improve firefox default configs

## From 3.4 to 3.4.1 (03/01/2017)
* Fix kernel modules for the installer
* Upgrade the installer

## From 3.3 to 3.4 (01/01/2017)
* Update the linux kernel from 4.8.11 to 4.8.15
* Fix i2p package and reinclude anonsurf
* Update geany IDE
* Include the freenet installer as a preview
* Include GNUNet
* Update zulucrypt
* Add new mirror servers to netboot images
* Fix beef-xss config file
* Import some updates from Debian
* Drop parrot cloud live iso support
  + Parrot cloud still exists through our netboot images,
  + our debian installation script and our VPS service


## From 3.2 to 3.3 (25/12/2016)
* include linux 4.8 kernel
* fix touchpad/multitouch support
* fix mismatching kernel installer
* update anonsurf
* fix minor MATE bugs
* include GCC 6.2
* update metasploit-framework 4.13
* switch to php 7
* upgrade most of the tools to their latest version


## From 3.1 to 3.2 (15/10/2016)
* fix and improve anonsurf
* add car hacking tools and automotive utilities
* include custom-compiled MATE 1.16 desktop
* fix GTK/MATE compatibility issues
* include Linux 4.7
* include major security updates
* remove libreoffice and kdevelop
* import full kde plasma support for parrot studio
* upgrade (and fix) many security tools
* start including packages from debian pkg-security
* fix mate-terminal update-alternatives priority
* fix penmode 2 start screen
* fix menuexec behavior
* include back traceroute, whois and other missing utilities
* add sbin to PATH env variable
* start conversion from Parrot Libre to Iris Project






## From 3.0 to 3.1 (26/07/2016)
* many tools updates
* switch from mysql to mariadb
* include php7 support
* include stability improvements
* update parrot-core
* update parrot-menu
* update parrot tools selection to include new tools
* fix systemd workarounds
* fix icon theme
* upgrade to linux 4.6
* update support for GCC 4.8.5, 4.9.3, 5.4.0 and 6.1.1
* update support for CLANG 3.6-33 and 3.8-2
* update drivers support
* include qtcreator 4.0.2
* include Qt framework 5.6.1 
* fix apt-parrot mirror selection system
* modify tasksel to include parrot flavours
* upgrade to zulucrypt 5.0
* upgrade to anonsurf 2.1
* include torbrowser launcher
* fix noscript plugin and firefox launchers
* Conky removed (waiting to fix the theme)
