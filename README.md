This is for an Arch install running the xfce4 DE.  Borrowed heavily from the arcolinux team.  

When copying the bashrc file to new user's home don't forget to add the dot to the beginning of the filename.

If tap-to-click settings will not persist in setting add the 30-touchpad.conf file to /etc/X11/xorg.conf.d

For installing packages run
pacman -S - < masterList.txt
