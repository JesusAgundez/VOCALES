cmake_minimum_required(VERSION 3.5)

project(VOCALES LANGUAGES C)

add_executable(VOCALES main.c)

install(TARGETS VOCALES
    LIBRARY DESTINATION ${CMAKE_INSTALL_LIBDIR})
