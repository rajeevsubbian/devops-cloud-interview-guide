1. Quick Navigation commands - https://github.com/rajeevsubbian/ultimate-linux-guide/blob/main/05-vi-shortcuts/README.md
2. Book referred - https://dew1-share.percipio.com/cd/rSHnHT3cd 

# 3. Important directories

/: It is the root directory and everything that runs in your Linux system is below this directory.

/etc: This directory stores all the configuration files on Linux.

/var: This directory stores the log files and data of some services. For example, if you have a MySQL server installed in your system, you can find all the data stored inside /var/lib/mysql/data.

/lib: Here you will find the libraries of your system. We do not have to often access this directory, but it is an important one to know. For example, the kernel modules are stored in /lib/modules.

/bin: This directory stores the binaries. In other words, the programs are required for your Linux Words. For example, the command ls, it is found in this directory.

/usr: Here you can find some binaries, like the /bin. But the binaries installed here are not required for your system works. For example, /usr/bin/at, this binary allows you to schedule a task to run in your system, but you can live without that.

/boot: In this directory, you can find your kernel installed. My current version is: /boot/vmlinuz-4.15.0-76-generic.

/proc: This is the current process running. One fact about this directory is it only exists when your Linux is turned on. If you have a dual boot and you try to mount your Linux partition, you will be able to see all the directories, except the /proc, because it is your RAM content.

/opt: Usually, it becomes empty after your installation. But, when you compile a program, it is a good practice to put the binaries and the configuration files in this directory.

/sbin: This is exactly like the /bin, but the binaries here require administration permissions. For example, if you want to format a partition, you will call the command /sbin/fdisk. You cannot run this command as a common user.

/home: In this directory, you will find the home directory of all the common users. The only exception is the user root; its home directory can be found in /root.

/mnt: Here, you can use to mount network shares; your pendrive, SD card, and another kind of external volumes.

These are the most important directories you can find in your Linux system and they will be a part of your daily work.
