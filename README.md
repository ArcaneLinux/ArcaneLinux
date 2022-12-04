### Arcane Linux 👋

Here are some ideas to get you started:

- 🔭 I’m currently working on Arcane Linux
- 📫 How to reach me: You can check out my persona page @RRSolomon or on Twitter @HandsomeWryter
- ⚡ Fun fact: I like Linux :D

# What is it?
Arcane Linux (I just call it Arcane, tbh) is a custom Arch Linux install that will be game ready out of the box. This is mainly for my purposes. It was put together so I can ust install Arch without needing to constantly be reinstalling everything all at once. Yes, I know I could just write my own deploy script, but this should be much easier in the long run. Work smarter, not harder...

---

# Variants of Arcane
## Arcane Base
- Arcane Installation Scripts that installs Arcane and drops you off in a TTY
- Doesn't come with anything out of the box. Essentially a base Arch Level Install with a few tweaks.

## Arcane
- Basic Arcane Installation
- Contains programs tailored for gaming and basic Dev.

## Arcane Xtended
- Comes with my configs, and 

## Arcane Lite
- Chose a Desktop Environment/Tiling Window Manager, and enjoy the blankslate :D
- This will install my spin on a specific Desktop Environment or Tiling Window Manager.
- This version of the Arcane that doesn't come with any programs out of the box. This is just the DE or TWM of your choosing.

## Arcane Suckless
- Arcane...but with all the Suckless programs with my patched versions of said Suckless programs.

---

# Phase One | Arcane Installation Script
## Description
**Phase One** consists of getting the basic Arch Installation Script up and running in order to pave the way to creating the final product. Eventually, I'll go and make an ArchISO packaged with the script packaged within the ISO for an Offlin Install.

## Goals
- This phase is simply to install Arch Linux and drop you in a TTY
- Script will have basic partition system.

### Partition System
This will follow a basic partition system. Below is a table that goes into the specifics of the partition scheme. 

_**Note:** This is going to be based on off of a 1TB hard drive. This isn't required, but it is the average size of hard drive that I have._

| Partition Section | Type | Size |
|-  | - | - |
| Boot | efi | 300MB |
| Swap | swap | 10GB | 
| / |  ext4 | 100GB |
| /home | ext4 | Remainder of Storage |

---

# Phase Two | Arcane
As I've mentioned above, Arcane is basically my deploy script of Arch Linux with some tweaks...mainly my own branding applied to it. lol...Anyway, this

## Features
- **Kernal**: Zen or Liquorix
- **Winodw Manager**: Spectrwm, Polybar, Rofi
	- Requires [xlock](https://man.archlinux.org/man/community/xlockmore/xlock.1.en)
- **Flavors**: XFCE, KDE, Gnome (Instlal Gnome Tweaks)
- **Terminal**: [[Alacritty]]
	- Customize using https://www.Terminal.sexy
	- Have to download from the [Alacrity Github Repository](https://github.com/alacritty/alacritty).
- **Compositor**: Picom
- **File Explorer**: PcManFM
- **Shell**: Bash (Test out Fish)
- **Image Viewer**: gpicview
- **Wallpaper Setter**: Nitrogen
- Base-Devel have to be installed for building arch packages
- Starship commandd
- SysTray Program: 
- Volume manager
- Sudo Program: Doas
- Init System: Test Different Ones

## Packages Out of the Box
- Firefox Everyday
	- Dark Reader
	- Pirvacy Badger
	- uBlock Origin
	- Keepass-XC Extension
	- Decenteralleyes
	- Canvas Blocker
	- Sponsor Block
	- Clear URLS
	- Buku Front End
- Steam
- Lutris
- RetroArch
    - No...Bios files and all that will not be included.
- qBitTorrent
- jDownloader2 (Create Binary)
- VLC
- LibreOffice with Modifications to Make it More Like 
- Keepass-XC
- Timeshift (Create Binary)
- Obsidian
- Discord
- Doom EMACS (Create Binary)
- VSCodium
	- Use `vscodium` from AUR
- Scrivener3 (Create Binary)
- Neofetch
- HTOP
- WIne
- Wine Tricks
- Yay or Paru (This one is maintained.)
- GUI AUR and GUI Pacman Package Manager
- MegaSync
	- Use `Megasync-bin` from AUR to get this working
- GitHub Sync
	- Use `github-desktop-bin` from AUR
 
## Branding
I believe that branding is a very important feature when it comes to a Linux "distro". I'm going to basically make my own themes, wallpapers, icons, and sounds for Arcane. So far I've come up with some Ideas.
 
### Themes
1. **Nightwave** - Synthwave inspired theme with cyan and purple accents.
2. **Darkwave** - Synthwave inspirated theme with faded wallpaper, and blkac backgrounds, and purple accents.
3. **Lightwave** - Synthwave inspired theme with standard wallpaper, and pink, cyan, and purple accents. Light theme option.
4. **Galactic** - Purple and Cyan color (Think plaentary duality) with the new JWST photos, and colorized to be purple and cyan.
 
#### Requirements for Themes
All themes must have the following included:
- Custom icons
- Customized WM, and settings
- Customized terminal
- Custom GTK theme

### Wallpaper Packs
The very first thing that you see when you turn on your computer is your wallpaper, so it goes without saying that a good looking wallpaper is super important for the distro's identity and first impressions.
1. **Country Pack** - Beautiful sceneic views from various countries.
2. **Galactic Pack** - Contains various galaxy wallpapers 
3. **Abstract Pack** - This will contain various abstract art and different 
4. **Dark Pack** - Contains various dark wallpaers that are kinda horror based since I'm a major horror buff lol
5. **FOR SCIENCE Pack** - Various science and science fiction wallpapers I find on the internet.
6. **Suckless Wallpaper Pack*** - Super minimal wallpapers!
 
---
# Phase Three: Arcane Xtended
Basically what I would consider the "main" branch of Arcane because it'll be my Arcane install with everything. Basically it'll contain all the customizations that I have made.

## Included Desktop Environments
- XFCE - No XFCE Goodies in Lite
- KDE - No KDE Applications in Lite

## Included Window Managers
- SpectrWM
- i3 w/ Gaps
- DWM
- Berry
- Awesome
- Sway
- HerbsLuftWM
- QTile

---

# Phase Four: Arcane Lite
Basically, this is all my Arcane Installation with with an emphasise on being lightweight since I understand that not all computers are super brutal desktops with 12490GB of Ram and 192949 Core. My goal with this is to try and optimize Arcane for lower-end computers.

---

# Phase Five: Arcane Suckless
Basically Arcane with Suckless programs. This will come with basic Wallpapers lol
