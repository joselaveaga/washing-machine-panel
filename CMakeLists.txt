cmake_minimum_required(VERSION 3.13)
include(pico_sdk_import.cmake)

project(Fibonacci C CXX ASM)
set(CMAKE_C_STANDARD 11)
set(CMAKE_CXX_STANDARD 17)
set(PICO_BOARD pico_w)


pico_sdk_init()

add_subdirectory(fibonacci)
add_subdirectory(hello_7segment)