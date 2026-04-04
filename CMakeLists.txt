cmake_minimum_required(VERSION 3.10)
project(rubiks-cube-scramble-engine C)

set(CMAKE_C_STANDARD 99)

include_directories(scramble_engine)

add_executable(scramble_engine
        scramble_engine/scramble_engine.c
        scramble_engine/scramble_engine.h
        example.c)
