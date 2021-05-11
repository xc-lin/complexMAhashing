cmake_minimum_required(VERSION 3.19)
project(Q1 C)

set(CMAKE_C_STANDARD 99)

add_executable(
        Q1
        bits.c
        bits.h
        hash.c
        hash.h
        pages.c)