# libdevil
Fork of https://openil.sourceforge.net/download.php

# FreeBSD Configuration

## deps
```sh
pkg install cmake
```

## how to clean up:
```sh
cd DevIL/DevIL
rm -f CMakeCache.txt
make clean
```

## how to compile:
```sh
cd DevIL/DevIL
cmake CMakeLists.txt
make install
```
