Welcome to my `~` (crib)

<br>
<img src="assets/desktop.png" alt="img" align="center">
<br>
<br>

Here are some of my (disorganised) dotfiles.
Parts of this rice are based on dotfiles from [elenapan](https://github.com/elenapan/dotfiles) and [owl4ce](https://github.com/owl4ce/dotfiles). Thank you! ✨🤍

Fonts used:
 - `pacman -S ttf-bitstream-vera ttf-liberation`
 - Iosevka (Terminal)
 - Google Product Sans (WM, Notifications)
 - Typicons, Icomoon


Elements:
 - Terminal: [kitty](https://github.com/kovidgoyal/kitty)
 - Window manager: [openbox](http://openbox.org)
 - Bunnyfetch from [elenapan](https://github.com/elenapan/dotfiles)
 - Cutefetch from [cybarspace](https://github.com/cybarspace/cutefetch)
 - Music player: `ncmpcpp`
 - Music notification: `dunst`
 - Visualiser: `cava`
 - htop: `htop` (duh!)
 - My assignment: `vim`


Install on Arch-based distros with
```sh
$ pacman -S alsa-plugins alsa-tools alsa-utils arc-gtk-theme arc-icon-theme bspwm cava code dunst feh ffmpegthumbnailer kitty mpc mpd mpv ncmpcpp neofetch neovim openbox polybar sxhkd thunar thunar-archive-plugin thunar-media-tags-plugin thunar-volman xclip
```

Consider aliasing `gimme=startx ~/.xinitrc` so you can do something like `gimme openbox` to start the window manager.

Some essential packages for my build, and possibly yours,

```sh
$ pacman -S amd-ucode nvidia bluez bluez-utils tlp dos2unix firefox font-manager git gparted htop imagemagick networkmanager ntfs-3g pavucontrol polkit powertop pulseaudio pulseaudio-alsa ranger refind rsync scrot wget xf86-input-libinput xf86-video-nouveau xorg-xinit xorg-xinput xorg-xkill xorg-xrandr xorg-xrdb xorg-xset xorg-xwininfo xterm zip zsh
```
