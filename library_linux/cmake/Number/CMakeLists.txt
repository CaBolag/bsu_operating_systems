cmake_minimum_required(VERSION 3.21)
project(Number)

set(CMAKE_CXX_STANDARD 20)
set(SOURCE_FILES Number.cpp)

add_library(Number STATIC ${SOURCE_FILES})
