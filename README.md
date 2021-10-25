# Installing FreBSD and Ubuntu using VirtualBox
## FreeBSD
FreeBSD is a free and open-source Unix-like operating system based on Berkeley Software Distribution (BSD) Unix. It the most popular BSD-based operating system designed for stability and performance. FreeBSD comes as a complete operating system with its kernel, device drivers, shell tools and many system tools ready for use.

FreeBSD has seen a wide adoption by Internet Service Providers, students, researchers, computer professionals, and home users all over the world. There are over 20,000 packages ranging from databases, web servers, Developer tools, Desktop Applications , gaming, and business software available for easy installation.

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
- The installer will start. Hit enter key.
![vm1]()
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


- Set root password and add a guest user to the system.
![vm1]()
- Installation of FreeBSD is now complete
![vm1]()
- Now you can install any Desktop enviroments or window managers like GNOME or KDE5 Plasma or XfCE. Here we are installing GNOME.
![vm1]()
- Login in as root.
![vm1]()
- Update the system
```bash
freebsd-update fetch
```
![vm1]()
- Install the updates
```bash
freebsd-update install
```
![vm1]()
- Install NANO command-line text editor. You can also use vi command-line editor.
```bash
pkg install nano
```
![vm1]()
- Install and configure sudo
```bash
pkg install sudo
```
![vm1]()
- edit sudoers file using `visudo` command.
```bash
visduo
```
![vm1]()
- Once vi shows up, use your down arrow to navigate to the line that says root ALL=(ALL) ALL and add below the following:
```bash
<your username> ALL=(ALL) ALL
```
![vm1]()
sudo is now installed
- Installing GNOME desktop environment
```bash
pkg install gnome-desktop gdm xorg gnome3
```
![vm1]()
- Enable dbus, hal, mouse, gdm deaemons
```bash
nano /etc/rc.conf
```
![vm1]()
Next, add the following lines in rc.config file:
```bash
gnome_enable=”YES”
moused_enable=”YES”
dbus_enable=”YES”
hald_enable=”YES”
gdm_enable=”YES”
```
![vm1]()
- Mount /proc in fstab
```bash
nano /etc/fstab
```
![vm1]()
Add the following line in fstab file:
```bash
proc /proc procfs rw 0 0
```
![vm1]()
Save and close the fstab file.
- Boot into GNOME desktop
```bash
reboot
```
![vm1]()

## Ubuntu

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
