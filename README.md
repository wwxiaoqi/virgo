virgo
=====
Virtual Desktop Manager for Windows

> English | [中文](README-CN.md)

### Features:
- resource friendly, exe is <10kb on disk and uses <1mb memory while running
- 4 virtual desktops (more if you change a constant and recompile the code)
- shows only a tray icon with the number of the desktop you are on

### Hotkeys:

| shortcut key           | introduce                                   |
| ---------------------- | ------------------------------------------- |
| ALT + 1..4             | changes to desktop 1..4                     |
| CTRL + 1..4            | moves active window to desktop 1..4         |
| ALT + CTRL + SHIFT + Q | exits the program                           |
| ALT + CTRL + SHIFT + S | starts/stops handling of other hotkeys      |
| ALT + CTRL + SHIFT + T | pin active window (makes it always visible) |


### Build:

Install `gcc` and `make`:
1. Visit [MSYS2 Install](https://msys2.github.io/) and install `MSYS2` following the instructions.
2. Open `MSYS2 Shell` and use `pacman` to install `mingw-w64-x86_64-gcc`, `mingw-w64-x86_64-make`, and `mingw-w64-x86_64-cmake`.
3. Add `C:\msys64\mingw64\bin` (your `MSYS2` installation path) to the `PATH` environment variable.

Build:
```shell
git clone https://github.com/papplampe/virgo.git
cd virgo
mingw32-make
```
