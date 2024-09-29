### 🏯 Contents 🏯

<a><img src="https://i.pinimg.com/originals/31/26/51/3126516d77b2f81eb31c088f605b2378.gif" width="30%" height="40%" title="🙂" align="right"></a>
<br/><br/>

- <b>[GRUB Themes](#previews)</b>
   - [Ver. 1](#1.)
   - [Ver. 2](#2.)
   - [Eng ver. 2](#eng2)

- <b>[🔧 Installation](#installation)</b>
  - [First method](#1.)
  - [Second method (wip script, soon)](#2)


## Installation
##1.
<a><img src="https://i.pinimg.com/originals/2c/0e/de/2c0ede6151436eeaf2f96ccfa6decf89.gif" width="30%" height="30%" title="🙂" align="right"></a>
- Open your terminal
- Copy the repository and unzip

```
    https://github.com/Zerabalus/Video-Games-Grub-Themes.git
```

- cd to where you copied it, on your terminal:
```
 sudo cp -r <theme> /usr/share/grub/themes
```

- Or like in my case (DEBIAN-ARCH)

>Arch/Debian `sudo cp -r <theme> /boot/grub/themes`

- Then edit the name of the grub theme you want:
```
sudo nano /etc/default/grub
```
```
GRUB_THEME="/boot/grub/themes/<theme>/theme.txt"
```
- Update the grub
```
sudo grub-mkconfig -o /boot/grub/grub.cfg
```

- Reboot your pc
```
reboot
```

