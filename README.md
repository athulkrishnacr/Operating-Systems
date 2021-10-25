# Installing FreBSD and Ubuntu using VirtualBox
## FreeBSD

FreeBSD is a free and open-source Unix-like operating system based on Berkeley Software Distribution (BSD) Unix. It the most popular BSD-based operating system designed for stability and performance. FreeBSD comes as a complete operating system with its kernel, device drivers, shell tools and many system tools ready for use.

FreeBSD has seen a wide adoption by Internet Service Providers, students, researchers, computer professionals, and home users all over the world. There are over 20,000 packages ranging from databases, web servers, Developer tools, Desktop Applications , gaming, and business software available for easy installation.

FreeBSD's kernel provides support for some essential tasks such as managing processes, communication, booting and filesystems. FreeBSD has a monolithic kernel, with a modular design. Different parts of the kernel, such as drivers, are designed as modules. The user can load and unload these modules at any time. ULE is the default scheduler in FreeBSD since version 7.1, it supports SMP and SMT. The FreeBSD kernel has also a scalable event notification interface, named kqueue. It has been ported to other BSD-derivatives such as OpenBSD and NetBSD. Kernel threading was introduced in FreeBSD 5.0, using an M:N threading model. This model works well in theory, but it is hard to implement and few operating systems support it. Although FreeBSD's implementation of this model worked, it did not perform well, so from version 7.0 onward, FreeBSD started using a 1:1 threading model, called libthr.

FreeBSD uses tcsh(1) as the default root shell, and the Bourne shell-compatible sh(1) as the default user shell. sh(1) is very similar to Bash but with a much smaller feature-set. Generally shell scripts written for sh(1) will run in Bash, but the reverse is not always true.



