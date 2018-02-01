set(CMAKE_EXPORT_COMPILE_COMMANDS on)

include_directories(../hello_static/include)
link_directories(../hello_static/lib)
add_executable(hello main.c)
target_link_libraries(hello libhello)
