cmake_minimum_required(VERSION 3.26)
project(abstractclass)

set(CMAKE_CXX_STANDARD 17)

add_executable(abstractclass main.cpp
        header.cpp
        header.h
        tests.cpp)
