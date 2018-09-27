AutoHotkey mouse scripts
========================= 
by Joan Alba Maldonado (joanalbamaldonadoNO_SPAM_PLEASE AT gmail DOT com, without NO_SPAM_PLEASE)


## Description

Simple [AutoHotkey](https://autohotkey.com/ "AutoHotkey web site") scripts that will perform some actions by using the mouse.

I made these scripts for myself to be able to play some games in a tablet which lacks of a physical keyboard but has a mouse attached. This way I can exit the games, show their menus, show an on-screen keyboard (which does not work well with some games when they are running in full-screen mode, sadly), etc. by just using the mouse.

Hopefully, they could also be useful for someone else so I decided to share them.

They were tested on both 32 and 64-bit version of Microsoft Windows 10 (tablet and desktop) as well as on 32-bit versions of Microsoft Windows XP (with Service Pack 1) and Microsoft Windows 7. If, after trying a binariy (32-bit version and also 64-bit versions if any), it does not work on your Windows version then you can try to compile it from the source code provided. Please, have in mind that not all Windows versions have "tabtip.exe" or "osk.exe" files.


## Included scripts

**pressEsc_32** - It will press the "ESC" (_ESCAPE_) key when the mouse wheel button (the middle button) is pressed. Compiled for 32-bit but it should also run on 64-bit versions of Microsoft Windows.

**pressF5_32** - It will press the "F5" key when the mouse wheel button (the middle button) is pressed. Compiled for 32-bit but it should also run on 64-bit versions of Microsoft Windows.

**pressF10_32** - It will press the "F10" key when the mouse wheel button (the middle button) is pressed. Compiled for 32-bit but it should also run on 64-bit versions of Microsoft Windows.

**showOSK_32** - If available in the operating system, it will show the "OSK" (_osk.exe_) which belongs to the "On Screen Keyboard" ("floating" around the screen, as an independent window) when the mouse wheel button (the middle button) is pressed. Compiled for 32-bit.

**showOSK_64** - The same as "showOSK_32" but for 64-bit versions of Microsoft Windows. Use it in the case that you get [an error](https://autohotkey.com/board/topic/119602-the-system-cannot-find-the-file-specified/ "The system cannot find the file specified") using the "showOSK_32" version.

**showTabTip_32** - If available in the operating system, it will show the "TabTip" (_tabtip.exe_) which also belongs to an on-screen keyboad (different from the "osk.exe" one) when the mouse wheel button (the middle button) is pressed. Compiled for 32-bit.

**showTabTip_64** - The same as "showTabTip_32" but for 64-bit versions of Microsoft Windows. Use it in the case that you get [an error](https://autohotkey.com/board/topic/119602-the-system-cannot-find-the-file-specified/ "The system cannot find the file specified") using the "showTabTip_32" version.


## How to run

To use the already-compiled binaries, just run them as any other normal program. While they are running, an icon will be shown in the taskbar.

Note that, if desired, more than one script can be run at the same time to be combined.


## Compile from the source code

Apart from the binaries for Microsoft Windows, the source code is included so they can be easily modified to edit the actions performed, enhance features, etc.

To compile from the source code, the [AutoHotkey](https://autohotkey.com/ "AutoHotkey web site") software will be needed.