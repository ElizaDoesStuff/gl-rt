cmake_minimum_required(VERSION 3.30)
project(glrt)

add_executable(glrt Source/main.cpp)
target_link_libraries(glrt -libstdc++ -libgcc)
