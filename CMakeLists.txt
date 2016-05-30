cmake_minimum_required(VERSION 3.5)
project(pngcheck)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES pngcheck.c)
add_executable(pngcheck ${SOURCE_FILES})