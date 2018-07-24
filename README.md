virgo
=====

win上的虚拟桌面软件，类似Win10的CTRL+ALT + →，但切换起来更好看，也适合Win7。    

|快捷键|说明|
|-|-|
| Win+Ctrl+F9,F10,F11        |  选择1，2，3桌面。 | 
| Win+Ctrl+Shift+F9,F10,F11  |  当前窗口移到1，2，3桌面。 | 
| Win+Ctrl+左右键             |  在1，2，3桌面里左右切换（与Win10的类拟） | 
| Win+Ctrl+Shift+Q            | 退出程序 | 


> 发现原来的快捷键冲突比较多，所有的快捷键都增加Win键。

----
the nerds can build it with
```
 git clone https://github.com/tea4go/virgo.git
 cd virgo
 make
```

If you do not have gcc/make installed you can change that doing following

1. go to http://msys2.github.io/ and install it according to the instructions there
2. open msys2 shell and install mingw-w64-i686-gcc and mingw-w64-i686-make using pacman
3. duplicate C:\msys32\mingw32\bin\mingw32-make.exe and name it make.exe
