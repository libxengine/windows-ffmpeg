# windows-ffmpeg-module

#### current version

x64:7.1.1  
x86:7.1.1  
Arm:7.1.1
 
#### introduce
This version is a dynamic library compilation mode.
This project only provides the windows version of ffmpeg. Both x86 and x64 and arm64 versions are included.
This version is compiled based on the latest official version of the official source code.
Only ffmpeg releases the latest official version of this project will be updated

#### Software Architecture
Compile the latest official version of ffmpeg without modification
Contains support for many other third-party library audio and video codecs and hardware codecs
You can use the help of ffmpeg to check the supported codecs

#### Installation tutorial

1. Download directly through git or package
2. It may need to be unzipped after downloading
3. After entering the directory, ffmpeg.exe can be used directly

#### Instructions for use

1. Through the command line, use ffmpeg.exe ffplay.exe ffprobe.exe
2. The provided version is only allowed to be used by systems above windows10

#### Contains third party libraries

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

#### Participate in Contribution

Pull is not available in this.