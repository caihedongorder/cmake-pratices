cmake_minimum_required(VERSION 3.10)

project(HELLO)
message(STATUS "This is Binary dir:" ${HELLO_BINARY_DIR})
message(STATUS "This is SOURCE dir:" ${HELLO_SOURCE_DIR})
add_subdirectory(src bin)
