# CorsairCommanderProControl for Mac
This project is on hold, as the Corsair Commander Pro is identified as UPS in MacOS, which results in a segmentation fault on the Hackintosh installation. Only solution: disable the USB of the Corsair Commander Pro. But if it's disabled, it cant be controlled anymore.
  
  
It is still possible to use this, as OSX will boot with the Commander Pro installed AFTER the installation, but every OS install will hang. I will not give any support or help with the code, as i wont use it.
Tutorial:
remount local drive to uw `mount -uw /`
move /usr/libexec/ioupsd to a safe place  
move noups from this repository to /usr/libexec/ioupsd and make it executable  
install hidapi from brew `brew install hidapi`  
compile script
