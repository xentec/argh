cmake_minimum_required(VERSION 3.1)

project(argh)

add_library(argh INTERFACE)
target_include_directories(argh INTERFACE "${CMAKE_CURRENT_LIST_DIR}")
