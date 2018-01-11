cmake_minimum_required(VERSION 3.8)
project(untitled7)

set(CMAKE_C_STANDARD 90)

set(SOURCE_FILES main.c)
add_executable(untitled7 ${SOURCE_FILES})
target_link_libraries(untitled7 m)
target_link_libraries(untitled7 -fopenmp)