# cmake_minimum_required(VERSION <specify CMake version here>)
project(HelloWorld C)

set(CMAKE_C_STANDARD 99)

add_executable(HelloWorld cmake-build-debug/HelloWorld.c)