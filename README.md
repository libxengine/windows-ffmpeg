# windows-ffmpeg-module   

#### 当前版本

x64:9.0.2  
x86:9.0.2  
Arm:9.0.2
 
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
ffmpeg version n9.0.2-28-g669f5ab083-20261015 Copyright (c) 2000-2026 the FFmpeg developers
  built with gcc 16.2.0 (crosstool-NG 1.29.0.7_b1a94f6)
  configuration: --prefix=/ffbuild/prefix --pkg-config-flags=--static --pkg-config=pkg-config --cross-prefix=x86_64-w64-mingw32- --arch=x86_64 --target-os=mingw32 --enable-nonfree --enable-gpl --enable-version3 --disable-debug --enable-shared --disable-static --disable-w32threads --enable-pthreads --enable-iconv --enable-zlib --enable-libxml2 --enable-libvmaf --disable-libxcb --disable-xlib --enable-fontconfig --enable-libharfbuzz --enable-libfreetype --enable-libfribidi --enable-lcms2 --enable-vulkan --enable-libdav1d --enable-libvorbis --enable-librav1e --enable-librsvg --disable-libpulse --enable-gmp --enable-lzma --enable-liblcevc-dec --enable-opencl --enable-amf --enable-libaom --enable-avisynth --enable-chromaprint --enable-libdavs2 --enable-libdvdread --enable-libdvdnav --enable-libfdk-aac --enable-ffnvcodec --enable-cuda-llvm --enable-frei0r --enable-libgme --enable-libkvazaar --enable-libaribb24 --enable-libaribcaption --enable-libass --enable-libbluray --enable-libjxl --enable-libmp3lame --enable-libopus --enable-libplacebo --enable-librist --enable-libssh --enable-libtheora --enable-libvpx --enable-libwebp --enable-libzmq --enable-lv2 --enable-libvpl --enable-openal --enable-liboapv --enable-libopencore-amrnb --enable-libopencore-amrwb --enable-libopenh264 --enable-libopenjpeg --enable-libopenmpt --enable-librubberband --enable-schannel --enable-sdl2 --enable-libsnappy --enable-libsoxr --enable-libsrt --enable-libsvtav1 --enable-libtwolame --enable-libuavs3d --disable-libdrm --enable-vaapi --enable-vapoursynth --enable-libvidstab --enable-libvvenc --disable-whisper --enable-libx264 --enable-libx265 --enable-libxavs2 --enable-libxvid --enable-libzimg --enable-libzvbi --extra-cflags=-DLIBTWOLAME_STATIC --extra-cxxflags= --extra-libs=-lgomp --extra-ldflags=-pthread --extra-ldexeflags= --cc=x86_64-w64-mingw32-gcc --cxx=x86_64-w64-mingw32-g++ --ar=x86_64-w64-mingw32-gcc-ar --ranlib=x86_64-w64-mingw32-gcc-ranlib --nm=x86_64-w64-mingw32-gcc-nm --extra-version=20261015
  libavutil      61.  1.102 / 61.  1.102
  libavcodec     63.  1.102 / 63.  1.102
  libavformat    63.  1.102 / 63.  1.102
  libavdevice    63.  1.102 / 63.  1.102
  libavfilter    12.  1.102 / 12.  1.102
  libswscale     10.  1.102 / 10.  1.102
  libswresample   7.  1.102 /  7.  1.102
```

#### 参与贡献

此仓库不提供Push