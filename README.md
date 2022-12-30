# Arch install

## _The GPG error at run archinstall_

If you get several errors when starting the **archinstall** installation script, it's due to and error in the PGP keys.

To fix it just type:


>pacman-key --init

>pacman-key --populate archlinux


Retype **archinstall** and the problem will be fixed.

Please visit the Arch Wiki to see more information 

[Arch Wiki Package Signing](https://wiki.archlinux.org/title/Pacman/Package_signing)

Xavier M. 2022
