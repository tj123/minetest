

```bash

vcpkg install zlib curl[winssl] openal-soft libvorbis libogg sqlite3 freetype luajit gmp jsoncpp --triplet x64-windows

/D/ProgramFiles/vcpkg/downloads/tools/cmake-3.20.2-windows/cmake-3.20.2-windows-i386/bin/cmake . -G"Visual Studio 15 2017 Win64" -DCMAKE_TOOLCHAIN_FILE=D:/ProgramFiles/vcpkg/scripts/buildsystems/vcpkg.cmake -DCMAKE_BUILD_TYPE=Release -DENABLE_GETTEXT=OFF -DENABLE_CURSES=OFF

cmake --build . --config Release

```
