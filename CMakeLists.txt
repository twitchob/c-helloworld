cmake_minimum_required(VERSION 3.24)
project(helloworld C)

set(CMAKE_C_STANDARD 99)

add_executable(helloworld main.c)

set(CMAKE_EXPORT_COMPILE_COMMANDS ON)