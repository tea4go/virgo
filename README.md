virgo
=====
win上的虚拟桌面软件，类似Win10的CTRL+ALT + →，但切换起来更好看，也适合Win7。    

因为原版的占用了LOL这种游戏的按键，所以相比原版改了按键（基于1.4.2），提供两个版本，[在Release处下载](https://github.com/wintercoder/virgo/releases)：  

1. F9...F11 为切换桌面，CTRL+F9...F11 为把当前窗口挪到对应桌面，而F12因为系统热键冲突就不改了  
2. ALT+F9...F12切换，CTRL+F9...F12挪动   


----- END，以下为原版说明 ----- 

Virtual Desktop Manager for Windows

[Download here](https://github.com/papplampe/virgo/releases/download/v.1.4.2/virgo.zip)

Features:
- resource friendly, exe is <10kb on disk and uses <1mb memory while running
- 4 virtual desktops (more if you change a constant and recompile the code)
- shows only a tray icon with the number of the desktop you are on

Hotkeys:

        ALT + 1..4             -> changes to desktop 1..4
        CTRL + 1..4            -> moves active window to desktop 1..4
        ALT + CTRL + SHIFT + Q -> exits the program
        ALT + CTRL + SHIFT + S -> starts/stops handling of other hotkeys

the nerds can build it with

        git clone https://github.com/papplampe/virgo.git
        cd virgo
        make

If you do not have gcc/make installed you can change that doing following

1. go to http://msys2.github.io/ and install it according to the instructions there
2. open msys2 shell and install mingw-w64-i686-gcc and mingw-w64-i686-make using pacman
3. duplicate C:\msys32\mingw32\bin\mingw32-make.exe and name it make.exe
