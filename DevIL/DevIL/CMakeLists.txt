cmake_minimum_required(VERSION 2.6)

set(CMAKE_C_COMPILER "cc")
set(CMAKE_CXX_COMPILER "c++")

project(ImageLib)

add_subdirectory(src-IL)
add_subdirectory(src-ILU)
add_subdirectory(src-ILUT)

