cmake_minimum_required(VERSION 3.10)

project(desuscript)

set(CMAKE_RUNTIME_OUTPUT_DIRECTORY "${CMAKE_BINARY_DIR}")
set(CMAKE_C_STANDARD 99)

add_subdirectory(src/vm)
