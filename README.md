# Arch Linux

_**If you tried to change the GDM background with someother scripts, you first need to reset those changes. Other scripts may have the option --reset.**_

_**Recovery from fatal errors: If you encounter any problems after running this script..
log on to any tty and reinstall the package gnome-shell**_

Required Package: glib2
```
sudo pacman -S glib2
````

this script is to change the login screen background of Arch Linux which uses GDM as login manager only.

you can download the file `arch-gdm-login` via command line

    wget -qO - https://github.com/PRATAP-KUMAR/arch-gdm-login/archive/master.tar.gz | tar zx --strip-components=1 arch-gdm-login-master/arch-gdm-login

Once you downloaded the script `arch-gdm-login`. cd to the downloaded script file.

to set the background with Image  
`sudo ./arch-gdm-login /absolute/path/to/image`

to set the background with color  
`sudo ./arch-gdm-login \#aAbBcC` replace `#aAbBcC` with any vaid hex color code..

to reset everything that the script made..  
`sudo ./arch-gdm-login --reset`

![Black Color](https://i.imgur.com/075xQ38.png)

![Background as Image](https://i.imgur.com/DfsLbvk.png)

![Background as Image](https://i.imgur.com/RQz9V2d.png)
