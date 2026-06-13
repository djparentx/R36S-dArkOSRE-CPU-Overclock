This is a live patcher version of R36S DarkOS CPU Overclock by teacupx that can be run offline and on the device without need for a Windows PC. It creates backups of all files before over-writing. If your dtb file is named differently than in the DTB variable in the script change it to match your dtb name before running the script.

ex. DTB="rk3326-r36s-linux.dtb"

Change your overclock speed by editing /boot/boot.ini  (ie. max_cpufreq=1368)

Valid overclock speeds:
- 1368 Mhz (default)
- 1416 Mhz
- 1440 Mhz
- 1464 Mhz
- 1488 Mhz
- 1512 Mhz
- 1608 Mhz

All credit to teacupx for the overclocked kernel and opp table. This is merely an installer. See the original release for more information.

https://github.com/teacupx/overclock-r36s/releases
