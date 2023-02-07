1. Command name and purpose:

user@user:~$ ls //shows the directories


Desktop    Downloads  Pictures  snap       Videos

Documents  Music      Public    Templates


************************************************************************
2. Command name and purpose: 

user@user:~$ cd Downloads //opens a directory

user@user:~/Downloads$ 


************************************************************************
3. Command name and purpose:  
user@user:~/Downloads$ man -k syslog //shows a list of man pages containing a string

rsyslog.conf (5)     - rsyslogd(8) configuration file

rsyslogd (8)         - reliable and extended syslogd

syslog (2)           - read and/or clear kernel message ring...

syslog (3)           - read and/or clear kernel message ring...

vsyslog (3)          - send messages to the system logger

************************************************************************
4. Command name and purpose: 

user@user:~/Downloads$ whatis route //see description of the manual page

tc-route (8)         - route traffic control filter
************************************************************************
5. Command name and purpose:

user@user:~/Downloads$ man rsyslogd //shows the manual page for a command

RSYSLOGD(8)      Linux System Administration      RSYSLOGD(8)



NAME

       rsyslogd - reliable and extended syslogd



SYNOPSIS

       rsyslogd  [  -d  ]  [ -D ] [ -f config file ] [ -i pid

       file ] [ -n ] [ -N level ] [ -o fullconf ] [ -C ] [ -v

       ]


DESCRIPTION
(a very long description was brough up so I did not want to copy and paste the whole thing)
(you have to type q to exit the manual page)

************************************************************************
6. Command name and purpose: 
user@user:~/Downloads$ cd ~ //takes you back to your home directory

user@user:~$ 

************************************************************************
7. Command name and purpose: 

user@user:~$ pwd //print working directory, shows the current directory

/home/user

************************************************************************
8. Command name and purpose: 

user@user:~$ cd .. //goes to the parent direcotory

user@user:/home$ 

************************************************************************
9. Command name and purpose:  
user@user:~$ ls -lh //shows the numbers (file sizes) in a more human readable format

total 36K

drwxr-xr-x 2 user user 4.0K Feb  1 12:49 Desktop

drwxr-xr-x 2 user user 4.0K Feb  1 12:49 Documents

drwxr-xr-x 2 user user 4.0K Feb  1 12:49 Downloads

drwxr-xr-x 2 user user 4.0K Feb  1 12:49 Music

drwxr-xr-x 2 user user 4.0K Feb  1 12:49 Pictures

drwxr-xr-x 2 user user 4.0K Feb  1 12:49 Public

drwx------ 4 user user 4.0K Feb  1 13:19 snap

drwxr-xr-x 2 user user 4.0K Feb  1 12:49 Templates

drwxr-xr-x 2 user user 4.0K Feb  1 12:49 Videos


************************************************************************
10. Command name and purpose: 

user@user:~$ mkdir Random //create a new directory called "Random"

user@user:~$ ls

Desktop    Downloads  Pictures  Random  Templates

Documents  Music      Public    snap    Videos



************************************************************************
11. Command name and purpose: 

user@user:~$ rmdir Random //remove the "Random" directory. Only works for empty directories

user@user:~$ ls

Desktop    Downloads  Pictures  snap       Videos

Documents  Music      Public    Templates



************************************************************************
12. Command name and purpose:

user@user:~/Documents$ cat file1 //shows the contents of a file

This is a random file //the contents of the file

************************************************************************
13. Command name and purpose: 

user@user:~/Documents$ file file1 //determines the file type

file1: ASCII text

************************************************************************
14. Command name and purpose: 

user@user:~/Documents$ ls

file1

user@user:~/Documents$ touch file2 //creates a new empty file

user@user:~/Documents$ ls

file1  file2

user@user:~/Documents$ 

************************************************************************
15. Command name and purpose: 

user@user:~/Documents$ ls

file1  file2

user@user:~/Documents$ rm file2 //permanently removing a file

user@user:~/Documents$ ls

file1

************************************************************************
16. Command name and purpose: 

user@user:~/Documents$ ls

file1

user@user:~/Documents$ cp file1 file1copy //copy file1 and name it file1copy

user@user:~/Documents$ ls

file1  file1copy

************************************************************************
17. Command name and purpose: 

user@user:~/Documents$ ls

file1  file1copy

user@user:~/Documents$ mv file1copy FILE1COPY //rename a file

user@user:~/Documents$ ls

file1  FILE1COPY
************************************************************************
18. Command name and purpose:  

