# SELinux Enforce

This module switches SELinux to enforce mode during boot process.

This module intentionally lowers security settings of your
phone. Please, don't use it if you don't know what you are doing.

The module will not work if your kernel compiled with always enforcing config,
e.g., stock samsung kernels.

## How to install:

Stable release:
1. Dowload latest selinux_enforce.zip from releases page
   https://github.com/a-st/selinux_enforce/releases
2. MagiskManager -> Modules + Downloads/selinux_enforce.zip -> Reboot

Master branch:
1. git clone https://github.com/a-st/selinux_enforce
2. cd selinux_enforce
3. make install

## Support

- [Matrix](@a-st:matrix.org)
- [GitHub](https://github.com/a-st)
