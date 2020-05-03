# bcmon2020
The modified bcmon from google code

you might own a nexus 7 (model 2012) and have the possibility to get frame injection to work with software like aireplay-ng etc... BUT you know that it works only for kitkat because the original bcmon app was compiled without pie (a safety) and doesn't work on new system, so you'r like wondering if it's better to stick to kitkat just for that feature (but not being able to install awesome apps like termux) or forget about cracking wifi. Don't dwelve no more in sadness my friends, this apk I'm releasing is modified and will work with newer systems (tested with stock lollipop).

What I have done:
1 got the apk from google code (source is not available).
2 replaced the 17's byte from the non pie binaries (x02) with a pie flag (0x3) thanks to this thread:
https://yurushao.info/tech/2016/03/14/Android-PIE.html
3 signed the apk
That's it !!!!!!!!!

You'll need supersu and busybox.
Fill issues if you have ... issues, I will help because I have time to offer.
