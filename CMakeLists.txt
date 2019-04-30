cmake_minimum_required(VERSION 3.10)
project(cmocka_play C)

set(CMAKE_C_STANDARD 11)

add_executable(cmocka_play main.c)

add_subdirectory(cmocka)

target_link_libraries(cmocka_play cmocka)
