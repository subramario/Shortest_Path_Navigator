cmake_minimum_required(VERSION 2.8)
project(Shortest_Path)

## Project specific configurations go here

# enable c++11 support
set (CMAKE_CXX_FLAGS "-std=c++11 -Wall ${CMAKE_CXX_FLAGS}")

# create the main executable - add additional .cpp files if needed
add_executable(shortest Shortest_Path.cpp )

