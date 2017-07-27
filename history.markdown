### 2017.07.26
#### You should know that if you flash an opengapps pack into your Nubia phone with UI 5.0. Every application uses WebView will FC. How to deal? 
You should download the latest version of the Android WebView then use your TWRP recovery to move the Android WebView from /data/app to /system/app. Don't forget to mount /system! Then the issue will get fixed.