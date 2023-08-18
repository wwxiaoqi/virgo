virgo
=====
适用于 Windows 操作系统的虚拟桌面管理器。

> [English](README.md) | 中文

### 特点：
- 占用资源少，可执行文件小于 `10KB`，在运行时内存占用少于 `1MB`
- 提供 `4` 个虚拟桌面（如果您修改并重新编译代码，可以增加更多虚拟桌面）
- 只显示一个托盘图标，显示当前所在的虚拟桌面编号


### 快捷键：

| 快捷键                 | 快捷键介绍                         |
| ---------------------- | ---------------------------------- |
| ALT + 1..4             | 切换到 1 至 4 号虚拟桌面           |
| CTRL + 1..4            | 将活动窗口移动到 1 至 4 号虚拟桌面 |
| ALT + CTRL + SHIFT + Q | 退出程序                           |
| ALT + CTRL + SHIFT + S | 开启/停止监听快捷键                |
| ALT + CTRL + SHIFT + T | 固定活动窗口（使其始终可见）       |


### 构建：

安装 `gcc` 和 `make`：
1. 访问 [MSYS2 安装](https://msys2.github.io/)，根据指示安装 `MSYS2`
2. 打开 `MSYS2 Shell`，用 `pacman` 安装 `mingw-w64-x86_64-gcc` 和 `mingw-w64-x86_64-make` 和 `mingw-w64-x86_64-cmake`
3. 环境变量 `PATH` 中添加 `C:\msys64\mingw64\bin`（你的 `MSYS2` 安装路径）

构建：
```shell
git clone https://github.com/papplampe/virgo.git
cd virgo
mingw32-make
```
