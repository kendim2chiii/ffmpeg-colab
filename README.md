# FFmpeg 5.0
<div style="display: inline">
<img src="https://icon-library.com/images/ffmpeg-icon/ffmpeg-icon-20.jpg" style="width: 20px; height: 20px;">
<img src="https://colab.research.google.com/img/colab_favicon_256px.png" style="width: 20px; height: 20px;">
<div>
Static FFmpeg 5.0 binary for Google Colab

### [=] Installation
1. Clone this repository
```
!git clone https://github.com/XniceCraft/ffmpeg-colab.git
```
2. Install with provided script
```
!./ffmpeg-colab/install
```
3. Done

After installation you can remove the folder.

### [=] External Library
* libaom ```3.1.3-rc2```
* libass ```0.15.2```
* libbluray ```1.3.0```
* libdav1d ```0.9.2```
* libfdk-aac ```2.0.2```
* libfontconfig ```2.13.94```
* libfreetype ```2.11.0```
* libfribidi ```1.0.11```
* libkvazaar ```2.1.0```
* libmp3lame ```3.100```
* libopencore-amrnb ```0.1.5```
* libopencore-amrwb ```0.1.5```
* libopenh264 ```2.1.1```
* libopenjpeg ```2.4.0```
* libopus ```20210928```
* libshine ```3.1.1```
* libsoxr ```0.1.3```
* libsrt ```1.4.4```
* libvidstab ```20201110```
* libvmaf ```2.3.0```
* libvorbis ```1.3.7```
* libwebp ```1.2.2-rc1```
* libvpx ```1.10.0```
* libx264 ```20211230```
* libx265 ```3.5```
* libxvid ```1.3.7```
* libzimg ```3.0.3```
* zlib ```1.2.11```
* nv-codec-header ```20211113```

NVENC and NVDEC are supported.

### [=] FFmpeg Configuration
```
PKG_CONFIG_PATH="/content/build/lib/pkgconfig" CFLAGS="-I/content/build/include" LDFLAGS="-L/content/build/lib" ./configure --prefix=/content/build --pkg-config-flags="--static" --extra-cflags="-I/content/build/include" --extra-ldflags="-L/content/build/lib" --extra-libs="-lpthread -lm -lgomp" --ld="g++" --bindir="/content/build/bin" --disable-ffplay --disable-ffprobe --disable-doc --disable-htmlpages --disable-manpages --disable-podpages --disable-txtpages --enable-version3 --enable-gpl --enable-nonfree --enable-opencl --enable-opengl --disable-shared --enable-static --enable-libaom --enable-libass --enable-libbluray --enable-libdav1d --enable-libfdk-aac --enable-libfontconfig --enable-libfreetype --enable-libfribidi --enable-libkvazaar --enable-libmp3lame --enable-libopencore-amrnb --enable-libopencore-amrwb --enable-libopenh264 --enable-libopenjpeg --enable-libopus --enable-libshine --enable-libsoxr --enable-libsrt --enable-libvidstab --enable-libvmaf --enable-libvorbis --enable-libvpx --enable-libwebp --enable-libx264 --enable-libx265 --enable-libxvid --enable-libzimg --enable-zlib --enable-openssl --enable-cuvid --enable-ffnvcodec --enable-nvdec --enable-nvenc --enable-pthreads
```