user@user:~/Documents$ ls

file1  FILE1COPY  practice

user@user:~/Documents$ head practice //displays the first 10 lines of the file

line 1

line 2

line 3

line 4

line 5

line 6

line 7

line 8

line 9

line 10

************************************************************************
19. Command name and purpose: 

user@user:~/Documents$ ls

file1  FILE1COPY  practice

user@user:~/Documents$ tail practice //displays the last 10 lines of the file

line 12

line 13

line 14

line 15

line 16

line 17

line 18

line 19

line 20


************************************************************************
20. Command name and purpose: 

user@user:~/Documents$ cat file1 //old command, reading contents of file

This is a random file

user@user:~/Documents$ cat > file1 //NEW COMMAND: writing more flat text to the file

My name is Aubrie

I am writing more to the file

user@user:~/Documents$ cat file1

My name is Aubrie

I am writing more to the file

************************************************************************
21. Command name and purpose:  

user@user:~/Documents$ cat practice //OLD COMMAND

line 1

line 2

line 3

line 4

line 5

line 6

line 7

line 8

line 9

line 10

line 11

line 12

line 13

line 14

line 15

line 16

line 17

line 18

line 19

line 20


user@user:~/Documents$ tac practice //NEW COMMAND: read the file backwards


line 20

line 19

line 18

line 17

line 16

line 15

line 14

line 13

line 12

line 11

line 10

line 9

line 8

line 7

line 6

line 5

line 4

line 3

line 2

line 1

************************************************************************
22. Command name and purpose: 

user@user:~$ ls /  //everything on your Linux system is in the root directory. 
                   //this shows the root directory

bin    dev   lib    libx32      mnt   root  snap      sys  var

boot   etc   lib32  lost+found  opt   run   srv       tmp

cdrom  home  lib64  media       proc  sbin  swapfile  usr


************************************************************************
23. Command name and purpose: 
user@user:~$ ls /lib //shows shared libraries being used by /bin and /sbin binaries

apg

apparmor

apt

aspell

bfd-plugins

binfmt.d

bluetooth

brltty

cnf-update-db

command-not-found

compat-ld

console-setup

cpp

crda

cups

dbus-1.0

debug

dkms

dpkg

emacsen-common

environment.d

evolution-data-server

file

firewalld

firmware

gcc

girepository-1.0

gnome-session

gnome-settings-daemon-3.0

gnome-settings-daemon-42

gnome-shell

gnupg

gnupg2

gold-ld

groff

grub

grub-legacy

gvfs

hdparm

init

initramfs-tools

ispell

kernel

klibc

klibc-K8e6DOmVI9JpyGMLR7qNe5iZeBk.so

libreoffice

linux

linux-boot-probes

linux-sound-base

locale

lp_solve

lsb

man-db

memtest86+

mime

modprobe.d

modules

modules-load.d

netplan

networkd-dispatcher

NetworkManager

nvidia

openssh

openvpn

os-prober

os-probes

os-release

pam.d

pcmciautils

pkgconfig

pm-utils

policykit-1

polkit-1

pppd

pulse-15.99.1+dfsg1

python2.7

python3

python3.10

recovery-mode

rhythmbox

rsyslog

sasl2

shim

snapd

software-properties

speech-dispatcher-modules

ssl

sysctl.d

systemd

sysusers.d

tc

terminfo

thunderbird

thunderbird-addons

tmpfiles.d

ubiquity

ubuntu-advantage

ubuntu-release-upgrader

udev

udisks2

ufw

unity-settings-daemon-1.0

update-notifier

usrmerge

valgrind

X11

x86_64-linux-gnu

xorg

xserver-xorg-video-intel



************************************************************************
24. Command name and purpose:  
user@user:~$ cat /proc/interrupts //displays the interrupts

           CPU0       CPU1       CPU2       CPU3       

  0:         32          0          0          0   IO-APIC   2-edge      timer

  1:          0          0       2465          0   IO-APIC   1-edge      i8042

  8:          0          0          0          0   IO-APIC   8-edge      rtc0

  9:          0          0          0          0   IO-APIC   9-fasteoi   acpi

 12:          0      10042          0          0   IO-APIC  12-edge      i8042

 14:          0          0          0          0   IO-APIC  14-edge      ata_piix

 15:          0          0          0       5321   IO-APIC  15-edge      ata_piix

 18:          0      10550          0          0   IO-APIC  18-fasteoi   vmwgfx

 19:          0          0          0      61718   IO-APIC  19-fasteoi   enp0s3

 20:          0          0      23801          0   IO-APIC  20-fasteoi   vboxguest

 21:      13341          0      26555          0   IO-APIC  21-fasteoi   ahci[0000:00:0d.0], snd_intel8x0

 22:         26          0          0          0   IO-APIC  22-fasteoi   ohci_hcd:usb1

