1) Basics:
Legacy BIOS vs UEFI 
Partition table:GPT vs MBR
Boot Loaders: GRUB, GRUB2, LILO 
Booting process legacy vs uefi Initramfs, Intitramrd, vmlinuz runlevels, targets, sysvinit, systemd, process id 1, 
Anaconda, kickstart, cfengine, 
Boot troubelshooting, Installing grub, manual booting, 
Updating Kernel, Kernel panics Package management, repositories.

2) Shell:
Types of sheels, env_varibales, global variables, export command, profiles and bashrc files,
standard streams, redirections, regexs, scripting, config files, cron, anacron,

------------
# 3) Process:

### nice, renice, zombie, orphan, IPC's, system calls, process states, Exit code, kernel and user space, cache, buffer, Avg load, steal time, top, -namespaces, cgroups
-----
LINKS:\
[Process priority - nice - renice](https://askubuntu.com/questions/656771/process-niceness-vs-priority)\
[Zombie, Orphan process](https://stackoverflow.com/questions/20688982/zombie-process-vs-orphan-process)\
[IPC basic](https://opensource.com/article/19/4/interprocess-communication-linux-storage)\
[IPC basics2](https://opensource.com/article/19/4/interprocess-communication-linux-networking)\
[system calls vs interupts](https://pediaa.com/what-is-the-difference-between-system-call-and-interrupt/)\
[sockets](https://beej.us/guide/bgnet/html/#what-is-a-socket)\
[Best read for IPC](https://beej.us/guide/bgipc/html/single/bgipc.html)\
[Process, states, signals](https://www.bogotobogo.com/Linux/linux_process_and_signals.php)\
[Process signals](https://www.tutorialspoint.com/unix/unix-signals-traps.htm)\
[exit code](https://www.nitendratech.com/linux/exit-codes-linux/)\
[Kernel and user space](https://unix.stackexchange.com/questions/87625/what-is-difference-between-user-space-and-kernel-space)\
[buffer cache](https://www.glassdoor.co.in/Interview/Cache-vs-buffer-QTN_3090711.htm)\
[clear cache](https://www.tecmint.com/clear-ram-memory-cache-buffer-and-swap-space-on-linux/)\
[top command](https://www.howtogeek.com/668986/how-to-use-the-linux-top-command-and-understand-its-output/)\
[Top command memory usage](https://unix.stackexchange.com/questions/289435/differences-and-relations-between-virt-and-used-in-output-of-top)\
[steal time](https://scoutapm.com/blog/understanding-cpu-steal-time-when-should-you-be-worried)\
[cgroups and namespaces](https://stackoverflow.com/questions/34820558/difference-between-cgroups-and-namespaces)\

----------------------------------------------------------------------------------------------------------------

# 4) Files, filesystem, storage and permissions:

### File permissions, attributes-chattr/lsattr, umask, special permissions, sticky bits, umask, ACL's, Xfs, ext2/3/4, btrfs, inodes, hard/soft links, fdisk, parted, lvm, raid, benchmarking tools, encrypted filesystem, Luks, DRBD, fstab, df ,du,swap, /proc filesys, multipath, device mapper, dmsetup, nfs, iscsi,
backups and restorations swap
------
LINKS:\
[File permissions](https://www.guru99.com/file-permissions.html)\
[File attributes](https://www.tecmint.com/chattr-command-examples/)\
[umask](https://www.cyberciti.biz/tips/understanding-linux-unix-umask-value-usage.html)\
[special perms suid,sgid,sticky bits](https://www.thegeekdiary.com/linux-interview-questions-special-permissions-suid-sgid-and-sticky-bit/)\
[ACL's](https://www.geeksforgeeks.org/access-control-listsacl-linux/)\
[ext/btrfs/xfs](https://www.howtogeek.com/howto/33552/htg-explains-which-linux-file-system-should-you-choose/)\
[ext2,ext3,ext4](https://kerneltalks.com/disk-management/difference-between-ext2-ext3-and-ext4/)\
[hard link](https://www.redhat.com/sysadmin/inodes-linux-filesystem)
[hard link/soft link](https://techdifferences.com/difference-between-hard-link-and-soft-link.html)\
[inodes](https://www.javatpoint.com/linux-inodes)




--------
fuser  -  https://www.tecmint.com/learn-how-to-use-fuser-command-with-examples-in-linux/
strace - 
significance of /etc/groups /etc/passwd /etc/shadow files.
sudo, sudoer
