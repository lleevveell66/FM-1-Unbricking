# FM-1-Unbricking
Just a gentler guide for unbricking (soft and hard bricked) M-Vave FM-1 synths.

## What is this?
This will hopefully become an easier guide to unbricking both soft-bricked and hard-bricked Mvave FM-1 synths.  I happen to be pretty great at documentation.

## Firmware:
I have staged V15 and V16 versions of the FM-1 stock firmware on my website.  This comes with a very stern warning:

> [!CAUTION]
> **NEVER TRUST FIRMWARE PROVIDED BY ANYONE BUT THE VENDOR!**

But, for those who are going to ignore that, because MVave has not provided previous version links and this is your only choice... carry on.

Files:
* [V15](https://www.level6.art/downloads/free/FM-1/FM-1_V15.fwsc)
* [V16](https://www.level6.art/downloads/free/FM-1/FM-1_V16.fwsc)

When you download either, rename it to FM-1.fwsc to make things easier for other tools.

## Tools for Windows:
I am a 35+ year unix greybeard.  But, I still use the Windows platform for all multimedia/art and a quarter of my development.  So, I am doing this in Windows 10 Pro and will let you know how I have my environment set-up for this.

To match my environment, if you are new to all of this, download and install:
* [Git for Windows](https://gitforwindows.org/)
* [MSYS2](https://www.msys2.org/)
* Bring up a MING64 terminal and install python, wget, and git:
  ```
  pacman -S --noconfirm mingw-w64-x86_64-python wget git
  ```
  If that command does not work, you may have brought up the wrong terminal.  Simply hit WIN-r and paste "C:\msys64\mingw64" and hit enter to run the correct one.  You want to see "MINGW64" in your prompt, instead of "UCRT64".  Just my personal preference.
* Assuming you installed MSYS2 to the default C:\msys64\ directory, set up your shell environment to prefer the MINGW64 binaries over the rest when you enter your terminal, with:
  ```
  echo 'export PATH="/c/msys64/mingw64/bin:/c/msys64/usr/bin:$PATH"' >> ~/.bashrc
  source ~/.bashrc
  ```

You should now be able to easily "git clone" repos, wget firmware files, and run python scripts from your new unix-y terminal.    Enjoy!

If you find yourself *really* enjoying this sort of development environment and your new "linux" style shell in Windows, you can use pacman (the package manager) to search for packages you might like to install, then install them.  You might want to install gcc to compile C code.  Maybe you would like to install the lynx textual browser and hit an interesting gopher site?  Fun times.  Fun times.
```
$ pacman -Ss lynx
msys/lynx 2.9.3-1 [installed]
    A text browser for the World Wide Web
$ pacman -S --noconfirm lynx
$ lynx gopher://gopher.leper.org:7777/
```
Anyway...

## Soft vs. Hard Bricked:
More to come...

### Unbricking a soft-bricked FM-1:
More to come...

### Unbricking a hard-bricked FM-1:
More to come...

## Like My Work or Music?
You could always [Buy Me A Coffee](https://buymeacoffee.com/sixthlevel)   (:
