cmake_minimum_required(VERSION 4.2)
project(projekt)
set(CMAKE_EXPORT_COMPILE_COMMANDS ON)
add_executable(${PROJECT_NAME} main.cpp)

add_subdirectory(lib)

target_link_libraries(${PROJECT_NAME} PRIVATE mylib)
