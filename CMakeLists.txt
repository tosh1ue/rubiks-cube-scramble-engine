cmake_minimum_required(VERSION 3.10)
project(Rubiks-Cube-scramble-drawer C)

set(CMAKE_C_STANDARD 99)

include_directories(draw_scramble)

add_executable(draw-scramble
        draw_scramble/draw_scramble.c
        draw_scramble/draw_scramble.h
        example.c)
