cmake_minimum_required(VERSION 3.10)

add_subdirectory(source)

add_executable(dynamic_block2 program.c)
target_link_libraries(dynamic_block2 PUBLIC source)

add_executable(static_block2 program.c)
target_link_libraries(static_block2 PUBLIC source)
