# Kali-Linux-Missing-Files
some missing files after the OS installation.
here is a guide to check if you can install wifi drivers for Kali-linux.

boot using the bootable pendrive and see if kali live usb can boot or not and when it does,see if you can connect to the internet using wifi,if so then you can most probably install and use kali without any issue.
reboot again> choose graphic installation and then start selecting language and region and ..
automatically kali finds drivers.then usually the first part that needs
to find wifi driver fails,dont waste time trying to fix this,keep on clicking next, the important part is where you want to partition the HDD.only use 1 partition and choose it manually to figure it out.I used 140gb HDD unallocated partition.I selected to do it manually,it created a 4gb and the rest of the140 gb (4gb for boot).
when finished.it was fine and worked properly.But then when you boot it will say the missing firmwares are <for example
regulator.db and regulatory.db.p7s which you have to copy to the /lib/firmware/
directory
copy the missing files to the desktop then open a terminal..
then ls>cd Download >~Download#cp <filename> <path>>
  
the site in which you can look for your missing drivers are mentioned below.
I hope this tutorial is useful for you!

these are basically known as the non-free firmwares or drivers that you PC/Laptop needed when installing Kali-Linux
you can find there here:

# 1)https://awesomedetect.com/how-to-provide-non-free-firmware-files-to-kali-linux-installer/
# 2)https://unix.stackexchange.com/questions/316920/how-do-i-install-non-free-firmware-wifi-driver-from-usb