NMI:          0          0          0          0   Non-maskable interrupts

LOC:     179709     195244     193090     222035   Local timer interrupts

SPU:          0          0          0          0   Spurious interrupts

PMI:          0          0          0          0   Performance monitoring interrupts

IWI:          0          0          0          0   IRQ work interrupts

RTR:          0          0          0          0   APIC ICR read retries

RES:       1030       1618       1599       1370   Rescheduling interrupts

CAL:     122938     130818     115927     114205   Function call interrupts

TLB:       8481       8245       9164       9018   TLB shootdowns

TRM:          0          0          0          0   Thermal event interrupts

THR:          0          0          0          0   Threshold APIC interrupts

DFR:          0          0          0          0   Deferred Error APIC interrupts

MCE:          0          0          0          0   Machine check exceptions

MCP:         16         16         16         16   Machine check polls

ERR:          0

MIS:         36

PIN:          0          0          0          0   Posted-interrupt notification event

NPI:          0          0          0          0   Nested posted-interrupt event

PIW:          0          0          0          0   Posted-interrupt wakeup event


************************************************************************
25. Command name and purpose: 

user@user:~$ ls /var/log //shows the directory that serves as a central point to contain all log files

alternatives.log  dmesg.2.gz       openvpn

apt               dpkg.log         private

auth.log          faillog          speech-dispatcher

boot.log          fontconfig.log   syslog

bootstrap.log     gdm3             ubuntu-advantage.log

btmp              gpu-manager.log  ubuntu-advantage-timer.log

cups              hp               unattended-upgrades

dist-upgrade      installer        vboxadd-install.log

dmesg             journal          vboxadd-setup.log

dmesg.0           kern.log         wtmp

dmesg.1.gz        lastlog


************************************************************************
26. Command name and purpose: 

user@user:~user@user:~/Documents$ diff file1 file2 //show the difference between the two 	
1a2
> randm
3,5c4
< random
< random
< random

************************************************************************
27. Command name and purpose:

user@user:~/Documents$ ip addr //show the ip address of the computer
1: lo: <LOOPBACK,UP,LOWER_UP> mtu 65536 qdisc noqueue state UNKNOWN group default qlen 1000
    link/loopback 00:00:00:00:00:00 brd 00:00:00:00:00:00
    inet 127.0.0.1/8 scope host lo
       valid_lft forever preferred_lft forever
    inet6 ::1/128 scope host 
       valid_lft forever preferred_lft forever
2: enp0s3: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc fq_codel state UP group default qlen 1000
    link/ether 08:00:27:23:b8:df brd ff:ff:ff:ff:ff:ff
    inet 10.0.2.15/24 brd 10.0.2.255 scope global dynamic noprefixroute enp0s3
       valid_lft 83807sec preferred_lft 83807sec
    inet6 fe80::82de:47ae:3bf5:1c63/64 scope link noprefixroute 
       valid_lft forever preferred_lft forever

************************************************************************
28. Command name and purpose: 

user@user:~/Documents$ netstat -lt //display network connections/information
Active Internet connections (only servers)
Proto Recv-Q Send-Q Local Address           Foreign Address         State      
tcp        0      0 localhost:domain        0.0.0.0:*               LISTEN     
tcp        0      0 localhost:ipp           0.0.0.0:*               LISTEN     
tcp6       0      0 ip6-localhost:ipp       [::]:*                  LISTEN  

************************************************************************
29. Command name and purpose: 

user@user:~/Documents$ cal //show the calander
   February 2023      
Su Mo Tu We Th Fr Sa  
          1  2  3  4  
 5  6  7  8  9 10 11  
12 13 14 15 16 17 18  
19 20 21 22 23 24 25  
26 27 28

************************************************************************
30. Command name and purpose: 

user@user:~/Documents$ date //show the date
Mon Feb  6 09:50:05 PM EST 2023

************************************************************************
31. Command name and purpose:  

user@user:~/Documents$ dd if=file1 of=filepractice //copying the file 
0+1 records in
0+1 records out
44 bytes copied, 9.4349e-05 s, 466 kB/s
user@user:~/Documents$ ls
commands  file1  file2  filepractice

