cmake_minimum_required(VERSION 3.6)
project(linker)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp)
add_executable(linker ${SOURCE_FILES})