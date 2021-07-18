cmake_minimum_required(VERSION 3.10)

project(desuscript-vm)

set(CMAKE_C_STANDARD 99)

add_executable(${PROJECT_NAME} safe.c)
