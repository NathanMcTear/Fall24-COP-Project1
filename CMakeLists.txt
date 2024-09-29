cmake_minimum_required(VERSION 3.29)
project(Project1)

set(CMAKE_CXX_STANDARD 14)

include_directories(Project1/test-unit)

add_executable(Project1
    Project1/src/main.cpp
    Project1/test-unit/test.cpp)
