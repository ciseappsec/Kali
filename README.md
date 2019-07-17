# Kali
Custom Kali image with a copy of the class repo.

This iso is built from git clone git://gitlab.com/kalilinux/build-scripts/live-build-config.git

The following have been changed from the default iso:
* added an AppSec folder under /root that is a git clone of https://github.com/ciseappsec/AppSec.git
* added a boot script to perform a git pull every time kali is rebooted

## Creation of a bootable USB
This is very well documented here: https://docs.kali.org/downloading/kali-linux-live-usb-install. Just use the ISO in this repo instead.

## Using the iso in a Virtual Machine
There are free Virtual Machines where you can run the ISO under.
