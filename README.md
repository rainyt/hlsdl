HLSDL is a SDL2 backend for HashLink 
Read https://www.libsdl.org/ for more information on SDL

In order to compile on Windows, download the Development Libraries from SDL2 and unzip them into the hashlink/include/sdl directory, so you have the directories hashlink/include/sdl/include and hashlink/include/sdl/lib available.

## 说明
这是兼容了zyheaps的IME支持的功能

## Mac更新SDL
如果需要更新SDL时，请前往`https://github.com/libsdl-org/SDL/releases/tag/release-2.24.0`寻找最新的SDL版本，下载`SDL2-xxx.xx.xx.tar.gz`文件。

## 生成Makefile文件
请注意，文件夹不能存在空格。
```shell
./configure --prefix=/usr/local
```

## 编译SDL
如果非M系列的Mac，可删除`arch -x86_64`。
```shell
arch -x86_64 make
```

## 安装SDL
```shell
arch -x86_64 sudo make install
```