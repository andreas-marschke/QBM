##QBM (Quick Boot Manager) is an oversimplified init and DM system for Linux
 It allows to boot to the desktop in less than 1 second by hardcoding and
 parallelizing much of the process.

 Edit the variables main.c and the various scripts to fit your hardware and
 your needs and recompile.

- @author Emmanuel Lepage Vallee (Elv13) <elv1313@gmail.com>
- @author Andreas Marschke (andreas-marschke) <andreas.marschke@gmail.com>

<div style="color: red; font-weight: bold;">
 Disclaimer
 THE DEFAULT VERSION WILL NOT WORK FOR YOU KEEP A FALLBACK SYSTEM AT ALL TIME
</div>
### Installing it

In grub set the variable `init=/sbin/qbm` or on the kernel commandline during boot

**Distributed under the BSD license, no warrenty what so ever, be warned**
