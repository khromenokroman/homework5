cmake_minimum_required(VERSION 3.5)

project(homework-05)

add_executable(statistics statistics.cpp)
set_target_properties(statistics PROPERTIES CXX_STANDARD 23 CXX_STANDARD_REQUIRED ON)

