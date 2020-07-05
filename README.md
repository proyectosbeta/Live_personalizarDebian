# Personalizar Debian
Personalizamos Debian Buster a medida

* Sitio oficial: https://www.debian.org/
* Descargamos ISO: https://cdimage.debian.org/debian-cd/current/amd64/iso-cd/debian-10.4.0-amd64-netinst.iso

## Hardware utilizado:
* 2 CPU
* 30 GB de disco (LVM)
* 4 GB de RAM

## Software recomendado:
* sudo (sudo apt install sudo) proyectosbeta ALL=(ALL) ALL
* htop (sudo apt install htop)
* tmux (sudo apt install tmux)
* UFW (Firewall) (sudo apt install ufw​​​)

## Escritorios:
* XFCE:
   * Mínimo: sudo apt install --no-install-recommends xorg xfce4 slim dbus-x11
   * Completo: sudo apt install xfce4 xfce4-goodies 
* KDE Plasma:
   * Standard: sudo apt install kde-standard kde-l10n-es gtk2-engines-oxygen gtk2-engines-qtcurve
* Gnome:
  * Mínimo: sudo apt install gnome gnome-shell

## Gestores de sesión:
* lightdm (sudo apt install lightdm)
* sddm (sudo apt install sddm)

## Reconfigurar gestor de sesión:

  sudo dpkg-reconfigure ligthdm


## VirtualBox additions:

  sudo apt install build-essential dkms linux-headers-$(uname -r)
