cmake_minimum_required(VERSION 3.14)
project(ToySTL)

# version
set(ToySTL_VERSION_MAJOR 0)
set(ToySTL_VERSION_MINOR 1)
set(ToySTL_VERSION_PATCH 1)
set(ToySTL_VERSION "${ToySTL_VERSION_MAJOR}.${ToySTL_VERSION_MINOR}.${ToySTL_VERSION_PATCH}")
message(STATUS "The version of this project is: ${ToySTL_VERSION}")

set(CMAKE_CXX_STANDARD 11)

add_executable(ToySTL main.cpp)