# Nyarch Grub Theme
### This is the Grub theme for the [Nyarch linux distro](https://github.com/NyarchLinux/NyarchLinux)

It conains art from [ventoy-themes](https://github.com/odiegoduarte/ventoy-themes) grub theme, [FlatSense](https://github.com/ForsetGump1952/FlatSense) grub theme and the background by [raviolimavioli](https://www.pixiv.net/en/artworks/89596288) 
<br><br> 

<img src="preview.png" alt="Nyarch Grub theme preview" width="400"> <img src="terminal.png" alt="Nyarch Grub terminal preview" width="400"> 

<br> 

### Manual installation
 -  Download the theme using ```git clone https://github.com/princess-wawa/Nyarch-Grub-Theme```
 -  Copy the files into ur Grub folder using ````sudo cp -r Nyarch-Grub-Theme/Nyarch-theme /boot/grub/themes````
 -  Then edit the name of the grub theme you want in `/etc/default/grub` using ````sudo nano /etc/defaults/grub````
   - Find the line starting with `#GRUB_THEME` and change it to `GRUB_THEME="/boot/grub/themes/Nyarch-theme/theme.txt"`
 -  Upgrade your git config using ```sudo grub-mkconfig -o /boot/grub/grub.cfg```
 -  finally, you can `reboot`

<br><br> 

