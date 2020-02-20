cmake_minimum_required (VERSION 3.16)
project(microtar)

add_library(microtar src/microtar.c)
target_include_directories(microtar PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/src)

install(TARGETS microtar)
