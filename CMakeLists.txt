
cmake_minimum_required(VERSION 3.10)

project(second)

set(CMAKE_CXX_STANDART 11)
set(CMAKE_CXX_STANDART_REQUIRED True)

include_directories(src)

add_executable(second src/main.cpp src/utils.cpp src/utils.hpp)