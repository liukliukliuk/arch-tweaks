# Arch Linux tweaks

This is a collection of the tweaks and modification I've made to my Arch Linux installation over the months. These may be applicable to other distros, but please check first before doing anything.

``` 
## su
## pacman -Syu
## pacman -S base-devel gnome-common libgda6 rust jq aria2 xdelta3
## pacman -S --needed lib32-mesa vulkan-intel lib32-vulkan-intel vulkan-icd-loader lib32-vulkan-icd-loader locate
## updatedb
``` 

# Remove Flatpak

``` 
## flatpak uninstall --all --delete-data
## rm -rf .local/share/flatpak && rm -rf /var/lib/flatpak
## pacman -R flatpak
``` 

# Wine and dependency hell
``` 
## pacman -S wine-staging winetricks wine-mono
## pacman -S giflib lib32-giflib libpng lib32-libpng libldap lib32-libldap gnutls lib32-gnutls mpg123 lib32-mpg123 openal lib32-openal v4l-utils lib32-v4l-utils libpulse lib32-libpulse alsa-plugins lib32-alsa-plugins alsa-lib lib32-alsa-lib libjpeg-turbo lib32-libjpeg-turbo libxcomposite lib32-libxcomposite libxinerama lib32-libxinerama ncurses lib32-ncurses opencl-icd-loader lib32-opencl-icd-loader libxslt lib32-libxslt libva lib32-libva gtk3 lib32-gtk3 gst-plugins-base-libs lib32-gst-plugins-base-libs vulkan-icd-loader lib32-vulkan-icd-loader cups samba dosbox
``` 

# Other apps
``` 
## pacman -S spotify lutris discord extension-manager qbittorrent gdm-settings neofetch gnome-browser-connector spotify-adblock menulibre openssl-1.1
``` 

# Extensions
### Aylur's Widgets
### Blur my Shell
### Dash to Dock
### Desktop Icons NG (DING)
### Emoji Selector
### Espresso
### Hide Activities Button
### Just Perfection
### Looking Glass Button
### Pano - Clipboard Manager
### Rounded Corners
### RunCat
