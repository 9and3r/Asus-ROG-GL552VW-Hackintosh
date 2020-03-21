# Installing
Guide used: 
- [https://internet-install.gitbook.io/macos-internet-install/](Install using recovery from internet)
- [https://github.com/corpnewt/gibMacOS](gibMacOS)

# Clover

Once the USB is ready use I used the [https://github.com/fidele007/Asus-ROG-GL552VW-Hackintosh/tree/catalina](Asus-ROG-GL552VW-Hackintosh) files to replace the ones in the USB. Two changes must be made:

- config_preinstall.plist should be used. Rename this file to config.plist and remove the other one
- Change the file in /CLOVER/kexts/Other/RealtekRTL8111.kext/Contents/Info.plist. Change on the final part "<string>Network-Root</string>" to <string>Network-Root</string> to enable Lan on installation. [https://www.reddit.com/r/hackintosh/comments/dgla2p/rtl8111_kexts_dont_seem_to_inject_el_capitan/](rtl8111_kexts_dont_seem_to_inject_el_capitan)
