cmake_minimum_required(VERSION 2.6)

set(CMAKE_C_COMPILER "gcc12")
set(CMAKE_CXX_COMPILER "g++12")

project(ImageLib)

add_subdirectory(src-IL)
add_subdirectory(src-ILU)
add_subdirectory(src-ILUT)

