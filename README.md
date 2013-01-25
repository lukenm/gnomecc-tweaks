gnomecc-tweaks
==============

This repository is for storing gnomecc tweaks to various gnome themes.

Brown n Grey Theme
------------------

See http://www.upubuntu.com/2012/02/12-new-best-gnome-shell-themes-for.html

Installation:

    mkdir ~/.themes
    sudo apt-get install gnome-tweak-tool
    wget -O brown_n_grey.zip http://goo.gl/vY08y
    unzip brown_n_grey.zip -d ~/.themes
    gsettings set org.gnome.desktop.interface gtk-theme 'Brown n Grey Dark GTK '
    gconftool-2 --set --type string /apps/metacity/general/theme 'Brown n Grey Dark GTK '

Then using GNOME Color Chooser, install brown-n-grey-tweaks.gnomecc


