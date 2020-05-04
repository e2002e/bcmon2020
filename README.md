# bcmon2020
The modified bcmon from google code archive.

you might own a nexus 7 (model 2012) and have the possibility to get frame injection to be able to work with softwares like aireplay-ng etc... 
BUT you know that it works only for kitkat because the original bcmon app was compiled without pie (a safety) and so isn't allowed to run on new systems, it's either stick to kitkat just for that feature (but not being able to install awesome apps like termux) or forget about cracking wifi.
Don't dwelve no more in sadness my friends, this apk I'm releasing is modified and will work with newer systems (tested with stock lollipop only).

What I have done:
- 1 got the apk from google code (source is not available).
- 2 replaced the 17's byte from the non pie binaries (x02) with a pie flag (0x3) thanks to this thread:
https://yurushao.info/tech/2016/03/14/Android-PIE.html
- 3 signed the apk

That's it !
Tested on a stock lolipop rom (nakasig-lmy47v) with:
- stericson busybox (from the playstore, if you get it from anywhere else it's a malware).
- SuperSU-v2.82 (be carefull with all the false links, as long as you'r on the domain chainfire.eu it is fine).

Let me know if you go about testing it with other superuser apps, busyboxes or android versions, so that I can update the readme.

#NOTE:
If you have problems with the app, install it with adb.


