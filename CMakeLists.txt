cmake_minimum_required(VERSION 3.30)
project(glrt)

add_library(glrt Source/glrt.cpp)

add_executable(demo Demo/demo.cpp)
target_link_libraries(demo glrt -libstdc++ -libgcc)