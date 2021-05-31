# Reactos-4.15-inside-Ubuntu-20

Download ReactOS 4.15
(I TRIED 4.13 AND IT WOULD NOT WORK...)
https://iso.reactos.org/bootcd/reactos-bootcd-0.4.15-dev-2620-g5ce9e2e-x86-gcc-lin-dbg.7z

Find the 7.z file and extract it.

Open a terminal and insert the command for gnome-boxes
sudo apt --install-suggests --install-recommends install gnome-boxes

In the terminal, insert the command to open gnome-boxes
gnome-boxes
or find it in applications

Click on the + on the LEFT UPPER Corner!

Add a new Virtual Machine (BOTTOM MOST LINK)

Open the folder with the unzipped ReactOS file and use it

Click Customize

Change the memory settings to 256mb to 300mb
(Too much memory made my system crash)

The only thing to remember now is to not change the file system format to BTRFS.
Mine would not take it.

This installed fine on my Acer X501

We need Windows Drivers!!!

https://www.youtube.com/watch?v=1CQBQcZNaIs
The above link is not me.


