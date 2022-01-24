# FFmpeg Google Colab
Static FFmpeg 5.0 binary for Google Colab

### [=] Installation
1. ```!git clone https://github.com/XniceCraft/ffmpeg-colab.git```
2. ```!mv ffmpeg-colab/bin/ffmpeg /usr/bin```
3. ```Done```

or install it with ./install (i'll add it soon)

### [=] External Library
* libaom
* libass
* libbluray
* libdav1d
* libfdk-aac
* libfontconfig
* libfreetype
* libfribidi
* libkvazaar
* libmp3lame
* libopencore-amrnb
* libopencore-amrwb
* libopenh264
* libopenjpeg
* libopus
* libshine
* libsoxr
* libsrt
* libvidstab
* libvmaf
* libvorbis
* libwebp
* libvpx
* libx264
* libx265
* libxvid
* libzimg
* zlib
* nv-codec-header

### [=] FFmpeg Configuration
```
PKG_CONFIG_PATH="/content/build/lib/pkgconfig" CFLAGS="-I/content/build/include" LDFLAGS="-L/content/build/lib" ./configure --prefix=/content/build --pkg-config-flags="--static" --extra-cflags="-I/content/build/include" --extra-ldflags="-L/content/build/lib" --extra-libs="-lpthread -lm -lgomp" --ld="g++" --bindir="/content/build/bin" --disable-ffplay --disable-ffprobe --disable-doc --disable-htmlpages --disable-manpages --disable-podpages --disable-txtpages --enable-version3 --enable-gpl --enable-nonfree --enable-opencl --enable-opengl --disable-shared --enable-static --enable-libaom --enable-libass --enable-libbluray --enable-libdav1d --enable-libfdk-aac --enable-libfontconfig --enable-libfreetype --enable-libfribidi --enable-libkvazaar --enable-libmp3lame --enable-libopencore-amrnb --enable-libopencore-amrwb --enable-libopenh264 --enable-libopenjpeg --enable-libopus --enable-libshine --enable-libsoxr --enable-libsrt --enable-libvidstab --enable-libvmaf --enable-libvorbis --enable-libvpx --enable-libwebp --enable-libx264 --enable-libx265 --enable-libxvid --enable-libzimg --enable-zlib --enable-openssl --enable-cuvid --enable-ffnvcodec --enable-nvdec --enable-nvenc --enable-pthreads
```
