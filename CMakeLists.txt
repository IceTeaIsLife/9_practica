cmake_minimum_required(VERSION 3.17)
project(9_practica C)

set(CMAKE_C_STANDARD 99)
set(CMAKE_C_STANDARD_REQUIRED ON)

add_definitions(-DPNEUMO_SIMULATE -DPNEUMO_DEBUG)
add_executable(9_practica automata.h automata.c)