# bcmon2020
The modified bcmon from google code archive.

you might own a nexus 7 (model 2012), thanks to bcmon you are able to work with softwares like aireplay-ng etc... in other words you can crack wifi with the internal wifi card.

BUT you know that it works only for kitkat because the original bcmon app was compiled without pie (a safety) and so isn't allowed to run on new systems. It's either stick to kitkat just for that feature (but not being able to install awesome apps like termux) or forget about cracking wifi (without an external dongle).

I'm releasing this modified apk that will work with newer systems (up to android 6 included).

What I have done:
- 1 got the apk from google code (source is not available).
- 2 replaced the 17's byte from the non pie binaries (x02) with a pie flag (0x3) thanks to [this post](https://yurushao.info/tech/2016/03/14/Android-PIE.html)
- 3 signed the apk

That's it !  
Tested on a stock lollipop rom (nakasig-lmy47v) with:  
- [SuperSU-v2.82](https://download.chainfire.eu/1220/SuperSU/SR5-SuperSU-v2.82-SR5-20171001224502.zip?retrieve_file=1)   
- stericson busybox from the playstore, you don't need pro version, just use standard install in /system/xbin or /su/xbin. And **do not** install the busybox from the link below as it will break the system.  

Tested on Unlegacy Android marshmallow:  
- [SuperSU-v2.82](https://download.chainfire.eu/1220/SuperSU/SR5-SuperSU-v2.82-SR5-20171001224502.zip?retrieve_file=1)  
- [Busybox](https://forum.xda-developers.com/android/software-hacking/tool-flashable-busybox-v1-23-2-stericson-t3219431/)  
- boot.img that you will find in the releases, compiled from [nvidia kernel for tegra version 3.4, configured by binkybear](https://github.com/binkybear/android_kernel_asus_grouper-1). Note that if you unplug the headset's jack while a media is playing, the tablet needs to be reboot to regain the device. Also Facing suddent reboots when giving it a lot of work. Note that my device was old and dies shortly after so there might be no issues.  
