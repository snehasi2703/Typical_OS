# A Simple Os
A Simple OS
It is a very simple UNIX-based operating system in C++. The OS would be able to boot, start a user shell and be extensible. It would provide services such as memory management, process management and multitasking. To use these services this OS can be extended further with more features. Currently, the OS would load all modules and load successfully with a friendly message to user.

Summary
*Boot with Grub
*Memory management: physical and virtual
*Process management and multitasking
*Userland and syscalls
*Modular drivers
*Some basics modules: console, keyboard
*IDE Hard disks
*DOS Partitions
*EXT2 read-only filesystems
*Standard C library (libC)
*UNIX basic tools: sh, cat

Get inside the project source directory. (where vagrant file is present)

* Install, configure and run the box using vagrant. #vagrant up

* Connect and access the virtual box. #vagrant ssh

* Get inside the vagrant directory. cd /vagrant

* Build the OS. #make all

* Run the OS #make run

The OS will boot with the help of grub and 'qemu'.
