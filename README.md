# Ubuntu with [Sway](https://github.com/swaywm/sway) Wayland compositor

![2022-05-24T21:15:50,611785616+04:00](https://user-images.githubusercontent.com/11344982/170094239-a31829b7-f53c-4526-8f9b-6f87d18fe156.png)


### This project is an attempt to take the best from Sway, Wayland and Ubuntu world's. It uses some very useful CLI-based Wayland apps along with some graphical apps to meet the needs of most users.

**Apps included:**

* [Azote](https://github.com/nwg-piotr/azote)
* [Autotiling](https://github.com/nwg-piotr/autotiling)
* [Cliphist](https://github.com/sentriz/cliphist)
* Firefox
* Flatpak
* [Foot](https://codeberg.org/dnkl/foot)
* Gimp
* Gparted
* [Greetd](https://sr.ht/~kennylevinsen/greetd/)
* [Grimshot](https://github.com/swaywm/sway/blob/master/contrib/grimshot)
* htop
* [Kanshi](https://git.sr.ht/~emersion/kanshi)
* [Khal](https://github.com/pimutils/khal)
* LibreOffice
* [Neovim](https://github.com/neovim/neovim)
* Pavucontrol
* Pluma
* [Poweralertd](https://sr.ht/~kennylevinsen/poweralertd/)
* Pulsemixer
* [Swayimg](https://github.com/artemsen/swayimg)
* Ranger
* Thunar
* Thunderbird
* [Tuigreet](https://github.com/apognu/tuigreet)
* [nwg-wrapper](https://github.com/nwg-piotr/nwg-wrapper)
* [nwg-drawer](https://github.com/nwg-piotr/nwg-drawer)
* Ubuntu Driver Manager
* Waybar
* [Wdisplays](https://github.com/luispabon/wdisplays)
* [wf-recorder](https://github.com/ammen99/wf-recorder)
* [wlr-randr](https://sr.ht/~emersion/wlr-randr/)
* [Zathura](https://github.com/pwmt/zathura)

**Config files:**
```
~/.config/sway/config - common config that includes all user and system config's
~/.config/sway/config.d/ - user defined config's (put your config's here to overwrite system's one)
~/.config/sway/variables.d/ - user defined variables for defalut apps and settings (put your own variables here)
~/.config/waybar/ - Waybar config's

/etc/sway/config.d/ - system config's for autostart applications and settings
/etc/sway/modes/ - system default modes for Sway (keybindings)
/etc/sway/outputs/ - system default settings for output configuration
/etc/sway/inputs/ - system default settings for input devices
/etc/sway/variables - system default variables for default apps and settings

/usr/share/sway/scripts/ - scripts for weather inficator, WOB indicator, etc.
/usr/share/sway/themes/ - theme and color settings
```
