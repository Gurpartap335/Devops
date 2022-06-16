### Desktop environment

### GNU - GNU is not Unix

### What is desktop environment ?
A desktop environment is the bundle of components that provide you common graphical user interface(GUI) elements like icons, wallpaper, widgets.
#### GNOME is a desktop environment
There are more DE and these DE detemines what your Linux system looks like and how you interact with it.
examples like clothes
- KDE
- Xfce
- LXDE

echo $XDG_CURRENT_DESKTOP

If the screen shows dollar sign ($) and hash # on the left of the blinking cursor, you are in a command-line environment.
- $ : you are normal user.
- # : you are system adminstrator(root)

prompt usually show the login username, machine hostname and curent working directory
[shinji@fedora ~]$
~ tilde means home directory i.e default directory when first loggend in.

use man uname to practise how to read man and practises tag.

uname -n
cat /etc/os-release

Updating fedora
- dnf check-update
- dnf updateinfo
- sudo dnf upgrade
- sudo shutdown -r now
for checking run dnf updateinfo

