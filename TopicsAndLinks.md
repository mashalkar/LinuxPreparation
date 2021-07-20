------------
# 1) Basics:
*Legacy BIOS vs UEFI, Partition table:GPT vs MBR, Boot Loaders: GRUB, GRUB2, LILO 
Booting process legacy vs uefi Initramfs, Intitramrd, vmlinuz runlevels, targets, sysvinit, systemd, process id 1, 
Anaconda, kickstart, cfengine, 
Boot troubelshooting, Installing grub, manual booting, 
Updating Kernel, Kernel panics Package management, repositories.*

-----
LINKS:\
[Legacy BIOS vs UEFI](https://fossbytes.com/uefi-bios-gpt-mbr-whats-difference/)\
[MBR vs GPT partition table](https://www.mustbegeek.com/difference-between-mbr-and-gpt/)\
[more](https://docs.google.com/document/d/1GJTPKkasOxuShUwi3VuJ_Wjpxf5WjLLfcxv5Xt9LWOs/edit)\
[GRUB vs GRUB2](https://ngelinux.com/difference-between-grub-0-97legacy-grub-and-grub-2-in-linux/)  
[more](https://linoxide.com/best-difference-between-linux-grub-and-grub2-bootloader)
[more](https://www.codementor.io/@packt/grub-and-grub2-qevq1yree)\
[Initrd and Initramfs](www.ngelinux.com/difference-between-initrd-and-initramfs-all-what-you-need-to-know/)\
[Complete boot process](https://docs.google.com/document/d/1rAFF2fKD-o5NiO4NlOSeqkMTvJ_wwwTe9IwZCwX11Rc/)

-----------
# 2) Shell:
*Types of sheels, env_varibales, global variables, export command, profiles and bashrc files, standard streams, redirections, regexs, scripting, config files, cron, anacron,*

-----
LINKS:\
[Differnt types shells](https://www.edureka.co/blog/types-of-shells-in-linux/)\
[Special variables](https://www.tutorialspoint.com/unix/unix-special-variables.htm)

------------
# 3) Process:
*nice, renice, zombie, orphan, IPC's, system calls, process states, Exit code, kernel and user space, cache, buffer, Avg load, steal time, top, -namespaces, cgroups*

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
*File permissions, attributes-chattr/lsattr, umask, special permissions, sticky bits, umask, ACL's, Xfs, ext2/3/4, btrfs, inodes, hard/soft links, fdisk, parted, lvm, raid,  encrypted filesystem, Luks, DRBD, fstab, df ,du,swap, /proc filesys, multipath, device mapper, dmsetup, nfs, iscsi, backups and restorations

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
[inodes](https://www.javatpoint.com/linux-inodes)\
[Create partition using fdisk](https://www.tecmint.com/fdisk-commands-to-manage-linux-disk-partitions/)\
[parted vs fdisk](https://unix.stackexchange.com/questions/104238/fdisk-vs-parted)\
[LVM-redhat](https://www.redhat.com/sysadmin/lvm-vs-partitioning)\
[LVM-thegeekdiary](https://www.thegeekdiary.com/redhat-centos-a-beginners-guide-to-lvm-logical-volume-manager/)\
[RAID](https://www.wisdomjobs.com/e-university/raid-interview-questions.html)\
[Encrypted partition](https://www.redhat.com/sysadmin/encrypt-single-filesystem)\
[LUKS](https://www.redhat.com/sysadmin/disk-encryption-luks)\
[DRBD](https://www.tecmint.com/setup-drbd-storage-replication-on-centos-7/)\
[fstab](https://www.linuxgurus.in/linux-etc-fstab-file/)\
[df command](https://www.redhat.com/sysadmin/four-tips-df)\
[du vs df](https://www.redhat.com/sysadmin/du-vs-df) [One more](https://unix.stackexchange.com/questions/41863/how-to-remember-the-difference-between-du-and-df)\
[du](https://www.redhat.com/sysadmin/du-command-options)\
[swap](https://www.thegeekdiary.com/the-ultimate-linux-interview-questions-swap/)\
[swapiness](https://www.redhat.com/sysadmin/clear-swap-linux)\
[/proc](https://www.redhat.com/sysadmin/linux-proc-filesystem)  [more /proc](https://www.redhat.com/sysadmin/important-proc-files)\
[multipath](https://www.thegeekdiary.com/understanding-linux-multipath-using-dm-multipath/)\
[device mapper](https://en.wikipedia.org/wiki/Device_mapper)

--------

# 5) Security:
*Selinux, iptables, firewalld, polkit, ACL's, SSL/TLS md5,sha, System hardening

-----
LINKS:\
SELINUX [P1](https://www.digitalocean.com/community/tutorials/an-introduction-to-selinux-on-centos-7-part-1-basic-concepts), [P2](https://www.digitalocean.com/community/tutorials/an-introduction-to-selinux-on-centos-7-part-2-files-and-processes), [P3](https://www.digitalocean.com/community/tutorials/an-introduction-to-selinux-on-centos-7-part-3-users)\
[iptables](https://www.howtogeek.com/177621/the-beginners-guide-to-iptables-the-linux-firewall/), [1](https://www.redhat.com/sysadmin/iptables), [2](https://www.digitalocean.com/community/tutorials/a-deep-dive-into-iptables-and-netfilter-architecture)\
[firewalld](https://www.digitalocean.com/community/tutorials/how-to-set-up-a-firewall-using-firewalld-on-centos-8)\
[polkit]()

------------
# 6) System admin tools/commands:
*Find, locate, Grep, Awk, sed, cut,wc,sort tar,zip,bzip,gzip,zcat lsof, curl, wget dd,hexdump, nohup,screen, atime,mtime,ctime ssh, top, strace

------
# 7) System logging: 
*Local logs, rsyslogs, remote logs, logratate, log-levels,

------
# 8) User managemnt:
*user, group, password management, LDAP, AD, kerberos auth,

-----
# 9) Linux networking: 
*Configuring nic, ip command, setting route/gateway, adding dns entries, hosts file, hostname, teaming, bonding, bond modes, bridges,

----
# 10) Servers: 
*DNS, DHCP, HTTPD, Mysql, LoadBalancer,

-----
# 11) Performance issues: 
*Disk, Process, Network, Web server, Memory,




-----

fuser  -  https://www.tecmint.com/learn-how-to-use-fuser-command-with-examples-in-linux/
strace - 
significance of /etc/groups /etc/passwd /etc/shadow files.
sudo, sudoer

Networking: https://www.redhat.com/sysadmin/7-great-network-commands

Performance: Benchmarking tools


Interview questions:
https://javarevisited.blogspot.com/2011/05/unix-command-interview-questions.html#axzz70Qbi7t7y
