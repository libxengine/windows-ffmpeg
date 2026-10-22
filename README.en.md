# windows-ffmpeg-module

#### current version

x64:9.0.2  
x86:9.0.2  
Arm:9.0.2
 
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

#### Participate in Contribution

Pull is not available in this.