# Kali
Custom Kali image with a copy of the class repo.

This iso is built from git clone git://gitlab.com/kalilinux/build-scripts/live-build-config.git

The following have been changed from the default iso:
* added an AppSec folder under /root that is a git clone of https://github.com/ciseappsec/AppSec.git
* added a boot script to perform a git pull every time kali is rebooted
