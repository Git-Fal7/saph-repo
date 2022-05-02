# saph-repo
my arch repo, with packages i use
# whats in it?
``openbox`` openbox that is lighter, uses a better theme and snap aero. 

``lightdm-qt5-greeter`` a lightdm greeter made in qt 

``nm-tray`` networkmanager frontend in qt 

``pavutray`` simple tray for pavucontrol-qt 

``qt5-polkit-agent`` lxqt-polkit without lxqt libs 

``qt5-styleplugins`` gtk style for qt 

 ``pcmanfm-qt-patched`` & ``libfm-qt-patched`` patched version of pcmanfm-qt + libfm-qt for some QoL improvements
 
 ``st`` st that has scrollback + fitting theme
 
 ``qmpanel`` lighter lxqt-panel
 
# installing
put this in your ``/etc/pacman.conf``
```
[saph-repo]
SigLevel = Optional TrustedOnly
Server = https://git-fal7.github.io/$repo/$arch
```
