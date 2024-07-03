cmake_minimum_required(VERSION 3.28)
project(basic_notions)

set(CMAKE_CXX_STANDARD 17)

add_executable(basic_notions main.cpp
        src/header.h
        src/test.cpp
        src/exercise.cpp)
