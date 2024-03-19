cmake_minimum_required(VERSION 3.26)
project(Language_Build C)

set(CMAKE_C_STANDARD 11)
#set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -save-temps=obj")
#set(CMAKE_C_FLAGS "${CMAKE_CXX_FLAGS} -save-temps=obj")
#set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -g -O0")

add_executable(Language_Build main.c)
