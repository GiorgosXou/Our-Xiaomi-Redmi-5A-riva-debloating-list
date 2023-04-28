# Intro
A *["Xiaomi Redmi 5A (riva)"](https://www.gsmarena.com/xiaomi_redmi_5a-8898.php) (Excessively tested)* debloating list for use within the [Hexapterygon-tool](https://github.com/GiorgosXou/hexapterygon) *(Disclaimer: I am not responsible for google play apps that may not work after :P)*

# 💥 Results

[Here](https://odysee.com/hexapterygon:9) you can see a brief demonstration of how this device performs right now under a lot of presure

# ⚙️ Configure 
Before running `hexapterygon` make sure you :
- Disabled `find device` Under `Passwords & Security > Privacy > Device admin apps`
- Under `Developer options`:
- - Enabled `USB debugging`
- - Enabled `USB debugging (Security settings)` 
- - Enabled `Install via USB`


# 🔍 Research
***⚠️ Disclaimer:*** [This is not yet fully documented, please refer to the actuall list for more informations](https://github.com/GiorgosXou/Our-Xiaomi-Redmi-5A-riva-debloating-list/blob/main/devices/Xiaomi%20Redmi%205A%20riva.txt). Don't trust everything listed bellow, things have been listed under huge forces of pressure of limited free time, based on my grouped browser-tabs and additional notes.

|App Name |Package Name |Additional Context & references|
|---|---|---|
||com.miui.securitycenter|[🔍](https://forum.xda-developers.com/t/can-miui-security-center-be-removed.3897111/)|
||com.miui.guardprovider|[🦠](https://research.checkpoint.com/2019/vulnerability-in-xiaomi-pre-installed-security-app/)|
||com.miui.powerkeeper|[🦠](https://forum.xda-developers.com/t/psa-com-miui-powerkeeper-acts-like-a-malware-remove-it-trough-adb-for-increased-performance.4514455/)|
|Xiaomi MIUI Forum|com.miui.enbbs|[🛒](https://www.apkmirror.com/apk/xiaomi-inc-2/xiaomi-miui-forum/xiaomi-miui-forum-2-0-3-release/xiaomi-miui-forum-2-0-3-android-apk-download/)|
|MIUI Daemon|com.miui.daemon|[🔍](https://xiaomiui.net/what-is-the-miui-daemon-app-on-xiaomi-devices-1085/)|
||com.xiaomi.finddevice|[🔍](https://forum.xda-developers.com/t/anybody-knows-how-to-disable-finddevice.3322341/#post-87580581)|
|GetApps|com.xiaomi.mipicks|[🛒](https://apkcombo.com/getapps/com.xiaomi.mipicks/)|
|Joyose|com.xiaomi.joyose|[🔍](https://xiaomiui.net/what-is-the-joyose-app-on-xiaomi-phones-14625/)|
|MiWebView|com.mi.webkit.core|[🛒](https://www.apkmirror.com/apk/xiaomi-inc/miwebview/miwebview-1-41_fallback-release/miwebview-1-41_fallback-android-apk-download/)|
|Mi Pay|com.mipay.wallet.id|[🛒](https://www.apkmirror.com/apk/xiaomi-miui/mi-pay-2/mi-pay-2-0-0-3-release/mi-pay-0-0-3-android-apk-download/)|
||org.codeaurora.ims|[3](https://www.reddit.com/r/Xiaomi/comments/jyps2q/orgcodeauroraims/), [2](https://www.reddit.com/r/OnePlus8T/comments/miiitd/what_is_that_orgcodeauroraims_if_anybody_knows/), [1](https://www.reddit.com/r/GooglePixel/comments/tde8mt/orgcodeauroraims_causing_several_issues/)|
||com.android.systemui|[1](https://stackoverflow.com/questions/29229474/is-it-safe-to-disable-com-android-systemui)|
||com.android.updater|[1](https://forum.xda-developers.com/t/do-not-disable-com-android-updater.4084635/)|
||com.qualcomm.qcrilmsgtunnel |[🔍]( https://www.reddit.com/r/Nexus5/comments/1r1em0/anyone_know_what_comqualcommqcrilmsgtunnel_is/ )|
||com.google.android.feedback|[🔍](https://stackoverflow.com/questions/10812432/how-to-use-send-feeback-feedbackactivity-in-android)|
||com.android.providers.media|[1](https://forum.xda-developers.com/t/q-com-android-providers-media-what-is-this-xd.1336239/)|
|Google Drive|com.google.android.apps.docs|[🛒](https://play.google.com/store/apps/details?id=com.google.android.apps.docs)|
|under construction 🛠️🏗️|under construction 🛠️🏗️|under construction 🛠️🏗️|

##


**🔗 Links related to:**
- ***ADB:***
- - ***Python Libraries:***
- - - [pure-python-adb *(Currently using)*](https://github.com/Swind/pure-python-adb)
- - - [adbutils](https://github.com/openatx/adbutils)
- - - [adb_shell](https://github.com/JeffLIrion/adb_shell)
- - - [python-adb](https://github.com/google/python-adb)
- - ***Questions:***
- - - [Get application version name using adb](https://stackoverflow.com/questions/11942762/get-application-version-name-using-adb)
- - - [Change system app permissions through ADB](https://android.stackexchange.com/questions/136698/change-system-app-permissions-through-adb)
- - - [How do I get an apk file from an Android device?](https://stackoverflow.com/questions/4032960/how-do-i-get-an-apk-file-from-an-android-device/18003462#18003462)
- ***XDA:***
- - ✨ [Uninstall bloatwares \[No root\]](https://forum.xda-developers.com/t/uninstall-bloatwares-no-root.4321387/)
- - ***Random:***
- - - [How to deactivate RCS service / Rich Communication on XZ1 compact?](https://forum.xda-developers.com/t/how-to-deactivate-rcs-service-rich-communication-on-xz1-compact.3730605/#post-75164780)
- - - [Packages which are safe to remove and a few problems.](https://forum.xda-developers.com/t/packages-which-are-safe-to-remove-and-a-few-problems.4006171/)
- - - [Uninstall bloatwares No root](https://forum.xda-developers.com/t/uninstall-bloatwares-no-root.4321387/)
- - - [Question Debloating Mi 11](https://forum.xda-developers.com/t/debloating-mi-11.4242883/)
- - - [Other](https://forum.xda-developers.com/t/delete-this.4203903/page-2)
- ***MIUI:***
- - ✨ [Removing all unnecessary bloatware from Xiaomi MIUI 11/12 (Android 9/10) without root](https://selivan.github.io/2020/02/25/removing-bloatware-from-xiaomi-miui-android.html)
- - ✨ [MIUI 13 System Apps](https://gist.github.com/mcxiaoke/0a4c639d04e94c45eb6c787c0f98940a) <sup>[backup](https://gist.github.com/GiorgosXou/9b5efb522be1a3a398b28a416a522c8b)</sup>
- - [\[ADB DEBLOAT\] MIUI 12.0.8 List](https://forum.xda-developers.com/t/adb-debloat-miui-12-0-8-list.4160091/)
- - [Debloating MIUI without Root Access (Manual Method)](https://forum.xda-developers.com/t/debloating-miui-without-root-access-manual-method.4149707/)
- - [Xiaomi Bloatware List (Safe to Remove) on MIUI 14/13/12](https://technastic.com/xiaomi-bloatware-list-miui/)
- ***Exploits:***
- - ***Potential:***
- - - [CVE-2019-2215 0day local Android privilege escalation exploit](https://forum.xda-developers.com/t/cve-2019-2215-0day-local-android-privilege-escalation-exploit.3981873/)
- - ***Rooting:***
- - - ***Potential:***
- - - - ["Root" via dirtyc0w privilege escalation exploit (automation script) / Android (32 bit)](https://gist.github.com/Arinerron/0e99d69d70a778ca13a0087fa6fdfd80)
- - - - [CVE-2016-5195 (dirty cow/dirtycow/dirtyc0w) proof of concept for Android](https://github.com/timwr/CVE-2016-5195)
- - - - [VIKIROOT - CVE-2016-5195 (Dirty COW) PoC for Android 6.0.1 Marshmallow](https://github.com/hyln9/VIKIROOT)
- ***Redmi 5A (exclusively):***
- - [\[GUIDE\]\[Newbie friendly\] ALL IN ONE Bypass bootloader lock guide of Redmi 5A](https://forum.xda-developers.com/t/guide-newbie-friendly-all-in-one-bypass-bootloader-lock-guide-of-redmi-5a.3974581/#post-80371153)
- - [\[Ultimate Guide\]\[Riva\] Unlock, Root, TWRP Guide for Redmi 5A [6/3/2018]](https://forum.xda-developers.com/t/ultimate-guide-riva-unlock-root-twrp-guide-for-redmi-5a-6-3-2018.3759470/)
- ***Lists:***
- [Xiaomi Super bloatware List 2020]( https://lucacesarano.medium.com/xiaomi-super-bloatware-list-2020-db38ace9e9e1 ) *(Additional context)*






<!-- TODO: bromite - setup coockies shazam photopea-->
