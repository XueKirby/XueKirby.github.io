<head>
 <title>XueKirby's 每日一翻</title>
 <link href="/favicon.ico" type="image/x-icon" rel="shortcut icon" />
</head>
### 2017.07.28
#### Google assistant is a perfect intelligent voice assist. It can run on any devices running Android 7.0+. Yet many people may be enslaved to the new versions of Android that cannot use Xposed well. The way to solve it is to use Magisk modules or to edit the build.prop in /system. I will tell you how to install Magisk modules. First of all, you should download Magisk manager from XDA. Then you will be told to install the latest version of Magisk. After the installation, you should reboot. After that, open Magisk manager and open the drawer from the left side. You can see "Download" in it. Find the Google Assistant enabler and install it. After rebooting, you can use Google Assistant happily.

---

### 2017.07.27
#### Sometimes we may not use LTE in the phone uses a new custom ROM. The problem comes from the baseband. Nearly all the functions like SMS MMS and phone calls depend on the baseband. Unlike the official ROM, custom ROMs do NOT provide a baseband. Sometimes it will go wrong. You should flash a proper firmware by flashing a proper official ROM. Then type in *#*#4636#*#* and enter Phone information menu. The last thing is to set preferred network type to WCDMA preferred. Then this issue will be figured out.

---

### 2017.07.26
#### You should know that if you flash an opengapps pack into your Nubia phone with UI 5.0. Every application uses WebView will FC. How to deal? 
#### You should download the latest version of the Android WebView then use your TWRP recovery to move the Android WebView from /data/app to /system/app. Don't forget to mount /system! Then the issue will get fixed.