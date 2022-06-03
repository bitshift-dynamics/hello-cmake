cmake_minimum_required(VERSION 3.0)

project(hello-cmake)
add_executable(hello-cmake main.c)
install(TARGETS hello-cmake RUNTIME DESTINATION bin)
