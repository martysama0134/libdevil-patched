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

## how to change compiler:
Open `DevIL/DevIL/CMakeLists.txt`, and edit this:

```sh
set(CMAKE_C_COMPILER "gcc12")
set(CMAKE_CXX_COMPILER "g++12")
```

Remove this part if you want to use the default CC CXX values.

## how to specify environment:

Open `DevIL/DevIL/CMakeLists.txt`, and add this:

```
set(CMAKE_CXX_FLAGS -m32)
set(CMAKE_CXX_FLAGS -L/usr/local/lib32/gcc12/)
```
