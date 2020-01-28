cmake_minimum_required(VERSION 3.15)
project(tlpi C)

set(CMAKE_C_STANDARD 99)
include_directories(include)
include_directories(lib)

add_executable(tlpi_exec main.c)
add_subdirectory(lib)
add_subdirectory(fileio)
