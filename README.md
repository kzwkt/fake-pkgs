# fake-pkgs
```
https://packages.debian.org/stable/amd64/xfce4-helpers/filelist
/etc/xdg/xfce4/helpers.rc,/usr/share/xfce4/helpers/termanl-names.desktop, browser-name.desktop etc help in setting default apps


https://packages.debian.org/bookworm/amd64/x11-xserver-utils/filelist
x11-xserver-utils  needs cpp(c preprocessor) dont know which binary excatly
 iceauth, a tool for manipulating ICE protocol authorization records;
 - rgb;
 - sessreg, a simple program for managing utmp/wtmp entries;
 - xcmsdb, a device color characteristic utility for the X Color Management
   System;
 - xgamma, a tool for querying and setting a monitor's gamma correction;
 - xhost, a very dangerous program that you should never use;
 - xmodmap, a utility for modifying keymaps and pointer button mappings in X;
 - xrandr, a command-line interface to the RandR extension;
 - xrdb, a tool to manage the X server resource database;
 - xrefresh, a tool that forces a redraw of the X screen;
 - xset, a tool for setting miscellaneous X server parameters;
 - xsetmode and xsetpointer, tools for handling X Input devices;
 - xsetroot, a tool for tailoring the appearance of the root window;
 - xstdcmap, a utility to selectively define standard colormap properties;
 - xvidtune, a tool for customizing X server modelines for your monitor.


upower pulls dbus and some things until dbus-broker provides dbus lets use dummy 

i have python from anaconda so instally dummy for now
sudo dpkg -i  cpp_99.9.9_all.deb  xfce4-helpers_99.9.9_all.deb python-dummy_1.0_all.deb dbus_99.9.9_all.deb
sudo apt install xfce4

Suggested packages:
  sensible-utils notification-daemon devhelp iso-codes thunar-archive-plugin thunar-media-tags-plugin gvfs-backends nickle cairo-5c xorg-docs-core
  xfce4-goodies xfce4-power-manager fortune-mod sudo
Recommended packages:
  liburi-perl upower libxfce4util-bin gvfs policykit-1-gnome | polkit-1-auth-agent thunar-volman tumbler udisks2 xdg-user-dirs desktop-base tango-icon-theme
  xfce4-notifyd xorg pavucontrol pulseaudio light-locker | xfce4-screensaver | xscreensaver | gnome-screensaver | mate-screensaver colord x11-utils xiccd
T
```
