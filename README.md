# install_xubuntu
Commands and notes how to install xubuntu to speed it up the next time.

0. Back-up /home (Documents, Pictures, Videos, Music, Reactor, .thunderbird, KeepassX key file, .config). Remote copy scp.

~/.config/chromium
~/.config/xfce4
~/.config/zim

1. Download ISO and create bootable disk. Unetbootin works on Windows + Linux.
```
sudo add-apt-repository ppa:gezakovacs/ppa
sudo apt-get update
sudo apt-get install unetbootin
```
2. Install manually
- OS
Appearance
Style = AdWaita
Icons = Xfce darkest
Font = 14 pt
- VeraCrypt
- Google Chrome
- Zim wiki
- Mega
- Eclipse
ToDo in docker?
- mysql-server
- openssh-server
- docker-compose

3. Install scripted
- KeePassX
- Docker
- Double Commander
- Calibre
- Cheese
- Chromium
- Gimp
- Gnome system monitor
- Clipman (ToDo: panel launcher)
- Audacious
- exfat-fuse exfat-utils (for SD cards >32 GB)
- VLC
- git
- GThumb
- gstreamer library (video plugin for gthumb)
- jhead
- Lightning calendar
- Octave
- rar
- Shutter (if 'edit image' is disabled, follow https://itsfoss.com/shutter-edit-button-disabled/)
- Skype
- Virtualbox (must confirm EULA manually)
- Capslock indicator
- SDKman + java
- Youtube-dl
```
sudo apt-get install keepassx
sudo apt install docker.io
sudo apt-get install doublecmd-gtk
sudo apt-get install calibre
sudo apt-get install cheese
sudo apt-get install chromium-browser
sudo apt-get install gimp
sudo snap install gnome-system-monitor
sudo apt-get install xfce4-clipman
sudo apt-get install audacious
sudo apt-get install exfat-fuse exfat utils
sudo snap install vlc
sudo apt-get install git
sudo apt-get install gthumb
sudo apt install gstreamer1.0-gtk3
sudo apt-get install jhead
sudo apt-get install xul-ext-lightning
sudo apt-get install octave
sudo apt-get install rar
sudo apt-get install shutter
sudo snap install skype --classic
sudo apt virtualbox virtualbox-ext-pack
sudo add-apt-repository ppa:tsbarnes/indicator-keylock
sudo apt update
sudo apt install indicator-keylock
sudo apt-get install curl
curl -s "https://get.sdkman.io" | bash
sdk install java
sudo apt-get install youtube-dl
```

