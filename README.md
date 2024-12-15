# ffmepg_release
high gcc version build ffmpeg3.4.13
# 更新日志
## 2024/12/15
  -[x] Add: windows下mingw64开发环境，高版本的gcc编译ffmpeg3.4源码修改 <br>
  -[x] Add: libx264 export PKG_CONFIG_PATH=${PKG_CONFIG_PATH}:G:\x264-build\lib\pkgconfig <br>
  -[x] Add: ./configure --prefix=G:/ffmpeg --enable-gpl --enable-libx264 --disable-static --disable-htmlpages --enable-muxer=rtsp --enable-demuxer=rtsp --enable-protocol=rtmp --enable-protocol=rtsp --enable-protocol=http --enable-shared --enable-sdl2 --enable-ffplay --enable-ffprobe --enable-ffmpeg --enable-avresample --extra-cflags="-IG:/x264-build/include" --extra-ldflags="-LG:/x264-build/lib" <br>

