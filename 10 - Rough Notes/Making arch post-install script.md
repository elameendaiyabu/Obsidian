### Notes
- [x] automate open-vpn setup
- [x] switch capslock and escape
- [x] setup tmux
- [x] setup node
- [x] setup yay
- [x] install yay apps
- [x] setup btop
- [ ] setup hyprland and all add ons
- [x] setup personal git and add all configs
- [x] setup oh my posh

###  Git Configs
user.name= ...
user.email= ...
core.editor=nvim
rerere.enabled=true
pull.rebase=true
init.defaultbranch=master

### installs i might need for hyprland config
### System
pipewire                                               # audio/video server
pipewire-alsa                                          # pipewire alsa client
pipewire-audio                                         # pipewire audio client
pipewire-jack                                          # pipewire jack client
pipewire-pulse                                         # pipewire pulseaudio client
gst-plugin-pipewire                                    # pipewire gstreamer client
wireplumber                                            # pipewire session manager
pavucontrol                                            # pulseaudio volume control
pamixer                                                # pulseaudio cli mixer
networkmanager                                         # network manager
network-manager-applet                                 # network manager system tray utility
bluez                                                  # bluetooth protocol stack
bluez-utils                                            # bluetooth utility cli
blueman                                                # bluetooth manager gui
brightnessctl                                          # screen brightness control
udiskie                                                # manage removable media
### Display Manager
sddm                                                   # display manager for KDE plasma
qt5-quickcontrols                                      # for sddm theme ui elements
qt5-quickcontrols2                                     # for sddm theme ui elements
qt5-graphicaleffects                                   # for sddm theme effects

### Window Manager
hyprland                                               # wlroots-based wayland compositor
dunst                                                  # notification daemon
rofi-lbonn-wayland-git                                 # application launcher
waybar                                                 # system bar
swww                                                   # wallpaper
swaylock-effects-git                                   # lock screen
wlogout                                                # logout menu
grimblast-git                                          # screenshot tool
hyprpicker                                             # color picker
slurp                                                  # region select for screenshot/screenshare
swappy                                                 # screenshot editor
cliphist                                               # clipboard manager

### Dependencies
polkit-gnome                                           # authentication agent
xdg-desktop-portal-hyprland                            # xdg desktop portal for hyprland
pacman-contrib                                         # for system update check
python-pyamdgpuinfo                                    # for amd gpu info
parallel                                               # for parallel processing
jq                                                     # for json processing
imagemagick                                            # for image processing
qt5-imageformats                                       # for dolphin image thumbnails
ffmpegthumbs                                           # for dolphin video thumbnails
kde-cli-tools                                          # for dolphin file type defaults
libnotify                                              # for notifications

### Theming
nwg-look                                               # gtk configuration tool
qt5ct                                                  # qt5 configuration tool
qt6ct                                                  # qt6 configuration tool
kvantum                                                # svg based qt6 theme engine
kvantum-qt5                                            # svg based qt5 theme engine
qt5-wayland                                            # wayland support in qt5
qt6-wayland                                            # wayland support in qt6

### Applications
firefox                                                # browser
kitty                                                  # terminal
dolphin                                                # kde file manager
ark                                                    # kde file archiver
vim                                                    # terminal text editor
code                                                   # ide text editor

### Shell
eza|zsh                                                # file lister for zsh
oh-my-zsh-git|zsh                                      # plugin manager for zsh
zsh-theme-powerlevel10k-git|zsh oh-my-zsh-git          # theme for zsh
lsd|fish                                               # file lister for fish
starship|fish                                          # customizable shell prompt
fastfetch                                              # system information fetch tool
pokemon-colorscripts-git|zsh                           # display pokemon sprites

### HyDE
hyde-cli-git                                           # cli tool to manage hyde


#### copy to /etc/vconsole.conf to load custom keyboard conf on startup
KEYMAP=/usr/local/share/kbd/keymaps/personal.map