### Steps
- Download FreeBSD disk iso image file based on your system architecture from [https://www.freebsd.org/](https://www.freebsd.org/).
- Open Oracle VirtualBox and select `New`.
![vm1](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(116).png)
- Give VM a name and choose OS type and version.
![vm2](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(120).png)
- Give the necessary RAM.
![vm1](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(121).png)
- Choose to create virtual hard disk.
![vm1](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(122).png)
- Choose hard disk file type
![vm1](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(123).png)
- Select Dynamic or fixed size storage type.
![vm1](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(124).png)
- Give atleast recommended disk space
![vm1](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(125).png)
- Now VM template is created and ready to start.
![vm1](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(126).png)
- Select the iso file.
![vm1](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(129).png)
- The installer will start. Hit okay.

- Follow these steps:
![vm1](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(131).png)

![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(132).png)

![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(133).png)

![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(134).png)

![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(135).png)

![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(136).png)

![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(137).png)

![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(138).png)

![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(139).png)

![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(140).png)

![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(141).png)

![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(142).png)

![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(143).png)

![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(144).png)

Installation is finished.

- Configure and setting up

![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(146).png)

![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(147).png)

![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(148).png)

![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(149).png)

![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(150).png)

![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(151).png)

![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(152).png)

![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(153).png)

![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(154).png)

![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(155).png)

![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(156).png)

![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(157).png)

![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(158).png)

![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(159).png)

![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(160).png)

- Set root password and add a guest user to the system.

![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(162).png)

![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(163).png)

![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(166).png)

![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(167).png)

![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(169).png)

![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(171).png)

- Now you can install any Desktop enviroments or window managers like GNOME or KDE Plasma 5 or XFCE. Here we are installing GNOME.
- Login in as root.

![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(201).png)

- Update the system
```bash
freebsd-update fetch
```
![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(160).png)

- Install the updates
```bash
freebsd-update install
```
![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(217).png)

- Install NANO command-line text editor. You can also use vi command-line editor.
```bash
pkg install nano
```
![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(218).png)

- Install and configure sudo
```bash
pkg install sudo
```

![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(220).png)

- edit sudoers file using `visudo` command.
```bash
visudo
```
![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(222).png)

- Once vi shows up, use your down arrow to navigate to the line that says root ALL=(ALL) ALL and add below the following:
```bash
<your username> ALL=(ALL) ALL
```
![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(223).png)

![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(224).png)

sudo is now installed
- Installing GNOME desktop environment
```bash
pkg install gnome-desktop gdm xorg gnome3
```
![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(225).png)

- Enable dbus, hal, mouse, gdm deaemons
```bash
nano /etc/rc.conf
```
![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(228).png)

Next, add the following lines in rc.config file:
```bash
gnome_enable=”YES”
moused_enable=”YES”
dbus_enable=”YES”
hald_enable=”YES”
gdm_enable=”YES”
```
![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(231).png)

- Mount /proc in fstab
```bash
nano /etc/fstab
```
![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(234).png)

Add the following line in fstab file:
```bash
proc /proc procfs rw 0 0
```
![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(237).png)

Save and close the fstab file.
- Boot into GNOME desktop
```bash
reboot
```

![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(243).png)

![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(244).png)

![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(245).png)

![v](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/Screenshot%20(246).png)

![GNOME](https://github.com/athulkrishnacr/Operating-Systems/blob/main/freebsd%20and%20ubuntu/WhatsApp%20Image%202021-10-25%20at%209.04.43%20PM.jpeg)

## Ubuntu

Ubuntu is a Linux distribution based on Debian and composed mostly of free and open-source software. Ubuntu is officially released in three editions: Desktop, Server, and Core for Internet of things devices and robots. All the editions can run on the computer alone, or in a virtual machine. Ubuntu is a popular operating system for cloud computing, with support for OpenStack. Ubuntu's default desktop has been GNOME, since version 17.10.

Ubuntu's default shell is Bash (like most other Linux distributions).

At the core of the Ubuntu operating system is the Linux kernel, which manages and controls the hardware resources like I/O (networking, storage, graphics and various user interface devices, etc.), memory and CPU for your device or computer.


- Select New in VirtualBox

![u1](https://www.freecodecamp.org/news/content/images/2019/11/start-1.png)

- Select the appropriate type

![u2](https://www.freecodecamp.org/news/content/images/2019/11/Screenshot--14-.png)

- Give the required RAM and Create a virtual hard disk

![u3](https://www.freecodecamp.org/news/content/images/2019/11/Screenshot--16-.png)

![u3](https://www.freecodecamp.org/news/content/images/2019/11/Screenshot--17--1.png)

- Allocate storage

![u4](https://www.freecodecamp.org/news/content/images/2019/11/Screenshot--18-.png)

- Now we have to set up iso file
- Select disk image and open it

![u3](https://www.freecodecamp.org/news/content/images/2019/11/Screenshot--23-.png)

![u3](https://www.freecodecamp.org/news/content/images/2019/11/Screenshot--25-.png)

- Press start to install

![u3](https://www.freecodecamp.org/news/content/images/2019/11/Screenshot--26-.png)

- Click install ubuntu

![u](https://www.freecodecamp.org/news/content/images/2019/11/Screenshot--27-.png)

- select keyboard layout

![u](https://www.freecodecamp.org/news/content/images/2019/11/Screenshot--29-.png)

- Select Normal installation

![u](https://www.freecodecamp.org/news/content/images/2019/11/Screenshot--30-.png)

- Select "Erase disk and install Ubuntu"

![u](https://www.freecodecamp.org/news/content/images/2019/11/Screenshot--31-.png)

- Click continue

![u](https://www.freecodecamp.org/news/content/images/2019/11/Screenshot--32-.png)

- Choose your location

![u](https://www.freecodecamp.org/news/content/images/2019/11/Screenshot--33-.png)

- Set up your profile

![u](https://www.freecodecamp.org/news/content/images/2019/11/Screenshot--34-.png)

- Installation started

![u](https://www.freecodecamp.org/news/content/images/2019/11/Screenshot--35-.png)

- After installation reboot and login.

![u](https://www.freecodecamp.org/news/content/images/2019/11/Screenshot--40-.png)

## What is Kernal and shell?

Kernel is central component of an operating system that manages operations of computer and hardware. It basically manages operations of memory and CPU time. Kernel loads first into memory when an operating system is loaded and remains into memory until operating system is shut down again. It is responsible for various tasks such as disk management, task management, and memory management. It decides which process should be allocated to processor to execute and which process should be kept in main memory to execute. It basically acts as an interface between user applications and hardware.

Shell is the interface to the operating system. It is the outermost layer of the operating system. Shells incorporate a programming language to control processes and files, as well as to start and control other programs.

## What is Operating System(OS)?

An Operating System (OS) is a software that acts as an interface between computer hardware components and the user. Every computer system must have at least one operating system to run other programs. Applications like Browsers, MS Office, Notepad Games, etc., need some environment to run and perform its tasks.
The OS helps you to communicate with the computer without knowing how to speak the computer’s language. It is not possible for the user to use any computer or mobile device without having an operating system.
