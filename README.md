# CloneZilla

Clonezilla is based on DRBL, Partclone, and udpcast, allows you to do bare metal backup and recovery. Two types of Clonezilla are available:
 - Clonezilla live : Clonezilla live is suitable for single machine backup and restore.
 - Clonezilla SE (Server Edition) :  Clonezilla SE is for massive deployment, it can clone many (40 plus!) computers simultaneously.

Due to absence of the hardware, we've used Clonezilla live.

CloneZilla live can be downloaded from : http://clonezilla.org/downloads.php

Detailed documentation can be found here : http://clonezilla.org/clonezilla-live-doc.php



Steps:

- Download CloneZilla live and create bootable using tuxboot
 - Boot the machine via Clonezilla live


![alt tag](http://clonezilla.org/clonezilla-live/doc/01_Save_disk_image/images/ocs-01-bootmenu.png)

 - Here we choose 800x600 mode, after pressing Enter, you will see Debian Linux booting process

![alt tag](http://clonezilla.org/clonezilla-live/doc/01_Save_disk_image/images/ocs-02-booting.png)

 - Choose the language and then in the next option, choose this :
![alt tag](http://clonezilla.org/clonezilla-live/doc/01_Save_disk_image/images/ocs-04-keymap.png)

 - In the next option, choose this :
 ![alt tag](http://clonezilla.org/clonezilla-live/doc/01_Save_disk_image/images/ocs-05-start-clonezilla.png)
 -  Choose device-to-device
![alt tag](http://clonezilla.org/clonezilla-live/doc/03_Disk_to_disk_clone/images/ocs-05-2-device-device-clone.png)

 - In the next screen, choose disk_to_remote_disk
 - Choose HardDisk you want to clone
 - You can choose to skip checking/repairing source file system
 - Press "Enter" to start the source server.
 
You can follow the instructions on the screen on the target server and the cloning will start.



