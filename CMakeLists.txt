cmake_minimum_required(VERSION 3.8)

add_library(math INTERFACE)
target_include_directories(math INTERFACE ${CMAKE_CURRENT_SOURCE_DIR})
set_property(TARGET game PROPERTY CXX_STANDARD 17)