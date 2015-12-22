systemui-overlay-sample
=======================

change the homeButton PNG via systemui-overlay.apk


With this sample we replace only one PNG file for the systemUI's HomeButton with a gray one for portrait and landscape-mode!
<br>And we change statusbar-clockview-related colors! 

See the /res Folder and the AndroidManifest.xml (for the Target-Key-String)...

The PNG filename(s) have to match the original PNG-FileNames in /res/drawable-sw600dp-xhdpi/ 
of the original target.apk 'SystemUI.apk/res7drawable-sw600dp-xhdpi'


The Target_packageName in AndroidManifest.xml of the new overlay.apk has to match the android:packageName of the target.apk...

