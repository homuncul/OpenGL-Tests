cmake_minimum_required(VERSION 3.3)
project(OpenGL_Tests)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp)
add_executable(OpenGL_Tests ${SOURCE_FILES})