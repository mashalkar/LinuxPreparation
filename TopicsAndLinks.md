------------
# 1) Basics:
*Legacy BIOS vs UEFI, Partition table:GPT vs MBR, Boot Loaders: GRUB, GRUB2, LILO 
Booting process legacy vs uefi Initramfs, Intitramrd, vmlinuz runlevels, targets, sysvinit, systemd, process id 1, 
Anaconda, kickstart, cfengine, 
Boot troubelshooting, Installing grub, manual booting, RHEL 6vs7vs8,
Updating Kernel, Kernel panics, Package management, repositories,*

-----
LINKS:\
[Legacy BIOS vs UEFI](https://fossbytes.com/uefi-bios-gpt-mbr-whats-difference/)\
[MBR vs GPT partition table](https://www.mustbegeek.com/difference-between-mbr-and-gpt/)\
[GRUB vs GRUB2](https://ngelinux.com/difference-between-grub-0-97legacy-grub-and-grub-2-in-linux/) 
[more](https://linoxide.com/best-difference-between-linux-grub-and-grub2-bootloader)
[more](https://www.codementor.io/@packt/grub-and-grub2-qevq1yree)\
[Initrd and Initramfs](www.ngelinux.com/difference-between-initrd-and-initramfs-all-what-you-need-to-know/)\
[Complete boot process](https://docs.google.com/document/d/1rAFF2fKD-o5NiO4NlOSeqkMTvJ_wwwTe9IwZCwX11Rc/)
[more](https://www.technicalmint.com/linux/linux-boot-process-in-rhel7-rhel6/)\
[Post bootup](https://www.tecmint.com/linux-boot-process-and-manage-services/)\
[init vs systemd](https://www.tecmint.com/systemd-replaces-init-in-linux/)\
[rt-kernel](https://www.redhat.com/sysadmin/real-time-kernel)\
[kernel panic](https://www.redhat.com/sysadmin/linux-kernel-panic)\
[kernel upgrade manually](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/7/html/kernel_administration_guide/ch-manually_upgrading_the_kernel)\
[booting issue](https://www.tecmint.com/find-and-fix-linux-boot-issues/)\
[RHEL 6vs7vs8](https://www.2daygeek.com/comparison-difference-between-rhel-8-vs-rhel-7-vs-rhel-6/)

-----------
# 2) Shell:
*Types of shells, env_varibales, global/local scope, export command, profiles and bashrc files, standard streams, redirections, regexs, scripting, config files, cron, anacron,*

-----
LINKS:\
[shell, rc and profiles files, ](https://docs.google.com/document/d/1ZW2T2cFpxKz4YBpHALh-nLQHEmeRGsvNQcKuwIqg_XQ/edit?usp=sharing)\
[shell redirections](https://docs.google.com/document/d/1Q_zigrVXB4wiuUGfzP1W6dxwZ3yZ7FrbCNf7VNd25yM/)
[REGEX](https://docs.google.com/document/d/1_-NQtc0dj8vdOhLj-7dwJ99ip1I07Cxz0zoENCrJXtQ/edit?usp=sharing)
[Differnt types shells](https://www.edureka.co/blog/types-of-shells-in-linux/)\
[Special variables](https://www.tutorialspoint.com/unix/unix-special-variables.htm)\
[Environment variables](https://www.geeksforgeeks.org/environment-variables-in-linux-unix/)\
[bash scripting cheatsheet](https://docs.google.com/document/d/1gVn1Zpg0aCaW6825xnKbpFwNJ-eGd8U5njyL4SJxifM/edit?usp=sharing)\
[shell config files](https://landoflinux.com/linux_bash_configuration_files.html)\
[crontab](https://www.geeksforgeeks.org/crontab-in-linux-with-examples/)  [more](https://stackoverflow.com/questions/21789148/difference-between-cron-and-crontab)\
[anacron](https://www.tecmint.com/cron-vs-anacron-schedule-jobs-using-anacron-on-linux/)  [more](https://opensource.com/article/21/2/linux-automation)\


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


-----------------------------------------------
# 4) Files, filesystem, storage and permissions:
*File permissions, attributes-chattr/lsattr, umask, special permissions, sticky bits, umask, ACL's, Xfs, ext2/3/4, btrfs, inodes, hard/soft links, fdisk, parted, lvm, raid,  encrypted filesystem, Luks, DRBD, fstab, df ,du,swap, /proc filesys, multipath, device mapper, dmsetup, nfs, iscsi, backups and restorations*

------
LINKS:\
[File permissions](https://www.guru99.com/file-permissions.html)\
[File attributes](https://www.tecmint.com/chattr-command-examples/)\
[umask](https://www.cyberciti.biz/tips/understanding-linux-unix-umask-value-usage.html) [more](https://www.digitalocean.com/community/questions/what-is-umask-how-to-set-it-permanently-for-a-user)\
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


--------------
# 5) Security:
*Selinux, iptables, firewalld, polkit, ACL's, sudo, SSL/TLS, md5,sha, System hardening*

-----
LINKS:\
SELINUX [P1](https://www.digitalocean.com/community/tutorials/an-introduction-to-selinux-on-centos-7-part-1-basic-concepts), [P2](https://www.digitalocean.com/community/tutorials/an-introduction-to-selinux-on-centos-7-part-2-files-and-processes), [P3](https://www.digitalocean.com/community/tutorials/an-introduction-to-selinux-on-centos-7-part-3-users)\
[iptables](https://www.howtogeek.com/177621/the-beginners-guide-to-iptables-the-linux-firewall/), [1](https://www.redhat.com/sysadmin/iptables), [2](https://www.digitalocean.com/community/tutorials/a-deep-dive-into-iptables-and-netfilter-architecture)\
[firewalld](https://www.digitalocean.com/community/tutorials/how-to-set-up-a-firewall-using-firewalld-on-centos-8)\
[polkit](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/7/html/desktop_migration_and_administration_guide/policykit)\
[ACL's]-[Basic](https://www.geeksforgeeks.org/access-control-listsacl-linux/), [Detailed](https://www.tecmint.com/secure-files-using-acls-in-linux/)\
[SSL,TLS](https://www.ssl2buy.com/wiki/ssl-vs-tls)\
[Hardening](https://www.tecmint.com/linux-server-hardening-security-tips/)\
[md5,sha]()


------------
# 6) System admin tools/commands:
*Find, locate, grep, awk, sed, cut, wc, sort, tar, zip, bzip, gzip, zcat, lsof, curl, wget, dd, hexdump, nohup, screen, atime, mtime, ctime, ssh, strace*

----
LINKS\

----------------------
[Find 1](https://geekflare.com/linux-find-commands/), [find 2](https://linuxize.com/post/how-to-find-files-in-linux-using-the-command-line/)\
[locate](https://linuxize.com/post/locate-command-in-linux/)\
[grep](https://www.geeksforgeeks.org/grep-command-in-unixlinux/) \
[awk](https://www.geeksforgeeks.org/awk-command-unixlinux-examples/)\
[sed 1](https://www.geeksforgeeks.org/sed-command-in-linux-unix-with-examples/), [sed 2](https://www.geeksforgeeks.org/sed-command-linux-set-2/)\
[cut](https://www.geeksforgeeks.org/cut-command-linux-examples/) , [wc](https://www.geeksforgeeks.org/wc-command-linux-examples/)\
[sort](https://www.geeksforgeeks.org/sort-command-linuxunix-examples/), [uniq](https://www.geeksforgeeks.org/uniq-command-in-linux-with-examples/)\
[gzip vs bzip2](https://tukaani.org/lzma/benchmarks.html)
[tar, gzip](https://www.howtogeek.com/248780/how-to-compress-and-extract-files-using-the-tar-command-on-linux/)
[zcat](https://www.howtoforge.com/linux-zcat-command/)\
[lsof](https://geekflare.com/lsof-command-examples/)\
[wget](https://geekflare.com/wget-command-examples/)\
[dd](https://linoxide.com/linux-dd-command-create-1gb-file/)\
[hexdump](https://www.geeksforgeeks.org/hexdump-command-in-linux-with-examples/)\
[nohup](https://www.geeksforgeeks.org/nohup-command-in-linux-with-examples/)\
[screen vs nohup](https://unix.stackexchange.com/questions/24658/nohup-vs-screen)\
[atime,ctime,mtime](https://www.howtogeek.com/517098/linux-file-timestamps-explained-atime-mtime-and-ctime/)\
[strace 1](https://www.geeksforgeeks.org/strace-command-in-linux-with-examples/) [2](https://www.geeksforgeeks.org/strace-command-in-linux-with-examples/)\
[ssh](https://zah.uni-heidelberg.de/it-guide/ssh-tutorial-linux)


------
# 7) System logging: 
*Local logs, rsyslogs, remote/central logs, logratate, log-levels, journalctl,*

---
LINKS:\
[Linux logging 1](https://www.plesk.com/blog/featured/linux-logs-explained/)   [2](https://mytrashcode.com/linux-logging-guide)\
[syslog vs rsyslog vs syslog-ng](https://serverfault.com/questions/692309/what-is-the-difference-between-syslog-rsyslog-and-syslog-ng)\
[remote/centralised logging](https://www.thegeekdiary.com/configuring-remote-logging-using-rsyslog-in-centos-rhel/) [One more](https://www.tecmint.com/install-rsyslog-centralized-logging-in-centos-ubuntu/)\
[logrotate](https://www.redhat.com/sysadmin/setting-logrotate)\
[log level](https://linuxconfig.org/introduction-to-the-linux-kernel-log-levels)\
[journalctl](https://www.debugpoint.com/2020/12/systemd-journalctl/)\


------
# 8) User managemnt:
*user, group, password management, sudoer, LDAP, AD, kerberos auth,*

---
LINKS:\
[useradd](https://linuxize.com/post/how-to-create-users-in-linux-using-the-useradd-command/)   [groupadd](https://linuxize.com/post/how-to-create-groups-in-linux/)\
[chgrp](https://linuxize.com/post/chgrp-command-in-linux/)  [usermod](https://linuxize.com/post/usermod-command-in-linux/)\
[passwd file](https://linuxize.com/post/etc-passwd-file/)   [passwd command](https://www.redhat.com/sysadmin/linux-user-account-management)\
[getent](https://www.geeksforgeeks.org/getent-command-in-linux-with-examples/)\
[sudoers](https://medium.com/kernel-space/linux-fundamentals-a-to-z-of-a-sudoers-file-a5da99a30e7f)\
[restricting sudo](https://www.digitalocean.com/community/questions/mini-tutorial-restricting-sudo-users-to-only-a-handful-commands)\
[authentication protocols](https://www.geeksforgeeks.org/types-of-authentication-protocols/)\
[LDAP vs Kerb](https://www.geeksforgeeks.org/difference-between-ldap-and-kerberos/)\
[Kerberos](https://www.geeksforgeeks.org/kerberos/)\
[LDAP](https://www.geeksforgeeks.org/lightweight-directory-access-protocol-ldap/)\
[AD connection](https://www.redhat.com/sysadmin/linux-active-directory)


-----
# 9)Networking: 
*Configuring nic, ip command, setting route/gateway, adding dns entries, hosts file, hostname, teaming, bonding, bond modes, bridges\
OSI model, subnet calculation, TCP/UDP pros and cons, TCP handshake, TCP flags, MTU, MSS, tcp packet capture, Window size, sequence number, socket states, graceful/forceful diconnection, checksums, fragmentations\
Routing - Dynamic, static. NAT, subnetting, ICMP, ARP, Broadcast, multicast, unicast, OSPF, BGP\
Switching - VLAN, MAC table\
Troubleshooting - Slow/No network, routing, TCP connection, tools like ping, traceroute, MTR, IPref, netstat, wireshark, etc.

---
LINKS:\


----
# 10) Servers: 
*DNS, DHCP, HTTPD, Mysql, LoadBalancer, AD, LDAP, *

---
LINKS:\
[AD](https://www.geeksforgeeks.org/introduction-of-active-directory-domain-services/)\


-----
# 11) Performance issues and troubleshooting
*Disk, Process, Network, Web server, Memory,*\

---
LINKS:\
[Trooubleshooting 101](https://www.redhat.com/sysadmin/troubleshooting-system-performance)\
[Basic tools/commands](https://www.bogotobogo.com/DevOps/DevOps-Sys-Admin-Interview-Questions-Linux-Monitoring-System-Application-Performance-Tuning-Tools.php)



ROUGH use
-----



fuser  -  https://www.tecmint.com/learn-how-to-use-fuser-command-with-examples-in-linux/
strace - 
significance of /etc/groups /etc/passwd /etc/shadow files.
sudo, sudoer

Networking: https://www.redhat.com/sysadmin/7-great-network-commands

Performance: Benchmarking tools



Interview questions:
https://javarevisited.blogspot.com/2011/05/unix-command-interview-questions.html#axzz70Qbi7t7y
