### 🏯 Contents 🏯

<a><img src="https://i.pinimg.com/originals/42/4b/e8/424be84e5ba9c497650a99faaf6e684f.gif" width="50%" height="40%" title="🙂" align="right"></a>
<br/><br/>

- <b>[GRUB Themes](#previews)</b>
   - [Ver. 1](#1)
   - [Ver. 2](#2)


- <b>[🔧 Installation](#installation)</b>
  - [First method]()
  - [Second method (wip script, soon)]()


## Installation

<a><img src="https://i.pinimg.com/originals/20/70/b9/2070b9572e412ba394cb6bc14950d0e6.gif" width="25%" height="30%" title="🙂" align="right"></a>
- Open your terminal
- Copy the repository or unzip

```
    https://github.com/Zerabalus/Ghost-of-Tsushima-GRUB
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


# Previews
#  Ver. 1
<div align="center" style="display:inline">
<img alt="1 preview" src="img/v1.png" width="1016px" />
</div>

#  Ver. 2
<div align="center" style="display:inline">
<img alt="2 preview" src="img/v2.png" width="1016px" />
</div>