cmake_minimum_required(VERSION 3.16)
project(DSwet1S24)

set(CMAKE_CXX_STANDARD 14)

include_directories(code)

add_executable(DSwet1S24
        code/main24b1.cpp
        code/pirates24b1.cpp
        code/pirates24b1.h
        code/wet1util.h)
