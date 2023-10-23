the same extension, but a few changes have been made for partial compatibility with gnome since version 42. the effects of opening the top panel menu, dash menu, desktop menu and window menu do not work.

to install, just run the script INSTALL.sh after enabling the script execution permission:

```bash
git clone https://github.com/SharaGGa/Animation-Tweaks-fixed-for-gnome-above42.git
cd Animation-Tweaks-fixed-for-gnome-above42
chmod +x INSTALL.sh
./INSTALL.sh
```
if you are interested in trying my config, then to install the config, enter the following command by opening the terminal in the folder with the ``.dconf`` file:

```bash
dconf load /org/gnome/shell/extensions/animation-tweaks/ < animations-set.dconf
```
