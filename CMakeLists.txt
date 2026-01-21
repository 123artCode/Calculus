cmake_minimum_required(VERSION 4.1)
project(cmake_example)

add_subdirectory(pybind11)
pybind11_add_module(cmake_example src/main.cpp)
