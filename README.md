<div align="center">

## 💌 ** kimuxer's Gentoo Hyprland Install Script ** 💌

![GitHub Repo stars](https://img.shields.io/github/stars/kimuxer/Gentoo-Hyprland?style=for-the-badge&color=cba6f7) ![GitHub last commit](https://img.shields.io/github/last-commit/kimuxer/Gentoo-Hyprland?style=for-the-badge&color=b4befe) ![GitHub repo size](https://img.shields.io/github/repo-size/kimuxer/Gentoo-Hyprland?style=for-the-badge&color=cba6f7)


<br/>
</div>

#### Hyprland-Dots-showcase 
<p align="center">
    <img align="center" width="49%" src="https://raw.githubusercontent.com/JaKooLit/screenshots/main/Hyprland-ScreenShots/Arch-v2/Arch-Default-Layout.png" /> <img align="center" width="49%" src="https://raw.githubusercontent.com/JaKooLit/screenshots/main/Hyprland-Dots-Showcase/dark-theme.png" />   
   <img align="center" width="49%" src="https://raw.githubusercontent.com/JaKooLit/screenshots/main/Hyprland-Dots-Showcase/Light-theme.png" /> <img align="center" width="49%" src="https://raw.githubusercontent.com/JaKooLit/screenshots/main/Hyprland-ScreenShots/Arch-v2/Another-Screenshot.png"" /> 
</p>

<p align="center">
    <img align="center" width="49%" src="https://raw.githubusercontent.com/JaKooLit/screenshots/main/Hyprland-Dots-Showcase/default-waybar.png" /> <img align="center" width="49%" src="https://raw.githubusercontent.com/JaKooLit/screenshots/main/Hyprland-Dots-Showcase/rofi.png" />   
   <img align="center" width="49%" src="https://raw.githubusercontent.com/JaKooLit/screenshots/main/Hyprland-Dots-Showcase/wlogout-dark.png" /> <img align="center" width="49%" src="https://raw.githubusercontent.com/JaKooLit/screenshots/main/Hyprland-Dots-Showcase/showcase2.png"" /> 
   <img align="center" width="49%" src="https://raw.githubusercontent.com/JaKooLit/screenshots/main/Hyprland-Dots-Showcase/waybar-layout.png" /> <img align="center" width="49%" src="https://raw.githubusercontent.com/JaKooLit/screenshots/main/Hyprland-Dots-Showcase/waybar-style.png"" /> 
</p>


#### 📷 Important note: This is just my personal experimental project, because Gentoo is special. Depending on everyone's settings, the final system will have many differences, so this script is not universal.
This script can probably only provide a little reference for people who have a certain understanding of gentoo and can manually modify the script.



> [!IMPORTANT]
> It has just been forked, so it is temporarily unavailable.



#### ✨ Costumize the packages to be installed
- inside the install-scripts folder, you can edit 00-hypr-pkgs.sh. Care though as the Hyprland Dots may not work properly!
- default GTK theme if agreed to be installed is Tokyo night GTK themes (dark and light) + Tokyo night SE icons



#### ✨ to run
> clone this repo (latest commit only) to reduce file size download by using git. Change directory, make executable and run the script
```bash
git clone --depth=1 https://github.com/kimuxer/Gentoo-Hyprland.git
cd Gentoo-Hyprland
chmod +x install.sh
./install.sh
```

<p align="center">
    <img align="center" width="100%" src="https://raw.githubusercontent.com/JaKooLit/Arch-Hyprland/main/Installer.png" />

#### ✨ for ZSH and OH-MY-ZSH installation
> installer should auto change your default shell to zsh. However, if it does not, do this
```bash
chsh -s $(which zsh)
zsh
source ~/.zshrc
```
- reboot or logout
- by default agnoster theme is installed. You can find more themes from this [`OH-MY-ZSH-THEMES`](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes)
- to change the theme, edit ~/.zshrc . Look for ZSH_THEME="desired theme"


#### 🙋 👋 Having issues or questions? 
- for the install part, kindly open issue on this repo
- for the Pre-configured Hyprland dots / configuration, submit issue [`here`](https://github.com/JaKooLit/Hyprland-Dots/issues)

#### 🔧 Proper way to re-installing a particular script from install-scripts folder
- CD into Arch-Hyprland Folder and then ran the below command. 
- i.e. `./install-scripts/gtk-themes` - For reinstall GTK Themes.


#### 👍👍👍 Thanks and Credits!
- [`Hyprland`](https://hyprland.org/)
- [`JaKooLit`](https://github.com/JaKooLit)