************************************************************************
32. Command name and purpose: 

user@user:~/Documents$ sudo fdisk -l //identify disks, their partitions and 	their capacity

Disk /dev/loop0: 4 KiB, 4096 bytes, 8 sectors
Units: sectors of 1 * 512 = 512 bytes
Sector size (logical/physical): 512 bytes / 512 bytes
I/O size (minimum/optimal): 512 bytes / 512 bytes


Disk /dev/loop1: 61.96 MiB, 64970752 bytes, 126896 sectors
Units: sectors of 1 * 512 = 512 bytes
Sector size (logical/physical): 512 bytes / 512 bytes
I/O size (minimum/optimal): 512 bytes / 512 bytes


Disk /dev/loop2: 163.29 MiB, 171225088 bytes, 334424 sectors
Units: sectors of 1 * 512 = 512 bytes
Sector size (logical/physical): 512 bytes / 512 bytes
I/O size (minimum/optimal): 512 bytes / 512 bytes


Disk /dev/loop3: 400.8 MiB, 420265984 bytes, 820832 sectors
Units: sectors of 1 * 512 = 512 bytes
Sector size (logical/physical): 512 bytes / 512 bytes
I/O size (minimum/optimal): 512 bytes / 512 bytes


Disk /dev/loop4: 91.69 MiB, 96141312 bytes, 187776 sectors
Units: sectors of 1 * 512 = 512 bytes
Sector size (logical/physical): 512 bytes / 512 bytes
I/O size (minimum/optimal): 512 bytes / 512 bytes


Disk /dev/loop5: 46.96 MiB, 49242112 bytes, 96176 sectors
Units: sectors of 1 * 512 = 512 bytes
Sector size (logical/physical): 512 bytes / 512 bytes
I/O size (minimum/optimal): 512 bytes / 512 bytes


Disk /dev/loop6: 284 KiB, 290816 bytes, 568 sectors
Units: sectors of 1 * 512 = 512 bytes
Sector size (logical/physical): 512 bytes / 512 bytes
I/O size (minimum/optimal): 512 bytes / 512 bytes


Disk /dev/loop7: 45.86 MiB, 48091136 bytes, 93928 sectors
Units: sectors of 1 * 512 = 512 bytes
Sector size (logical/physical): 512 bytes / 512 bytes
I/O size (minimum/optimal): 512 bytes / 512 bytes


Disk /dev/sda: 100 GiB, 107374182400 bytes, 209715200 sectors
Disk model: VBOX HARDDISK   
Units: sectors of 1 * 512 = 512 bytes
Sector size (logical/physical): 512 bytes / 512 bytes
I/O size (minimum/optimal): 512 bytes / 512 bytes
Disklabel type: gpt
Disk identifier: 493F58CC-D0AD-4C14-8F9F-07B95A3C1462

Device       Start       End   Sectors  Size Type
/dev/sda1     2048      4095      2048    1M BIOS boot
/dev/sda2     4096   1054719   1050624  513M EFI System
/dev/sda3  1054720 209713151 208658432 99.5G Linux filesystem

************************************************************************
33. Command name and purpose: 

user@user:~$ clear //this has no output because this command clears all the lines in the terminal

************************************************************************
34. Command name and purpose:  

user@user:~$ uptime //show the uptime
 21:59:15 up  1:01,  1 user,  load average: 0.04, 0.16, 0.13

************************************************************************
35. Command name and purpose: 

user@user:~$ df //show disk usage
Filesystem     1K-blocks     Used Available Use% Mounted on
tmpfs            1106284     1576   1104708   1% /run
/dev/sda3      102106072 11580160  85293068  12% /
tmpfs            5531420        0   5531420   0% /dev/shm
tmpfs               5120        4      5116   1% /run/lock
/dev/sda2         524252     6196    518056   2% /boot/efi
tmpfs            1106284     2492   1103792   1% /run/user/1000
/dev/sr0           62308    62308         0 100% /media/user/VBox_GAs_6.1.36

************************************************************************
36. Command name and purpose: 

user@user:~$ free //show memory and swap usage
               total        used        free      shared  buff/cache   available
Mem:        11062840      794304     8353912       41896     1914624     9948820
Swap:        2097148           0     2097148

************************************************************************
37. Command name and purpose: 

user@user:~$ ps //display current active processes
    PID TTY          TIME CMD
   5462 pts/0    00:00:00 bash
   5684 pts/0    00:00:00 ps

