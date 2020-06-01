cmake_minimum_required(VERSION 3.15)
project(Lab4_2)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(Lab4_2
        CSVparser.cpp
        CSVparser.hpp
        VectorSorting.cpp)
