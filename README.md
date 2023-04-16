# devilarch-flux
A flux configuration file that I use to stylize my desktop environment using fluxbox
# Further Setup

- Install lightdm
  - Install lightdm-gtk-greeter
  - In `/etc/lightdm/lightdm.conf`:
    - Under **[Seat:*]**:
      - `user-session=fluxbox`
      - `guest-session=lightdm-gtk-greeter`
      - `display-setup-script=xrandr -s 1920x1080`
  - In `/etc/lightdm/lightdm-gtk-greeter.conf`:
    - Under **[greeter]**:
      - `background=/usr/share/pixmaps/image.jpg-png`
- Install terminus-font
- Install xcompmgr
  - In `/etc/`:
    - Create **xprofile** and put `xcompmgr -c &`
- Install xfce4-terminal
  - Configure terminal settings to enable transparency

*Oh yea, install parcellite but still haven't got to that yet..*
