# Knowledge-Base

Ubuntu - Reset Root Password
1. [Login Screen] Reboot holding the shift key
2. [Grub] Choose "Advanced options for Ubuntu"
3. Choose the Ubuntu recover mode record with the latest version
4. [Recovery Menu] Choose "root" to enter root shell and press Enter until you see command prompt
5. [root Shell prompt] Enter the following commands:
5.1 mount -n -o remount,rw /
5.2 passwd <user> 
  5.2.1 [New password prompt] <new pass>
5.3 reboot
