
cmake_minimum_required(VERSION 3.4.1)

project(libogg)

include_directories(include)

add_library(
        ogg-lib
        SHARED
        src/bitwise.c
        src/framing.c
)
