# bitByteGo Timetable Admin

![bitByteGo](brand/bitbytego-logo-blue-transparent.png)

Official Windows installers and in-app update packages. Application source is maintained separately in a private repository.

## Download

[Download the latest Windows installer](https://github.com/adinarkar/bitbytego-desktop-releases/releases/latest/download/BitByteGo.TimetableAdmin-win-Setup.exe)

Windows 10/11, x64, with Microsoft Edge WebView2 Runtime. Python and Node are bundled or unnecessary on the user's PC.

## Upgrading

Users of 0.3.x need to install the updater-enabled edition once. Close the older edition first. Existing application data remains in `%LOCALAPPDATA%\bitByteGo\TimetableAdmin`.

Version 4.1.1 fixes Restart to update being blocked by ordinary background reads. Saves, calculations, and planning sync remain protected. If an older version's Restart button remains blocked, close it normally and run the latest installer once.

New releases appear with **Download now** and **Later**. After five days from publication, the next startup automatically downloads and installs the update before opening the workspace. A running workspace is not forcibly restarted. Offline or failed updates leave the current app usable and retry later. The timetable solver continues to run on the PC and remains usable offline.

## Appearance

Choose **Dark**, **Light**, or **System** in the sidebar or on the sign-in screen. Dark keeps the BBG blue background and white text. System follows Windows appearance changes. Your selection is saved across app launches.

Release assets include the installer, portable build, full/delta update packages, feeds and checksums. Review the accompanying `TERMS.txt` and `THIRD_PARTY_NOTICES.txt`. These installers are currently unsigned.

[All releases and release notes](https://github.com/adinarkar/bitbytego-desktop-releases/releases)
