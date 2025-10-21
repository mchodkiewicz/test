cmake_minimum_required(VERSION 3.15)

project(test_something)

add_library(test_something src/test_math.cpp include/test_something/test_math.h)
#target_include_directories(test_something INTERFACE ${CMAKE_CURRENT_SOURCE_DIR}/include)
include_directories(${CMAKE_CURRENT_SOURCE_DIR}/include)

