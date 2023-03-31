cmake_minimum_required(VERSION 3.25)
project(AILibrary)

set(CMAKE_CXX_STANDARD 17)

add_library(AILibrary library.cpp)
target_include_directories(AILibrary PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/include)
