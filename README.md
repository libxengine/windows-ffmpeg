# windows-ffmpeg-module   

#### 当前版本

x64:7.1.1  
x86:7.1.1  
Arm:7.1.1
 
#### 介绍
此版本为动态库编译模式.  
此项目只提供ffmpeg的windows版本.包含了x86和x64,arm64版本  
此版本为官方最新正式版源码为基础编译.  
只有ffmpeg发布最新正式版本此项目才更新

#### 软件架构
包涵最新正式版本ffmpeg编译,无修改
包含了很多其他三方库音视频编解码器和硬件编解码器的支持  
你们可以使用ffmpeg的帮助查看支持的编解码器  

#### 安装教程

1.  通过git或者打包直接下载即可
2.  下载完毕可能需要解压
3.  进入目录后有ffmpeg.exe可以直接使用

#### 使用说明

1.  通过命令行,使用ffmpeg.exe ffplay.exe ffprobe.exe
2.  提供的版本只允许windows10 及以上系统使用

#### 包含三方库

```
ffmpeg version n7.1-ffmpeg-windows-build-helpers Copyright (c) 2000-2024 the FFmpeg developers
  built with gcc 10.2.0 (GCC)
  configuration: --pkg-config=pkg-config --pkg-config-flags=--static --extra-version=ffmpeg-windows-build-helpers --enable-version3 --disable-debug --disable-w32threads --arch=x86_64 --target-os=mingw32 --cross-prefix=/home/ubuntu/ffmpeg-windows-build-helpers/sandbox/cross_compilers/mingw-w64-x86_64/bin/x86_64-w64-mingw32- --enable-libcaca --enable-gray --enable-libtesseract --enable-fontconfig --enable-gmp --enable-libass --enable-libbluray --enable-libbs2b --enable-libflite --enable-libfreetype --enable-libfribidi --enable-libharfbuzz --enable-filter=drawtext --enable-libgme --enable-libgsm --enable-libilbc --enable-libmodplug --enable-libmp3lame --enable-libopencore-amrnb --enable-libopencore-amrwb --enable-libopus --enable-libsnappy --enable-libsoxr --enable-libspeex --enable-libtheora --enable-libtwolame --enable-libvo-amrwbenc --enable-libvorbis --enable-libwebp --enable-libzimg --enable-libzvbi --enable-libmysofa --enable-libopenjpeg --enable-libopenh264 --enable-libvmaf --enable-libsrt --enable-libxml2 --enable-opengl --enable-libdav1d --enable-gnutls --enable-vulkan --enable-libsvtav1 --enable-libvpx --enable-libaom --enable-nvenc --enable-nvdec --extra-libs=-lz --extra-libs=-lpng --extra-libs=-lm --extra-libs=-lfreetype --extra-libs=-lshlwapi --extra-libs=-lmpg123 --extra-libs=-lpthread --extra-cflags=-DLIBTWOLAME_STATIC --extra-cflags=-DMODPLUG_STATIC --extra-cflags=-DCACA_STATIC --enable-amf --enable-libmfx --enable-libaribcaption --enable-gpl --enable-frei0r --enable-librubberband --enable-libvidstab --enable-libx264 --enable-libx265 --enable-avisynth --enable-libaribb24 --enable-libxvid --enable-libdavs2 --enable-libxavs2 --enable-libxavs --extra-cflags='-mtune=generic' --extra-cflags=-O3 --enable-shared --disable-static --prefix=/home/ubuntu/ffmpeg-windows-build-helpers/sandbox/win64/ffmpeg_git_with_fdk_aac_n7.1_shared --enable-nonfree --enable-libfdk-aac --enable-decklink
  libavutil      59. 39.100 / 59. 39.100
  libavcodec     61. 19.100 / 61. 19.100
  libavformat    61.  7.100 / 61.  7.100
  libavdevice    61.  3.100 / 61.  3.100
  libavfilter    10.  4.100 / 10.  4.100
  libswscale      8.  3.100 /  8.  3.100
  libswresample   5.  3.100 /  5.  3.100
  libpostproc    58.  3.100 / 58.  3.100
```

#### 参与贡献

此仓库不提供Push