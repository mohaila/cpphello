cmake_minimum_required(VERSION 3.1)
project(hello CXX)
file(GLOB SRC *.cpp)
add_executable(cpphello ${SRC})