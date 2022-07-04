This is a canadian compiled GCC compiler. It can build 32 bit windows programs on 64 bits windows. Sure you can use g++ -m32, but i find that sometimes it does not work, for example, windows 95 for unknown reasons. Built by the fast_io library's author

Unix Timestamp:1656900779.559503832
UTC:2022-07-04T02:12:59.559503832Z

fast_io:
https://github.com/cppfastio/fast_io

build	:	x86_64-linux-gnu
host	:	x86_64-w64-mingw32
target	:	i686-w64-mingw32

i686-w64-mingw32-g++ -v
Using built-in specs.
COLLECT_GCC=i686-w64-mingw32-g++
COLLECT_LTO_WRAPPER=d:/x86_64-windows-gnu/i686-w64-mingw32/bin/../libexec/gcc/i686-w64-mingw32/13.0.0/lto-wrapper.exe
Target: i686-w64-mingw32
Configured with: ../../../../gcc/configure --disable-nls --disable-werror --host=x86_64-w64-mingw32 --target=i686-w64-mingw32 --prefix=/home/cqwrteur/toolchains/x86_64-w64-mingw32/i686-w64-mingw32 --disable-libstdcxx-verbose --disable-sjlj-exceptions --enable-languages=c,c++ --with-gxx-libcxx-include-dir=/home/cqwrteur/toolchains/x86_64-w64-mingw32/i686-w64-mingw32/i686-w64-mingw32/include/c++/v1 --enable-multilib --with-multilib-list=32
Thread model: win32
Supported LTO compression algorithms: zlib
gcc version 13.0.0 20220704 (experimental) (GCC)
