cmake_minimum_required(VERSION 3.15)
project(NoobServer)

set(CMAKE_CXX_STANDARD 14)

add_executable(NoobServer main.cpp server.cpp server.h)
